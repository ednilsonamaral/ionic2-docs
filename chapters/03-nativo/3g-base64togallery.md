Base64 To Gallery
========  
```$ cordova plugin add cordova-base64-to-gallery ```
  
Repositório: [https://github.com/Nexxa/cordova-base64-to-gallery](https://github.com/Nexxa/cordova-base64-to-gallery)  
Este plugin permite a você salvar dados base64 como uma imagem no formato png em seu dispositivo.  

Plataformas suportadas
-----
- Android  
- iOS  
- Windows Phone 8   

Uso  
-----

``` javascript 

import {Base64ToGallery} from 'ionic-native';


Base64ToGallery.base64ToGallery(base64Data, 'img_').then(
  res => console.log("Saved image to gallery ", res),
  err => console.log("Error saving image to gallery ", err)
); 
```

Métodos de instância
-----

``` base64ToGallery(data, prefix) ```

Converte uma string base64 em um arquivo de imagem na galeria do dispositivo

| Parâmetro | Tipo   | Detalhes |
| --------- | ------ | -------  |
| data      |        |          |
| prefixo   |        |          |
