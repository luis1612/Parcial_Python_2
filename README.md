

# Parcial Python electiva
# Project2
# LUIS IBARGUEN
# ANDRES VELEZ

## Para ejecutar la aplicación Flask en el símbolo del sistema, use $ python app.py

### Heroku Link: 

##  Carpeta 
* carpeta de datos
    * carpeta de datos sin procesar  
        * archivos csv  
            * dataMathNaional.csv
            * dataReadNational.csv
        * jupyter notebook  para limpiar datos llamados crear nuevos marcos de datos y conectar nuevos marcos de datos a postgres
        * Limpiar archivos csv: 
            * female_math_data.csv
            * female_reading_data.csv
            * male_math_data.csv
            * male_reading_data.csv
        * schema.sql creando tablas para una nueva base de datos en postgres 
* carpeta db
    * almacenar el archivo sqlite db para ejecutar la aplicación de matraz (app.py)
* static carpeta 
    * carpeta css
        * El archivo style.css contiene estilos para index.html
    * carpeta js
        * app.js: funciones de Javascript que invocarán datos del archivo app.py para representar imágenes para la página web de metadatos
* carpeta de plantillas
    * chart.html: gráficos de barras de Chart.js que muestran el cambio porcentual en los puntajes de las pruebas para todos los estados por género 
    * math.html: tabla nacional de datos de puntajes matemáticos. Utiliza jquery 
    * read.html - Tabla nacional de datos de puntajes de lectura. Utiliza jquery
    * index.html: tablas de metadatos que muestran los puntajes de los exámenes de niños y niñas para cada materia
* Flask App (app.py)  
    * rutas para llamar a datos y archivos html 


## fuente Datos 

* URL de matemáticas: puntajes de matemáticas de niños y niñas de cuarto grado de 2009 y 2017 
Media nacional 
 https://www.nationsreportcard.gov/Dataservice/GetAdhocData.aspx?type=sigacrossyear&subject=mathematics&grade=4&subscale=MRPCM&variable=GENDER&jurisdiction=NT,AL,AZ,AK,AR,CA,CO,CT,DE,DC,FL,GA,HI,ID,IL,IN,IA,KS,KY,LA,ME,MD,MA,MI,MN,MS,MO,MT,NE,NV,NH,NJ,NM,NY,NC,ND,OH,OK,OR,PA,RI,SC,SD,TN,TX,UT,VT,VA,WA,WV,WI,WY&stattype=MN:MN&Year=2017,2009

* URLS de lectura: puntajes de lectura de niños y niñas de 4to grado de 2009 y 2017 
Promedio nacional  https://www.nationsreportcard.gov/Dataservice/GetAdhocData.aspx?type=sigacrossyear&subject=reading&grade=4&subscale=RRPCM&variable=GENDER&jurisdiction=NT,AL,AZ,AK,AR,CA,CO,CT,DE,DC,FL,GA,HI,ID,IL,IN,IA,KS,KY,LA,ME,MD,MA,MI,MN,MS,MO,MT,NE,NV,NH,NJ,NM,NY,NC,ND,OH,OK,OR,PA,RI,SC,SD,TN,TX,UT,VT,VA,WA,WV,WI,WY&stattype=MN:MN&Year=2017,2009

