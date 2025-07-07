# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh



## DEPLOY LINK: https://driven-docker-frontend.vercel.app/


# Subindo a aplicação com docker compose => docker compose up --build

# Fechando a aplicação com docker compose => docker compose down



# Subindo a aplicação com docker apenas 

# criar network =>  docker network create dockerNetwork (se criou no back primeiro não precisa)

# Construir a imagem => docker build -t myfrontend .

# Rodar o container => docker run -d --name frontend --network dockerNetwork -p 8080:80 myfrontend

# OBS PARA CONECTAR O BACKEND DO DEPLOY USAR ESSE ENV => VITE_BACKEND_DEPLOY=https://driven-docker-backend.onrender.com
# OBS PARA CONECTAR O BACKEND DO DOCKER  USAR ESSE ENV => VITE_BACKEND=http://localhost:5000

# Parar a aplicação => docker stop frontend

