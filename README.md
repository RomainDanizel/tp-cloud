TP cloud groupe 17  

Melvyn Dadure
Aymeric Gillet
Louis Fleury
Romain Danizel

# Tag

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** |  | [optional] 
**name** | **string** |  | [optional] 

[[Back to Model list]](../../README.md#documentation-for-models) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to README]](../../README.md)

# User

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**completion** | **int** | Pourcentage of the game done | [required] 
**finished** | **bool** |  | [required] [default to false]
**device** | **string** | Platform use | [required] 
**playtime** | **int** | Users played time in minutes | [required] 
**useditem** | **string** |  | [required] 
**playerslocation** | **int** | Zone number where the player is at the end of its play session | [required] 

[[Back to Model list]](../../README.md#documentation-for-models) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to README]](../../README.md)

# Swagger\Client\UserApi

All URIs are relative to *https://virtserver.swaggerhub.com/t3551/Gram/1.0.0*

Method | HTTP request | Description
------------- | ------------- | -------------
[**createUser**](UserApi.md#createuser) | **POST** /user | Create user
[**createUsersWithArrayInput**](UserApi.md#createuserswitharrayinput) | **POST** /user/createWithArray | Creates list of users with given input array
[**createUsersWithListInput**](UserApi.md#createuserswithlistinput) | **POST** /user/createWithList | Creates list of users with given input array
[**deleteUser**](UserApi.md#deleteuser) | **DELETE** /user/{username} | Delete user
[**getUserData**](UserApi.md#getuserdata) | **GET** /user/{username} | Get user information
[**updateUser**](UserApi.md#updateuser) | **PUT** /user/{username} | Updated user

# ApiResponse

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**code** | **int** |  | [optional] 
**type** | **string** |  | [optional] 
**message** | **string** |  | [optional] 

[[Back to Model list]](../../README.md#documentation-for-models) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to README]](../../README.md)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)
