# Franken-L11 Docker Configuration

This project provides a Docker Compose configuration for deploying a Laravel application using Franken Docker.

## Prerequisites

- Docker
- Docker Compose

## Getting Started

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/franken-l11.git
    cd franken-l11
    ```

2. Copy the example environment file and update the environment variables as needed:
    ```sh
    cp .env.example .env
    ```

3. Build and start the containers:
    ```sh
    docker-compose up --build --force-recreate --no-deps [-d]
    ```

4. Access the Laravel application:
    - Open your browser and navigate to `http://localhost` with port that you define on environment

## Useful Commands

- **Start the containers**:
    ```sh
    docker-compose up
    ```

- **Stop the containers**:
    ```sh
    docker-compose down
    ```

- **Rebuild the containers**:
    ```sh
    docker-compose up --build
    ```

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## Acknowledgements

- [Laravel](https://laravel.com/)
- [Docker](https://www.docker.com/)
- [Franken Docker](https://github.com/franken-docker)
