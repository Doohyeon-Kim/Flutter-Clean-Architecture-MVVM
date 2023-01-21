# flutter_clean_architecture_mvvm

Flutter Clean Architecture made by Doohyeon Kim.


![Mobile Clean Architecture-MVVM](https://user-images.githubusercontent.com/92246475/213839776-af65b27b-4545-4f2d-b78a-9f21ea7ab7bb.png)


## Directory Structure

```bash
.
├── README.md
├── android
├── ios
├── lib
│   ├── common
│   │   ├── error
│   │   │   ├── <project_name>_error
│   │   │   │   ├── <project_name>_error.dart
│   │   │   │   ├── <project_name>_errors.dart
│   │   │   │   ├── <project_name>_errors_factory.dart
│   │   │   │   └── error_type.dart
│   │   │   ├── error_message_handler
│   │   │   │   ├── error_message.dart
│   │   │   │   └── error_message_handler.dart
│   │   │   └── exception
│   │   │       ├── exception.dart
│   │   │       └── exception_factory.dart
│   │   ├── http
│   │   │   ├── http_client.dart
│   │   │   ├── http_request.dart
│   │   │   ├── http_response.dart
│   │   │   └── http_utils.dart
│   │   ├── logger
│   │   │   ├── logger.dart
│   │   │   ├── logger_factory.dart
│   │   │   └── logger_utils.dart
│   │   ├── network
│   │   │   └── connectivity.dart
│   │   └── services
│   │       ├── native_api
│   │       │   ├── local_notification.dart
│   │       │   ├── secure_storage.dart
│   │       │   └── shared_preference.dart
│   │       └── token
│   │           └── token_service.dart
│   ├── components
│   │   ├── bars
│   │   │   ├── navigation_bar
│   │   │   │   ├── navigation_bar.dart
│   │   │   │   └── navigation_bar_factory.dart
│   │   │   └── progress_bar
│   │   │       ├── progress_bar.dart
│   │   │       └── progress_bar_factory.dart
│   │   ├── buttons
│   │   │   ├── <project_name>_button
│   │   │   │   ├── <project_name>_button.dart
│   │   │   │   └── <project_name>_button_factory.dart
│   │   │   ├── circular_button
│   │   │   │   ├── circular_button.dart
│   │   │   │   └── circular_button_factory.dart
│   │   │   ├── outlined_button
│   │   │   │   ├── outlined_button.dart
│   │   │   │   └── outlined_button_factory.dart
│   │   │   ├── switch_button
│   │   │   │   ├── switch_button.dart
│   │   │   │   └── switch_button_factory.dart
│   │   │   └── text_button
│   │   │       ├── text_button.dart
│   │   │       └── text_button_factory.dart
│   │   ├── dialogs
│   │   │   ├── <project_name>_dialog.dart
│   │   │   └── <project_name>_dialog_factory.dart
│   │   ├── figures
│   │   │   └── circle
│   │   │       ├── circle.dart
│   │   │       └── circle_factory.dart
│   │   ├── indicators
│   │   │   └── progress_indicator
│   │   │       ├── progress_indicator.dart
│   │   │       └── progress_indicator_factory.dart
│   │   └── text_fields
│   │       ├── outline_text_field
│   │       │   ├── outline_text_field.dart
│   │       │   └── outline_text_field_factory.dart
│   │       └── underline_text_field
│   │           ├── underline_text_field.dart
│   │           └── underline_text_field_factory.dart
│   ├── configs
│   │   ├── app_config.dart
│   │   ├── http_config.dart
│   │   └── palette
│   │       ├── <project_name>_color.dart
│   │       └── <project_name>_typo.dart
│   ├── constants
│   │   ├── path
│   │   │   ├── api_path.dart
│   │   │   ├── asset_path.dart
│   │   │   ├── route_path.dart
│   │   │   └── url_path.dart
│   │   └── sizer
│   │       ├── sizer.dart
│   │       └── unit_size.dart
│   ├── data
│   │   ├── data_sources
│   │   │   ├── local
│   │   │   │   └── sample_local_data_source.dart
│   │   │   └── remote
│   │   │       └── sample_remote_data_source.dart
│   │   ├── entities
│   │   │   └── sample_entity.dart
│   │   ├── mapper
│   │   │   └── sample_mapper.dart
│   │   └── repositories
│   │       └── sample_repository_impl.dart
│   ├── domain
│   │   ├── models
│   │   │   └── sample_model.dart
│   │   ├── repositories
│   │   │   └── sample_repository.dart
│   │   └── use_cases
│   │       └── sample_use_case.dart
│   ├── main.dart
│   ├── presentation
│   │   ├── pages
│   │   │   └── home_page.dart
│   │   ├── view_models
│   │   │   └── sample_view_model.dart
│   │   └── views
│   │       └── sample_view.dart
│   ├── sdk
│   │   ├── apple
│   │   │   ├── apple_sdk.dart
│   │   │   └── apple_sdk_manager.dart
│   │   ├── datadog
│   │   │   ├── datadog_sdk.dart
│   │   │   └── datadog_sdk_manager.dart
│   │   ├── firebase
│   │   │   ├── firebase_sdk.dart
│   │   │   └── firebase_sdk_manager.dart
│   │   └── kakao
│   │       ├── kakao_sdk.dart
│   │       └── kakao_sdk_manager.dart
│   └── utilities
│       ├── controller
│       │   ├── button
│       │   │   ├── base_button_controller.dart
│       │   │   └── button_controller.dart
│       │   └── text_field
│       │       ├── base_text_field_controller.dart
│       │       └── text_field_controller.dart
│       ├── handler
│       │   └── format_handler.dart
│       ├── parser
│       │   └── parser.dart
│       └── validator
│           ├── reg_exp_pattern.dart
│           └── validator.dart
├── local.properties
├── pubspec.lock
├── pubspec.yaml
└── test
    └── widget_test.dart
```
