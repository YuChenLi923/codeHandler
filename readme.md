## codeHandler

基于js，对常见的编码格式进行编码和解码。之前的某个项目中，要求基于base64加密传输,本来可以使用自带btoa(),atob(),但是考虑到兼容性问题。打算写一个简单的用于编码和解码的js库。目前仅支持base64编码和解码，以后会逐渐支持各种格式的编码和解码。


## 快速开始

```
    console.log(codeHandler.encode('asd哈哈哈','base64'));

```

## 方法及参数说明

codeHandler.encode( str , type) 

将str字符串编码为type类型的字符串

- str 字符串,必须,需要编码的字符串
- type 字符串,必须,编码的格式。可选:base64

codeHandler.decode( str , type)

将str字符串按照type类型解码

- str 字符串,必须,需要解码的字符串
- type 字符串,必须,解码的格式 可选:base64