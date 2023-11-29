# **Proyecto Don Gato y Asociados React** 

- Clonar el repositorio de GitHub:
  ```bash
  git clone https://github.com/closorio/Don-gato-y-asociados.git
  ```

- cd dentro del directorio de la carpeta:
  ```bash
  cd Don-gato-y-asociados
  ```

- Para iniciar el entorno de desarrollo con Docker:
  ```bash
  docker-compose up
  ```
  
  - Para iniciar el entorno de desarrollo con Kubernetes
  ```bash
  kubectl apply -f kubernetes/
  ```


-------------------------------------------------------------------------

- Para correr pruebas unitarias con Jest:
	dongato-frontend/
  ```bash
  npm run test:unit
  ```
- Para correr la prueba Sonar:
	dongato-backend/
  ```bash
  npm run sonar
  ```
- Para correr pruebas ui con Selenium:
	dongato-frontend/
  ```bash
  node runUITest.js
  ```

- Para correr pruebas ui con Selenium-side-runner:
	dongato-frontend/
  ```bash
  node runBBTest.js
  ```

