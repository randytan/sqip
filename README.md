# Sqip

Sqip is a web-based CRM application for middle size company.

## Installation

Sqip will use Docker package manager to run the application. To begin you need to have [Docker](https://docker.com) installed on your machine.
Once you have installed Docker, you could obtain the latest version of Sqip Docker image on the Docker hub.

Run this command to pull 

```bash
docker pull sqip.me/console:latest
```

Run this command to run the Docker container

```bash
docker run -it -p 80:9000 -name sqip-console sqip.me/console:latest
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)