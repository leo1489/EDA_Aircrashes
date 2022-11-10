<h1 align="center"> Accidentes_aereos-Proyecto_individual:Rocket </h1>


# **Tabla de Contenido:**
- [Accidentes Aereos Contexto <a name="datathon"></a>](#el-datathon-)
- [Sobre el repositorio <a name="about_repo"></a>](#sobre-el-repositorio-)
- [Notebook <a name="notebook"></a>](#notebook-)
- [Dashboard <a name="notebook"></a>](#Dashboard-)
- [License](#license)


<p align="center">
<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQBxIraBAcOR48vF2tBSH3TG4CcsPXaCkhcUQ&usqp=CAU"  height=300>
</p>


# EDA_accidentes_aereos <a name="datathon"></a>

La Organización de Aviación Civil Internacional (OACI), organismo de la Organización de las Naciones Unidas, quiere investigar en profundidad los accidentes producidos desde inicios del siglo XX. Para ello, les solicita la elaboración de un informe y un dashboard interactivo que recopile tal información.

La OACI únicamente cuenta con un dataset sobre datos de accidentes de aviones, pero insta a la consultora de datos -de la que forman parte- que intente cruzar esta información con otras fuentes de su interés. Esto con el objetivo de obtener mayor claridad y consistencia en los fundamentos del estudio..​


# Sobre el repositorio <a name="about_repo"></a>

En el repositorio se encuentra el notebook `EDA_Aircrashes.ipynb`, donde se realizó el analisis exploratorio de datos EDA, se realizo un diccionario del dataset, un reporte de calidad del dato y se encuentran las relaciones y graficas deacuerdo a  la busqueda de patrones.

Se encuentran los *datasets* (Accidentes_Aviones, causes. planecrashinfo_20181121, causes_aircrashes). Deben encontrarse en la misma carpeta del archivo noteboook.ipynb

Se encuentra el dashboard en power BI donde se nos permite ver de manera clara los patrones relaciones y las conclusiones

Tambien se encuentra el archivo README explicando el contenido y desarrollo del proyecto


# Notebook <a name="notebook"></a>

El notebook esta organizado de la siguiente manera:

- **Procedimiento**: 
Se extrajo la información provista en el dataset la cual contiene datos de 5003 accidentes aéreos trágicos, donde se constata información de pasajeros, muertes, operador, tipode aeronave, localizacion, summary, fecha y una descripción en texto libre de algunas características del evento.; adcionalmente se agrego informacion de datasets para profundizar en el analisis y busqueda de patrones relacionados a los accidentes

Con el objetivo de ahondar en el análisis y poder encontrar mas patrones de relacion en un dashboard se hizo investigacion de artículos de academicos y periodísticos para analizar el problema y la temática. 

- **El EDA**: En esta parte encontramos la limpieza, calculos y visualización de variables. Las transformaciones principales que contribuyeron a encontrar las relaciones entre las variables y accidentes.

- **Ingesta Base de datos**:
Se carga los datos a la BD base de datos a traves del conector pymysql y sqlalchemy a mysql workbench para desde ahi ingestar a powerBi

Stack tecnológico:

+ `Python`: EDA + transformaciones 
+ `SQL`: base de datos
+ `Power BI` -preferentemente- o `Streamlit`: dashboard
+ `GitHub`: con un README.md donde se elabore el informe

# Dashboard <a name="Dashboard"></a>

6) Visualización y análisis en Power BI
Se puede visualizar en el archivo dashboard.pbix. El mismo consta de paginas donde se analisa-visualiza de cerca la temática.

El objetivo del dashboard es evaluar la influencia causas externas y factores humanos en los accidentes aéreos y su relacion con operadores comerciales y tipos de aeronaves; evaluar aspectos respecto accidentalidad en funcion del tiempo


# Licencia <a name="license"></a>

El uso de este trabajo está licenciado bajo [GNU General Public License v3.0 (GNU GPLv3)](https://choosealicense.com/licenses/gpl-3.0/).


Stack tecnológico:

+ `Python`: EDA + transformaciones 
+ `SQL`: base de datos
+ `Power BI` -preferentemente- o `Streamlit`: dashboard
+ `GitHub`: con un README.md donde se elabore el informe


- - -







