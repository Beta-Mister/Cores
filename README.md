# Custom Database de Cores Beta para Mister

En este repositorio se recopilan cores beta no incluidos en el script de Mister [**"Update_all"**](https://github.com/theypsilon/Update_All_MiSTer/blob/master/update_all.sh). Este proyecto está basado en [DB-Template_MiSTer](https://github.com/theypsilon/DB-Template_MiSTer/) desarrolado por [theypsilon](https://github.com/theypsilon)


## ¿Cómo añadir este repositorio para que Update_all lo utilice?


Existen dos formas de hacerlo:

1. La opción más sencilla es descargar el siguiente archivo .zip [Beta-Mister_Cores.zip](https://raw.githubusercontent.com/Beta-Mister/Cores/db/downloader_Beta-Mister_Cores.zip) y extraer el fichero **"downloader_Beta-Mister_Cores.ini"** en la raíz de la tarjeta Micro SD (también se puede extraer en la carpeta "downloader" de la raíz). 

2. Se puede editar de forma manual el fichero **downloader.ini** y añadir al final lo siguiente:
   
```ini
[Beta-Mister/Cores]
db_url = https://raw.githubusercontent.com/Beta-Mister/Cores/db/db.json.zip
```

En ambos casos, solo es necesario hacerlo una vez y luego cada vez que se ejecute el script [**"Update_all"**](https://github.com/theypsilon/Update_All_MiSTer/blob/master/update_all.sh) se descargarán los ficheros actualizados de este repositorio. 




### English version ###
# Custom Beta Core Database for MiSTer

This repository collects beta cores that are not included in the MiSTer [**"Update_all"**](https://github.com/theypsilon/Update_All_MiSTer/blob/master/update_all.sh) script. This project is based on [DB-Template_MiSTer](https://github.com/theypsilon/DB-Template_MiSTer/) developed by [theypsilon](https://github.com/theypsilon).


## How to add this repository for use with Update_all?


There are two ways to do this:

1. The simplest option is to download the following .zip file: [Beta-Mister_Cores.zip](https://raw.githubusercontent.com/Beta-Mister/Cores/db/downloader_Beta-Mister_Cores.zip) and extract the **"downloader_Beta-Mister_Cores.ini"** file to the root of your Micro SD card (it can also be extracted to the "downloader" folder at the root).

2. You can manually edit the **downloader.ini** file and add the following to the end:
   
```ini
[Beta-Mister/Cores]
db_url = https://raw.githubusercontent.com/Beta-Mister/Cores/db/db.json.zip
```

In either case, you only need to do this once; thereafter, every time the [**"Update_all"**](https://github.com/theypsilon/Update_All_MiSTer/blob/master/update_all.sh) script runs, the updated files from this repository will be downloaded.
