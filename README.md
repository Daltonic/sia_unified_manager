# Sia Unified Manager

## Project Overview

Sia Unified Manager (SUM) is a comprehensive tool for managing and accessing data on the Sia Network. It aims to consolidate and expand the capabilities of various Sia projects under one platform, providing users with a seamless experience.

## Features

* Integrated with Sia Renterd
* Modern and responsive UI/UX design
* File viewing and sharing capabilities
* Automatic database backup, export, and import
* Alerts and notifications
* Bulk and cross-platform file transfer
* Access control and domain whitelisting

## Getting Started

1. Clone this repository: 
```
$ git clone https://github.com/DappMentors/sia_unified_manager.git
```

2. Add Environment Variables: Create an environment variable (.env) in the root of this project and supply the following information:

```
RENTERD_SEED=<YOUR_SEED_PHRASE>
RENTERD_API_PASSWORD=<YOUR_LOGIN_PASSWORD>
```
3. Launch Renterd in Docker: 
```
$ docker compose -f "docker-compose.yml" up -d --build
```

4. Visit with browser: Head to http://localhost:9880 and login with your RENTERD_API_PASSWORD.
## Contributing

We welcome contributions to the Sia Unified Manager project. Please submit a pull request with your changes.

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

## Contact

For more information, please contact us at [contact@dappmentors.org](mailto:contact@dappmentors.org).

#### Useful links

- 🏠 [Sia Website](https://sia.tech)
- 🔥 [Sia Renterd](https://sia.tech/software/renterd)
- 👨‍💻 [Sia Renterd API](https://api.sia.tech/renterd)
- 🚀 [Sia Discord Channel](https://sia.tech/discord)
- 💡 [Our Website](https://dappmentors.org/)
- 💪 [YouTube Channel](https://youtube.com/@dappmentors)