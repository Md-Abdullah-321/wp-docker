# WordPress Docker Compose Setup

This repository contains a Docker Compose configuration for setting up a local development environment for WordPress using Docker.

## Prerequisites

Before you begin, ensure you have the following installed on your local machine:

- Docker Engine
- Docker Compose

## Getting Started

To set up WordPress locally, follow these steps:

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/your-username/wordpress-docker-compose.git
cd wordpress-docker-compose
docker-compose up -d
Access WordPress at http://localhost:8000 and phpMyAdmin at http://localhost:8080.


## Configuration

**WordPress:** Access WordPress at [http://localhost:8000](http://localhost:8000).

Default credentials:
- Username: admin
- Password: password

**phpMyAdmin:** Access phpMyAdmin at [http://localhost:8080](http://localhost:8080).

Use the following credentials to log in:
- Username: root
- Password: password

## Customization

You can customize the Docker Compose configuration to fit your specific needs. Here are some common customizations:

- Adjust ports: You can modify the ports mapped to WordPress and phpMyAdmin in the `docker-compose.yml` file.
- Configure environment variables: Customize database credentials and other settings in the `docker-compose.yml` file.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
