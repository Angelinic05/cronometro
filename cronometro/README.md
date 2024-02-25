---

# Cronómetro

Este es un cronómetro simple creado utilizando HTML, CSS y JavaScript. Permite iniciar, pausar y reiniciar el tiempo.

## Funcionamiento

El cronómetro muestra el tiempo transcurrido en horas, minutos y segundos en formato HH:MM:SS. Se puede iniciar el cronómetro haciendo clic en el botón de "Iniciar", que cambiará su icono a un botón de "Pausar". Al hacer clic en "Pausar", el cronómetro se detendrá y podrás reiniciarlo haciendo clic en el botón "Reiniciar".

## Estructura del Proyecto

El proyecto está estructurado de la siguiente manera:

```
cronometro/
│
├── css/
│   └── style.css
│
├── js/
│   └── app.js
│
├── index.html
│
└── README.md
```

- **css/**: Contiene el archivo CSS que define el estilo del cronómetro.
- **js/**: Contiene el archivo JavaScript que controla la lógica del cronómetro.
- **index.html**: Es el archivo HTML principal que muestra la interfaz del cronómetro.
- **README.md**: Este archivo que proporciona información sobre el proyecto.

## Clases del CSS

El archivo `style.css` define las siguientes clases para estilizar el cronómetro:

- **.contenedor-principal**: Estiliza el contenedor principal del cronómetro.
- **.contenedor-botones**: Estiliza el contenedor de los botones de control del cronómetro.
- **#cronometro**: Estiliza el elemento del cronómetro que muestra el tiempo.
- **.boton**: Estiliza los botones de inicio/pausa y reinicio del cronómetro.

Para más detalles sobre las propiedades CSS aplicadas a estas clases, consulta el archivo `style.css`.

## app.js

El archivo `app.js` contiene la lógica del cronómetro. Controla el inicio, pausa y reinicio del tiempo, así como el cálculo y visualización del tiempo transcurrido.

- **actualizarCronometro()**: Función que actualiza el tiempo del cronómetro en intervalos de 1 segundo.
- **asignarFormato(unidadDeTiempo)**: Función que formatea la unidad de tiempo (horas, minutos, segundos) con un cero inicial si es menor que 10.
- **toggleCronometro()**: Función que alterna entre iniciar y pausar el cronómetro.
- **reiniciarCronometro()**: Función que reinicia el cronómetro a 00:00:00.



