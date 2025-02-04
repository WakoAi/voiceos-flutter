# openapi.model.LanguageModelCost

## Load the model package
```dart
import 'package:openapi/api.dart';
```

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**provider** | [**WakoApiModelsLanguageModelProvider**](WakoApiModelsLanguageModelProvider.md) | The provider of the language model. | 
**cost** | **num** | The cost for the language model usage. Returns zero, if the provider account you provided was used. | 
**inputTokens** | **int** | The number of input tokens used for the language model. | 
**outputTokens** | **int** | The number of output tokens used for the language model. | 
**external_** | **bool** | Whether the provider account you provided was used. If true, the cost will be zero. | 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


