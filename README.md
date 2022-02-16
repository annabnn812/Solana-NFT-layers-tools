# Solana-NFT-layers-tools

```sh
npm install
```


```sh
npm run generate
```
The program will output all the images in the `build/images` directory along with the metadata files in the `build/json` directory. Each collection will have a `_metadata.json` file that consists of all the metadata in the collection inside the `build/json` directory. The `build/json` folder also will contain all the single json files that represent each image file. 


Программа выведет все изображения в каталоге "build/images" вместе с файлами метаданных в каталоге "build/json`. Каждая коллекция будет иметь файл `_metadata.json`, который состоит из всех метаданных коллекции внутри каталога `build/json`. Папка `build/json` также будет содержать все отдельные файлы json, которые представляют каждый файл изображения.


```sh
node utils/rarity.js  
```
shows the characteristics of the image and the percentages of each attribute across your collection 


показывает характеристики созданного файла и шанс выпадения 


```sh
node utils/pixelate.js
```
In order to convert images into pixelated images you would need a list of images that you want to convert. So run the generator first.

Для преобразования изображений в пиксельные изображения вам понадобится список изображений, которые вы хотите преобразовать. Так что сначала запустите генератор.


```sh
node utils/update_info.js  
```
Updating baseUri for IPFS and description 

Если меняется файл IPFS или другая инфа в файле config.js запустить эту команду , она поменяет везде. 


```sh
node utils/regenerateMetadata.js 
```
If you need to update Metadata or this file has been deleted, then a new one will be created

Если нужно обновить Metadata или этот файл был стерт, то он создастся новый


