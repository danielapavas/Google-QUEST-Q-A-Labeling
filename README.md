# Google-QUEST-Q-A-Labeling

## Miembros del grupo
* DIANA CAROLINA HUERTA GONZALES, CC 40944999,Ingeniería de Sistemas
* DANIELA ANDREA PAVAS BEDOYA, CC 1192741700, Ingeniería de Sistemas


## Datos
Los datos del proyecto se toman de la competición [Google-QUEST-Q-A-Labeling](https://www.kaggle.com/competitions/google-quest-challenge/data). Los pasos para hacerlos disponibles en google collab son los siguientes:  

1. Estando logueado en la cuenta de Kaggle, irse a Settings y dar click en "Create New Token":  

![image](https://user-images.githubusercontent.com/75345956/233895698-beb81b8b-489c-4bdd-a660-56efc1a1024e.png)

Después de dar click, se descargará un archivo llamado Kaggle.json

2. En el notebook de google Collab ejecutar las siguientes lineas de comando:
```
  !pip install kaggle
  
  from google.colab import files 
  files.upload()
```
Luego dar click en el boton "Elegir archivos" para cargar el archivo .json

![image](https://user-images.githubusercontent.com/55060788/233894298-1c75936e-c9ab-4c9d-8264-da97fa2920e0.png)

3. Por ultimo ejecutar las siguientes lineas de codigo:

```
  ! mkdir ~/.kaggle
  ! cp kaggle.json ~/.kaggle/
  ! chmod 600 ~/.kaggle/kaggle.json
  !kaggle competitions download -c allstate-claims-severity
  !unzip allstate-claims-severity.zip
```


## Videos

- [Video entrega final](https://www.youtube.com/watch?v=MEVIbQ9-ibc)
