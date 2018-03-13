# Convert Mp3

## Introduction
@TODO

## API
### Convert Mp3 from videos' url
Call Get API with params

	method: GET
	params: token

Example
From url need to be converted `https://example.com`
Input string as JSON `{"url":"https://example.com"}`
Encrypt input to create token
+ Encrypt method: aes-128-ecb

+ url: https://example.com
+ input: {"url":"https://example.com"}
+ token: da17cd8b9f0c7590f8f9cbd255c49d84507be389b88075fbd12f6436984abcfb


fullUrl: https://do2.tinker.press/convert-mp3?
token=da17cd8b9f0c7590f8f9cbd255c49d84507be389b88075fbd12f6436984abcfb

## Jenkins

### Setup WebHook
@TODO
@TODO

### Setup
