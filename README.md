<div align="center">
  <h3 align="center">N5 Now | Carlos Echeverría</h3>

  <p align="center">
    Microfrontend - Prueba tecnica
    <br />
    <a href="https://main-puce.vercel.app/">App Host</a>
    ·
    <a href="https://harry-potter-gules-ten.vercel.app/">Harry Potter</a>
    ·
    <a href="https://rick-and-morty-rho-ten.vercel.app/">Rick y Morty</a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary name="readme-top">Tabla de contenido</summary>
  <ol>
    <li>
      <a href="#sobre-el-proyecto">Hablemos del proyecto</a>
    </li>
    <li>
      <a href="#para-empezar">Para empezar</a>
      <ul>
        <li><a href="#uso-en-local">Para correr el proyecto</a></li>
        <li><a href="#unit-test">Pruebas unitarias</a></li>
      </ul>
    </li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## Sobre el proyecto

Este proyecto es pensado con una arquitectura de microfrontends, es decir cada modulo pertenece a una app diferente. Esto permite velocidad en el crecimiento del proyecto y mejorar la gestión y creación de los módulos ya que puede asignar una célula a la administracion de cada uno de ellos.

Con esto tambien cabe resaltar que por ser cada micro frontend una aplicación independiente pueden ver cada una de ellas por separado (ver en los links de la cabecera de este documento).

![Orquestado](<Captura de pantalla 2023-12-25 a la(s) 18.34.27.png>)
<p align="right">(<a href="#readme-top">Ir </a>)</p>



### Construido con

Por ser una prueba de frontend, se crean usando las siguientes herramientas:

* [![Next][Next.js]][Next-url]
* [![React][React.js]][React-url]
* [![Tailw][Tailwind.com]][Tailwind-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Para empezar
Debes tener en tu local las herramientas descritas anteriormente instaladas, además de git, visual studio code y un navegador.

Para iniciar debes clonar el proyecto en tu local:

   ```sh
   git clone https://github.com/echeverriadev/n5-now-project.git
   ```

Este es el reposotorio que contiene los micro frontends, a su vez, estos tienen un repositorio individual para separar cada uno en submodulos de git(cada proyecto). Para poder tenerlos en tu local debes inicializar estos submodulos:

  ```sh
  git submodule initi
  git submodule update
  ```

Esto hará que se descargue cada proyecto de forma individual y los tengamos tambien separados por repositorio.


### Uso en local
Luego de clonados:
Debes ingresar al proyecto host(main)

  ```sh
  cd main
  npm install
  npm run dev
  ```

De igual forma con cada uno de los submodulos

  ```sh
  cd ../harry-potter
  npm install
  npm run dev
  ```

  ```sh
  cd ../rick-and-morty
  npm install
  npm run dev
  ```

__Nota: Revisar las variables de entorno en cada proyecto__
<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Unit test
Cada proyecto tiene sus propias pruebas unitarias el archivo '\_\_test\_\_'
Estan separadas segun su proposito dentro de la aplicación:
  - \_\_test\_\_
    - Components
    - Hooks
    - Pages
    - Services
    - Utils

UNIT TEST main
![Main Test](<Captura de pantalla 2023-12-25 a la(s) 18.46.20.png>)

UNIT TEST harry-potter
![Harry Potter Test](<Captura de pantalla 2023-12-25 a la(s) 18.03.44.png>)


UNIT TEST Rick-and-morty
![Rick and Morty Test](<Captura de pantalla 2023-12-25 a la(s) 18.24.34.png>)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ROADMAP -->
## Roadmap

- [x] Crear proyecto base (orquestador)
- [x] Agregar submodulos de los mini proyectos
- [x] Crear entornos dev en Vercel
- [x] Agregar README file
- [x] Multi-language
    - [x] Español
    - [x] Ingles
- [x] Crear listado de personajes
    - [x] Harry Potter
    - [x] Rick and Morty
- [x] SEO Friendly
- [ ] Ajustar estilos


See the [open issues](https://github.com/othneildrew/Best-README-Template/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Carlos Echeverria - [Linkedin](https://linkedin.com/in/echeverriadev) - email@example.com

Project Link: [main](https://github.com/echeverriadev/n5-now-project)
Listado Harry Potter: [harry-potter](https://github.com/echeverriadev/harry-potter)
Listado Rick and Morty: [rick-and-morty](https://github.com/echeverriadev/rick-and-morty)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=for-the-badge
[contributors-url]: https://github.com/othneildrew/Best-README-Template/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=for-the-badge
[forks-url]: https://github.com/othneildrew/Best-README-Template/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/othneildrew/Best-README-Template/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/othneildrew/Best-README-Template/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/othneildrew
[product-screenshot]: images/screenshot.png
[Next.js]: https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white
[Next-url]: https://nextjs.org/
[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
[Tailwind.com]: https://img.shields.io/badge/tailwindcss-0F172A?&logo=tailwindcss
[Tailwind-url]: https://tailwindcss.com/