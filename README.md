# Docker Compose Files

This repository contains Docker Compose files for various services, including Audiobookshelf, FileZilla, JDownloader, Jellyfin, and Postgres with pgAdmin. These configurations simplify the setup and management of these services using Docker.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Available Services](#available-services)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Docker Compose is a tool for defining and running multi-container Docker applications. This repository provides pre-configured Docker Compose files to quickly set up services like media servers, file managers, downloaders, and database management.

## Installation

To get started, ensure you have Docker and Docker Compose installed:

1. Install Docker:

   - [Install Docker](https://docs.docker.com/get-docker/)

2. Install Docker Compose:

   - [Install Docker Compose](https://docs.docker.com/compose/install/)

3. Clone this repository:

   \`\`\`bash
   git clone https://github.com/rogelio-cortes/docker-compose-files.git
   \`\`\`

4. Navigate to the folder with the docker-compose file you'd like to use:

   \`\`\`bash
   cd docker-compose-files/your-environment
   \`\`\`

## Usage

1. Run the following command to start the services:

   \`\`\`bash
   docker-compose up
   \`\`\`

2. To stop and remove containers, networks, and volumes:

   \`\`\`bash
   docker-compose down
   \`\`\`

### Customizing Configuration

You can modify the \`docker-compose.yml\` file to suit your needs, such as changing ports, volumes, or service configurations.

## Available Services

This repository includes Docker Compose files for the following services:

- **Audiobookshelf** - A self-hosted audiobook and podcast server.
- **FileZilla** - A cross-platform FTP solution for both client and server.
- **JDownloader** - A popular download manager for automated downloading from various hosting services.
- **Jellyfin** - A media server for organizing and streaming your personal media collections.
- **Postgres with pgAdmin** - A powerful, open-source object-relational database system paired with a web-based database management tool.

Each folder contains a specific \`README.md\` with additional setup details for that service.

## Contributing

Contributions are welcome! Feel free to fork this repository and submit pull requests with improvements or new service configurations.

## License

This repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.
