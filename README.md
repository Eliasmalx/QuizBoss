# QuizBoss

Juego de preguntas y respuestas donde puedes elegir diferentes temas y dificultad. Podrás subir de experiencia contestando las respuestas correctas y así desbloquear nuevos rankings. 🧠

## Características principales

- Selección de diferentes temas para jugar.
- Niveles de dificultad ajustables.
- Sistema de experiencia: gana puntos al contestar correctamente.
- Rankings desbloqueables según el progreso.
- Interfaz intuitiva y dinámica.

## Tecnologías utilizadas

- **Frontend:** JavaScript, React.js, CSS, HTML
- **Backend:** Python, Flask, SQLAlchemy
- **Otros:** Dockerfile, Mako

## Instalación

### Backend

1. Instala los paquetes de Python:
   ```bash
   pipenv install
   ```
2. Crea tu archivo `.env`:
   ```bash
   cp .env.example .env
   ```
3. Configura tu base de datos y la variable `DATABASE_URL` según el motor que uses (SQLite, MySQL, Postgres).
4. Aplica las migraciones:
   ```bash
   pipenv run migrate
   pipenv run upgrade
   ```
5. Ejecuta la aplicación:
   ```bash
   pipenv run start
   ```

### Frontend

1. Instala los paquetes de Node:
   ```bash
   npm install
   ```
2. Inicia el servidor de desarrollo:
   ```bash
   npm run start
   ```

## Cómo jugar

1. Regístrate o inicia sesión en la plataforma.
2. Elige un tema y nivel de dificultad.
3. Responde las preguntas correctamente para ganar experiencia.
4. Desbloquea rankings y compite con otros usuarios.

## Despliegue

La aplicación está preparada para desplegarse fácilmente en plataformas como Render.com y Heroku. Consulta la [documentación oficial](https://4geeks.com/docs/start/deploy-to-render-com) para más detalles.

## Autores

- Eliasmal
- Erika
- David
- Nelcy

## Licencia

Este proyecto está bajo la Licencia MIT.

---
<img width="1917" height="864" alt="Captura de pantalla 2025-09-01 150417" src="https://github.com/user-attachments/assets/7588d7fd-15cb-49f2-b944-9f4eff75af33" />
<img width="1898" height="862" alt="Captura de pantalla 2025-09-01 150445" src="https://github.com/user-attachments/assets/d1dcc31d-d087-43a0-b95f-4bfd684cf885" />
<img width="1899" height="1075" alt="Captura de pantalla 2025-09-01 150538" src="https://github.com/user-attachments/assets/ce358aa3-5b03-4580-8557-37e90fab15c0" />
<img width="1898" height="1065" alt="Captura de pantalla 2025-09-01 150616" src="https://github.com/user-attachments/assets/a59b7879-f217-4148-9a9e-1f20a1f8e12f" />
<img width="1899" height="853" alt="Captura de pantalla 2025-09-01 150820" src="https://github.com/user-attachments/assets/98889e75-1e55-4226-9e11-25c32ccf428e" />
<img width="1918" height="864" alt="Captura de pantalla 2025-09-01 151310" src="https://github.com/user-attachments/assets/494f805a-b217-46b3-b6be-8bea1007d894" />
<img width="1902" height="867" alt="Captura de pantalla 2025-09-01 151638" src="https://github.com/user-attachments/assets/97bac8ce-a7f0-4dcd-97a1-aa8cc27ae582" />
<img width="1897" height="1051" alt="Captura de pantalla 2025-09-01 151741" src="https://github.com/user-attachments/assets/2fbf5302-3f3b-4ddd-9d8f-3bdadd8c21b8" />

