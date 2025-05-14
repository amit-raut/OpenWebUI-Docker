# OpenWebUI-Docker

Docker based OpenWebUI

## Requirements

- Docker
  - Install by visiting <https://docs.docker.com/get-docker/>
- Docker Compose
  - Install by visiting <https://docs.docker.com/compose/install/>
- Git
  - Install by visiting <https://git-scm.com/book/en/v2/Getting-Started-Installing-Git>
- Ollama
  - Install by visiting <https://ollama.com/download>

## Setup

Once you have all the requirements installed, you can clone this repository
and run the following commands:

```bash
git clone https://github.com/amit-raut/OpenWebUI-Docker.git
cd OpenWebUI-Docker
docker compose up -d
```

Hope this helps you to get started with OpenWebUI using Docker.
If you have any questions or issues, feel free to open an issue on the GitHub repository.

## Usage

To start using OpenWebUI web interface simply visit <http://localhost:3000>,
sign-up for your local account.

After loggging into OpenWebUI you'll find Chat Interface as shown in screenshot below:
![image](https://github.com/user-attachments/assets/3afc198c-5d2b-43ac-b237-49e811569088)


## Update

To update the OpenWebUI, you can run the following commands while inside
the `OpenWebUI-Docker` directory:

```bash
docker compose pull && docker compose up -d --force-recreate
```

Enjoy using OpenWebUI!

</br>
Amit Raut
