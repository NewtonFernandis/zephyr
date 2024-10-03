<div align="center">

  <a href="https://github.com/parazeeknova/zephyr">
    <img src="./assets/Zephyr-Banner.png" alt="Banner" width="98%"/>
  </a>
</div>

---

<br>

<div align="center">
  <a href="https://github.com//parazeeknova/zephyr#-development-setup-for-contributers"><kbd> <br> Development <br> </kbd></a>&ensp;&ensp;
  <a href="https://github.com/parazeeknova/zephyr/blob/main/CONTRIBUTING.md"><kbd> <br> Contribution <br> </kbd></a>&ensp;&ensp;
  <a href="https://github.com/parazeeknova/zephyr/wiki"><kbd> <br> Wiki <br> </kbd></a>&ensp;&ensp;
</div>

#### _<div align="left"><sub>// Project Overview</sub></div>_

<p align="left">
<strong>Zephyr</strong> is a Social aggregator, part social media platform, part news aggregator. It is a platform that allows users to share and discover content from around the web. Completly open-source and community-driven, Zephyr is a platform that is built by the community, for the community.
</p>

#### _<div align="left"><sub>// Development Setup (For Contributers)</sub></div>_

###### _<div align="right"><sub>// Prerequisites</sub></div>_

- [Node.js](https://nodejs.org/en/download/) (v20 or higher)
- [pnpm](https://pnpm.io/installation)
- [Turborepo](https://turbo.build/repo/docs/)

###### _<div align="right"><sub>// Installation</sub></div>_

<p align="left">
We use **pnpm** and **turbo** for managing the dependencies and the monorepo structutre. To install the dependencies and start the development server, run the following commands:
</p>

> [!IMPORTANT]
> Make sure you have the prerequisites installed before running the following commands and have `.env` file in the root directory.

```bash
# Clone the repository
git clone https://github.com/zephyr.git && cd zephyr
# Install the dependencies
pnpm install
# Start the development server on http://localhost:3000 (default web) and http://localhost:3001 (default wiki)
turbo dev
```

###### _<div align="right"><sub>// Docker:</sub></div>_

```bash
# Build the docker image for production and start the server
docker-compose -f docker-compose.yml up -d or docker-compose build and docker-compose up
```

#### _<div align="left"><sub>// License</sub></div>_

<p align="left">
<strong>Zephyr</strong> is licensed under the <a href="https://github.com/parazeeknova/zephyr/blob/main/LICENSE">AGPL License</a>.
</p>

<div align="right">
  <a href="#-project-overview"><kbd> <br> 🡅 <br> </kbd></a>
</div>

---
