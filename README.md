<p align="center">
<img src=https://d31uz8lwfmyn8g.cloudfront.net/Assets/logo-henry-white-lg.png

​
# <h1 align="center">**`Proyecto Individual 2 - Datathon ML`**

<p align="center">
<img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQrioxc9PYn0OSD5Ub_3AjMikA5AVgjF-YhBg&usqp=CAU
>
</p>
<hr>

## **Intro**​

¡Bienvenidos a mi segundo proyecto individual! Mi nombre es Juan Valentín Fogliatti y en este repositorio encontrarán la resolución a un problema de clasificación, que intenta determinar si la estadía de un paciente en un hospital será corta (menor o igual a 8 días) o será prolongada (más de 8 días).

Para ello realizaremos un análisis exploratorio sobre los datasets con los que contamos, seguiremos por transformar lo que consideremos necesario, y ya con nuestros datos procesados pasaremos a crear un modelo de Machine Learning que haga las predicciones que permitan clasificar los dos tipos de estadías de los pacientes. 
​<hr>

## **Desarrollo del trabajo**
Para trabajar este proyecto hemos creado este repositorio que está compuesto por:
- Una carpeta Datasets que contiene dos archivos 'csv' que serán nuestros datasets para entrenar y testear el modelo.
- Un archivo de jupyter notebook con todos los procesos realizados sobre los datasets.
- Un archivo 'csv' que cuenta con la predicción sobre el dataset 'hospitalizaciones_test.csv'.
- Un archivo '.pkl' donde hemos almacenado el pipeline del modelo.
- Este Readme.
<hr>

## **Tecnologias utilizadas**
- Python
- Pandas
- Scikit-Learn
- Matplotlib
- Seaborn
<hr>​

## **Descripción de las dimensiones**
A continuación expondremos las dimensiones con la que cuentan los datasets, de forma de poder entender nuestro punto de partida:
- Available Extra Rooms in Hospital: Habitaciones adicionales disponibles en el hospital. Una habitación no es igual a un paciente, pueden ser individuales o compartidas.
- Department: Área de atención a la que ingresa el paciente. 
- Ward_Facility_Code: Código de la habitación del paciente.
- doctor_name: Nombre de el/la doctor/a a cargo del paciente.
- staff_available: Cantidad de personal disponible al momento del ingreso del paciente.
- patientid: Identificador del paciente.
- Age: Edad del paciente.
- gender: Género del paciente.
- Type of Admission: Tipo de ingreso registrado según la situación de ingreso del paciente.
- Severity of Illness: Gravedad de la enfermedad/condición/estado del paciente al momento del ingreso.
- health_conditions: Condiciones de salud del paciente. 
- Visitors with Patient: Cantidad de visitantes registrados para el paciente.
- Insurance: Indica si la persona posee o no seguro de salud. 
- Admission_Deposit: Pago realizado a nombre del paciente, con el fin de cubrir los costos iniciales de internación. 
- Stay (in days): Días registrados de estancia hospitalaria. 
​
## **Palabras Finales​**
Muchas gracias por visitar mi repo. Espero que el trabajo realizado sea de su agrado.

Pueden ver los pasos del proceso en el siguiente archivo: https://github.com/ValenteFog/PI02_Datathon/blob/master/PI02_01_Procesos.ipynb