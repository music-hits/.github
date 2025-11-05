## Music Hits Application

This project is a full-stack application for managing music hits, built as a technical assessment to demonstrate backend and frontend development skills. It provides a RESTful API with a modern frontend interface to explore, search, and display music data from a CSV import.

The service persists data in a relational database and allows tracking of user requests.

## Features

The application allows users to:

- View Top 10 Artists – see the most popular artists in the dataset.
- View Top 10 Tracks – see the most popular tracks in the dataset.
- List All Artists – browse all available artists.
- Search for Artists – search by artist name with partial matches.
- View Artist Details – click on an artist to see their detailed information.

All requests include a simple user tracking header `Authorization: user=123`. This can be easily upgraded to a more secure authentication method like JWT or OAuth2.

## Technology stack

| Layer         | Technologies & Tools                                     |
| ------------- | -------------------------------------------------------- |
| Backend       | Node.js, NestJS, TypeORM, PostgreSQL, Docker, TypeScript |
| Frontend      | Angular, Tailwind CSS, Nx, Docker                        |
| Testing       | Jest (backend), Playwright (frontend)                    |
| Development   | VS Code, Nx monorepo structure, ESLint + Prettier        |
| Documentation | OpenAPI for REST API                                     |

## Project Structure

This repository contains two standalone apps (API and Frontend). Frontend was built with Nx for scalability and maintainability while API was was built using NestJS and TypeORM for database access.

- Frontend - [https://github.com/music-hits/music-hits-frontend/](https://github.com/music-hits/music-hits-frontend/)
- API - [https://github.com/music-hits/music-hits-api/](https://github.com/music-hits/music-hits-api/)

### Detailed Documentation

For step-by-step instructions, setup, testing, and deep dives into the project structure, check the respective READMEs:

- API [README.md](https://github.com/music-hits/music-hits-api/blob/main/README.md) - backend architecture, environment setup, migrations, and testing
- FRONTEND [README.md](https://github.com/music-hits/music-hits-frontend/blob/main/README.md) - frontend architecture, project sketches, environment setup, and e2e testing

## Author

- [Goran Tubic](https://github.com/orangeGoran) - passionate about buidling web applications!

## License

This project is licensed under the MIT License – free to use, modify, and share.
