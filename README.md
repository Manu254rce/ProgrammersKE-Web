# ProgrammersKE Web

## Project setup

### Create .env file

create .env file in root directory and add following variables

```bash
VITE_X_RAPID_API_HOST='judge0-ce.p.rapidapi.com'
VITE_X_RAPID_API_URL='https://judge0-ce.p.rapidapi.com/submissions'
VITE_X_RAPID_API_KEY='your-api-key'
```
<!-- NOTE: The above variables are still under development. However, make use of your own API keys, which you can get from [RapidAPI](https://rapidapi.com/). Furthermore, the commands take into consideration the use of Vite in the tech stack, but this may change in the future-->

### Install dependencies

```bash
npm install
```

## Run development server (with Vite)

```bash
npm run dev
```

## Run development server (with Docker)

Ensure you have Docker installed on your machine, then run the following; 

```bash
docker build -t programmerske-web_frontend .

docker run -d -p 5174:5173 programmerske-web_frontend
```
