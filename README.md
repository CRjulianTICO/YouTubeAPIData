# YouTubeAPIData
Sample of the DATA API of YouTube in Spanish 
# YouTubeDataAPISample
A sample of youtube data api

Ejemplo de uso de la API DATA de YouTube por medio de APIKEY

  Primero se debe crear un proyecto en:
  https://console.cloud.google.com

  *Ir al menu y seleccionar APIs y Servicios
  *Seleccionar Biblioteca y buscar la API DATA de YouTube
  *Luego crear credenciales y seleccionar APIKEY
  *Se restringe
  
  Despues se debe ir al siguiente link y seleccionar en la parte de la derecha search.list(se buscan canales videos y playlists)
  https://developers.google.com/youtube/v3/code_samples/python#search_by_keyword
  *Crear un archivo .py y pegar el codigo en el link anterior
  *Actualizar los prints a python3(agregar los parentesis)
  
  Acontinuacion debera abrir cmd (en windows) o el sudo linux y 
  poner para Windoes: cd C:\DIRECCION DE PYTHON\Python\Python37-12\Scripts
  Ya al acceder al power shell se debe de poner import pip (si es que no lo tiene) 
  y luego poner: pip install --upgrade google-api-python-client (mas informacion: https://developers.google.com/api-client-library/python/start/installation)
  Y tambien: pip install --upgrade oauth2client
  
  Despues debe copiar la APIKEY y pegarlar en DEVELOPER_KEY = 'AQUI PONE EL APIKEY'
  
  Y para finalizar en las lineas:
  argparser.add_argument("--q", help="Search term", default="python machine learning") Donde dice default es para lo que quiere buscar
  argparser.add_argument("--max-results", help="Max results", default=10) Donde dice default es limitar la busqueda
  
  
  
  
  
Luego se debe de ir a la parte de APIs y servicios, y seleccionar biblioteca buscar la API DATA de YouTube
