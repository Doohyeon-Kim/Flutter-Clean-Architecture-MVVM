# flutter_clean_architecture

Flutter Clean Architecture made by Doohyeon Kim.

![dooadex_flutter_architecture_mvvvm](https://user-images.githubusercontent.com/92246475/161225332-f066c4e4-7b9f-4e90-b4e4-c73c4ba22e1b.png)

## Directory Structure

```bash
.
├── README.md
├── android
├── ios
├── lib
│   ├── components
│   │   └── component.dart
│   ├── configs
│   │   ├── app_config.dart
│   │   ├── palette.dart
│   │   └── themes
│   ├── constants
│   │   ├── api_path.dart
│   │   ├── app_constants.dart
│   │   ├── asset_path.dart
│   │   ├── exception_constants.dart
│   │   ├── http_constants.dart
│   │   └── named_routes.dart
│   ├── data
│   │   ├── data_sources
│   │   │   ├── local
│   │   │   │   └── sample_local_data_source.dart
│   │   │   └── remote
│   │   │       └── sample_remote_data_source.dart
│   │   ├── entities
│   │   │   └── sample_entity.dart
│   │   └── repositories
│   │       └── sample_repository_impl.dart
│   ├── domain
│   │   ├── models
│   │   │   └── sample_model.dart
│   │   ├── repositories
│   │   │   └── sample_repository.dart
│   │   ├── translator
│   │   │   └── sample_translator.dart
│   │   └── usecases
│   │       └── sample_usecase.dart
│   ├── main.dart
│   ├── presentation
│   │   ├── view_models
│   │   │   └── sample_view_model.dart
│   │   └── views
│   │       └── sample_view.dart
│   ├── screens
│   ├── services
│   │   ├── error
│   │   │   └── error_message_handler.dart
│   │   ├── firebase
│   │   ├── native_api
│   │   │   ├── local_notifivation.dart
│   │   │   └── shared_preference.dart
│   │   └── network
│   │       ├── http
│   │       └── rest_api
│   └── utilities
│       └── logger.dart
├── pubspec.lock
├── pubspec.yaml
└── test
    └── widget_test.dart
```
