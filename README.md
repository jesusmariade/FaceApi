Programa de reconocimiento facial creado en Angular, con ayuda de la api de reconocimiento facial FACEAPI, Angular Material, firestore, storage, firestore database
Prerrequisitos
Node.js 14.x o superior

Angular CLI 13.x

Cuenta de Firebase

# 1. Clonar repositorio
git clone https://github.com/jesusmariade/FaceApi.git
cd FaceApi

# 2. Instalar dependencias
npm install

# 3. Descargar modelos de ML
npm run download-models

# 4. Configurar environment (ver sección siguiente)
cp src/environments/environment.example.ts src/environments/environment.ts

# 5. Ejecutar servidor de desarrollo
ng serve

# 6. Abrir en navegador
# http://localhost:4200

Contribuir
¡Contribuciones son bienvenidas! Sigue estos pasos:

Fork el proyecto

Crear rama de feature: git checkout -b feature/AmazingFeature

Commit cambios: git commit -m 'feat: Add AmazingFeature'

Push a la rama: git push origin feature/AmazingFeature

Abrir Pull Request
