# Elegant Sounds Backend

Elegant Sounds Backend is the server-side application for the Elegant Sound Project, providing RESTful APIs and backend logic for managing music, users, and related resources.

## Features

- RESTful API with Express
- MongoDB integration via Mongoose
- Authentication & JWT
- Modular controllers, routes, and models
- Input validation with Zod
- Docker support for easy deployment
- Environment configuration via .env
- Logging with Morgan
- File uploads with Multer

## Prerequisites

- [Node.js](https://nodejs.org/) (v16+ recommended)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)
- [Docker](https://www.docker.com/) (optional, for containerized deployment)
- [MongoDB](https://www.mongodb.com/) instance (local or remote)

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/Epic2077/elegant-backend.git
cd elegant-backend
```

### 2. Install Dependencies

```bash
npm install
# or
yarn install
```

### 3. Configure Environment Variables

Copy `.env.example` to `.env` and update the values as needed:

```bash
cp .env.example .env
```

Set your MongoDB URI and other secrets in `.env`.

### 4. Run the Application (Locally)

```bash
npm run start
# or
yarn start
```

The server will start on the port specified in your `.env` (default: 3000).

### 5. Run with Docker

Use Docker Compose :

```bash
docker-compose up
```

### 6. API Documentation

See `divar.postman_collection.json` for Postman requests.
Endpoints cover authentication, products, orders, profiles, etc.

## Development

- To start in development mode with auto-reload:
  ```bash
  npm run dev
  ```
- To run tests:
  ```bash
  npm test
  ```

## Contributing

Contributions are welcome! Please fork the repository, create a feature branch, and submit a pull request.

1. Fork the repo
2. Create your feature branch (`git checkout -b feature/my-feature`)
3. Commit your changes (`git commit -am 'Add new feature'`)
4. Push to the branch (`git push origin feature/my-feature`)
5. Open a pull request

## License

This project is licensed under the MIT License.

## Contact

For questions or support, open an issue or contact the maintainer.

---

Enjoy building with Elegant Sounds!
