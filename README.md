# <img src="https://github.com/jesus-cano-ortega/js-introduction-exercises/blob/main/assets/resources/img/face.png" width="45" alt="Personal Logo"> Conditional Profile Card

El objetivo de este proyecto es trabajar con operadores ternarios. Estos operadores, también conocidos como operadores condicionales, son sintaxis utilizadas como atajos para la instrucciones if y que cuentan con tres operandos: 

    ```
    condición ? expresión1 : expresión 2

    ```

Un ejemplo simple sería el siguiente: 

    ```
    
    (Instrucción IF-ELSE)
    
    if(crtl){
      console.log(expresión1);
    }else {
      console.log(expresión2);
    }

    (Operador Ternario)

    crtl ? expresión1 : expresión2;

    ```

La condición inicial del operador ternario se evalúa como true o false y se opta por una de las dos expresiones. Este tipo de simplificaciones tan solo debe ser utilizado para ejecutar sentencias sencillas buscando siempre así, mejorar la legibilidad del código. 

En este ejercicio, se debe crear el código HTML necesario para representar una tarjeta de perfil, donde el código final cambie de ejecución en función de una serie de variables que vaya escogiendo o variando el usuario.

![Conditional Profile Card](https://github.com/breatheco-de/exercise-conditional-profile-card/raw/master/preview.gif?raw=true)

1. Dentro `src/app.js` hay una function llamada `render` que recibe un objeto `variables`.
2. Este objeto `variables` contiene todos los valores asignados en el formulario de la aplicación (redes sociales, nombre apellido, etc.).
3. La función render tiene la lógica necesaria para recibir los valores del objeto `variables` e incluirlos dentro del HTML de la pagina utilizando `innerHTML`.


## 🌱  Cómo iniciar este proyecto

1. Este proyescto viene con los archivos necesarios para empezar a trabajar, pero tienes dos opciones para empezar:

    a) Abrir este link con Gitpod en tu navegador: https://gitpod.io#https://github.com/breatheco-de/exercise-conditional-profile-card.git

    b) Clonar este repositorio localmente en tu computador:

    ```sh
    $ git clone https://github.com/breatheco-de/exercise-conditional-profile-card.git
    ```
2. Entra en la carpeta del proyecto:  `cd exercise-conditional-profile-card`

3. Instala los paquetes NPM (asegúrate de usar la última versión de node): `npm install`

4. Corre el proyecto utilizando:  `npm run start`

5. Actualiza la función `render` dentro del archivo app.js.

💡 Importante: Recuerda actualizar el `remote` del proyecto con el de tu repositorio usando `git remote set-url origin <your new url>`, y luego guardar tu código en tu nuevo repositorio usando `add`, `commit` y `push`.


## 📝Instrucciones:

Revisa este video con las instrucciones para que entiendas mejor el ejercicio: https://youtu.be/gaVm8eyCqlM

1. Lee y comprende la función render y el valor de la variable `variables` que recibe.

2. Cambia el cotenido de la función render para que renderice todos los valores que llegan a través de `variables`en la tarjeta de perfil.

```js
console.log(window.variables);
/*
{
    includeCover: true, // if includeCover is true the algorithm should
    background: "https://images.unsplash.com/photo-1511974035430-5de47d3b95da", // this is the url of the image that will used as background for the profile cover
    avatarURL: "https://randomuser.me/api/portraits/women/42.jpg", // this is the url for the profile avatar
    socialMediaPosition: "left", // social media bar position (left or right)
    
    twitter: null, // social media usernames
    github: "alesanchezr",
    linkedin: null,
    instagram: null,

    name: null,
    lastname: null,
    role: null,
    country: null,
    city: null
}
*/
````