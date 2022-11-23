# Docker-Next.js

## Introduction
This project is a template for Next.js development environment using TypeScript built with Docker Compose.

You can generate a new repository with the same directory structure and files as [mizu0715/docker-next.js](https://github.com/mizu0715/docker-next.js).
 
- [Docker Compose](https://docs.docker.com/get-started/08_using_compose/)
- [Next.js](https://nextjs.org/)

## Dependencies
```json
  "dependencies": {
    "@types/node": "18.11.9",
    "@types/react": "18.0.25",
    "@types/react-dom": "18.0.9",
    "eslint": "8.28.0",
    "eslint-config-next": "13.0.4",
    "next": "13.0.4",
    "react": "18.2.0",
    "react-dom": "18.2.0",
    "typescript": "4.9.3"
  }
```
## Usage
### Create a new repository
- Click [[Use this template]](https://github.com/mizu0715/docker-next.js/generate)

The new repository will start with the same files and folders as this repository.

### Git clone
```bash
git clone https://github.com/[your repository]
```

### Docker Setup
```bash
docker-compose up -d
```

### Next.js Setup
```bash
docker-compose exec app yarn

# or

docker-compose exec app bash
yarn
```


### Start Next.js in development mode
```bash
docker-compose exec app yarn dev

# or

docker-compose exec app bash
yarn dev
```

http://localhost:3000/
