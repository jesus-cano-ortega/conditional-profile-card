# <img src="https://github.com/jesus-cano-ortega/js-introduction-exercises/blob/main/assets/resources/img/face.png" width="45" alt="Personal Logo"> Conditional Profile Card





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