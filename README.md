# Solana-NFT-layers-tools

npm install

npm run generate

node utils/rarity.js  
shows the characteristics of the image and the percentages of each attribute across your collection 
показывает характеристики созданного файла и шанс выпадения 


node utils/pixelate.js
In order to convert images into pixelated images you would need a list of images that you want to convert. So run the generator first.
Для преобразования изображений в пиксельные изображения вам понадобится список изображений, которые вы хотите преобразовать. Так что сначала запустите генератор.


node utils/update_info.js  
Updating baseUri for IPFS and description 
Если меняется файл IPFS или другая инфа в файле config.js запустить эту команду , она поменяет везде. 


node utils/regenerateMetadata.js 
If you need to update Metadata or this file has been deleted, then a new one will be created
Если нужно обновить Metadata или этот файл был стерт, то он создастся новый


