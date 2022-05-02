# pydownloader
PyDownloader Libreria Encargada de Procesar Y Descargar Enlaces

# Codigo De Ejemplo
``` 
from pydownloader import Downloader

downloader = Downloader()
file = downloader.download_url(url,progressfunc=progresshook,args=(downloader))
if not downloader.stoping:
   if file:
      print(file)
```
