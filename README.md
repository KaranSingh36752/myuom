<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->

<a name="readme-top"></a>

<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->

<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->

[![Forks][forks-shield]](https://github.com/Open-Source-UoM/MyUoM/fork)
[![Stargazers][stars-shield]](https://github.com/Open-Source-UoM/MyUoM/stargazers)
[![Issues][issues-shield]](https://github.com/Open-Source-UoM/MyUoM/issues)
[![MIT License][license-shield]](https://github.com/Open-Source-UoM/MyUoM/blob/main/LICENSE)
[![LinkedIn][linkedin-shield]](https://www.linkedin.com/company/80766091)

<!-- PROJECT LOGO -->
<br />
<div align="center">
    <img src="src/assets/myUOMLogo.png" alt="Logo" width="80" height="80">
  <h3 align="center">myUoM</h3>

  <p align="center">
    The official University of Macedonia Student application
    <br />
    <a href="https://github.com/Open-Source-UoM/MyUoM"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://my.uom.gr/">View the Project</a>
    ·
    <a href="https://github.com/Open-Source-UoM/MyUoM/issues/new">Report Bug</a>
    ·
    <a href="github.com/Open-Source-UoM/MyUoM/issues/82">Request Feature</a>
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#features">Features</a></li>
    <li><a href="#project-structure">Project Structure</a></li>
    <li><a href="#development">Development</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->

## About The Project

The myUoM app is a project of the Open Software Team of Applied Informatics, University of Macedonia (https://opensource.uom.gr).
It was designed to facilitate students' daily interactions with the university.

This project serves as a centralized platform for students and faculty, providing:
- A modern and intuitive user interface for accessing university services
- Real-time updates from official university sources
- A scalable backend architecture
- Integration capabilities for other universities
- Content Management System (CMS) for managing dynamic content

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Built With

- [![React][react.js]][react-url]
- [![Chakra UI][chakra.js]][chakra-url]
- [![Docker][docker.js]][docker-url]
- [![Node.js][node.js]][node-url]

## Getting Started

### Prerequisites

- Node.js (>=14.21.3)
- npm
- Docker (optional, for containerization)

### Installation

1. Clone the repository
   ```sh
   git clone https://github.com/Open-Source-UoM/MyUoM.git
   ```
2. Install NPM packages
   ```sh
   npm install
   ```
3. Start the development server
   ```sh
   npm start
   ```

For Docker deployment:
```sh
docker-compose up -d
```

## Features

- **Authentication System**: Secure login and user management
- **Real-time Updates**: Integration with university news and announcements
- **Responsive Design**: Works seamlessly on desktop and mobile devices
- **Multi-language Support**: Internationalization ready
- **CMS Integration**: Easy content management for administrators
- **Scalable Architecture**: Ready for multiple university deployments

## Project Structure

```
myUoM/
├── src/               # Source files
├── public/           # Static files
├── docs/            # Documentation
├── nginx/           # Nginx configuration
├── docker-compose.yml # Docker compose configuration
├── Dockerfile       # Docker configuration
└── package.json     # Project dependencies and scripts
```

## Development

### Available Scripts

- `npm start` - Runs the app in development mode
- `npm test` - Launches the test runner
- `npm run build` - Builds the app for production
- `npm run format` - Formats code using Prettier

### Coding Standards

- We use Prettier for code formatting
- Follow the React best practices and conventions
- Write meaningful commit messages
- Document new features and changes

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTRIBUTING -->

## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LICENSE -->

## License

Distributed under the MIT License. See [`LICENSE`](https://github.com/Open-Source-UoM/MyUoM/blob/main/LICENSE) for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTACT -->

## Contact

Open Source UoM - [@opensource_uom](https://twitter.com/opensource_uom) - linux-team@uom.edu.gr - https://opensource.uom.gr/

Project Link: [https://github.com/Open-Source-UoM/MyUoM](https://github.com/Open-Source-UoM/MyUoM)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Thanks to all the Contributors ❤️

<img src="https://contrib.rocks/image?repo=Open-Source-UoM/MyUoM" />

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/gitlab/contributors/opensourceuom/myUoM?style=for-the-badge
[forks-shield]: https://img.shields.io/gitlab/forks/opensourceuom/myUoM?style=for-the-badge
[stars-shield]: https://img.shields.io/gitlab/stars/opensourceuom/myUoM?style=for-the-badge
[issues-shield]: https://img.shields.io/gitlab/issues/open/opensourceuom/myUoM?style=for-the-badge
[license-shield]: https://img.shields.io/gitlab/license/opensourceuom/myUoM?style=for-the-badge
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[react.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[react-url]: https://reactjs.org/
[chakra.js]: https://img.shields.io/badge/Chakra_UI-319795?style=for-the-badge&logo=chakra-ui&logoColor=white
[chakra-url]: https://chakra-ui.com/
[docker.js]: https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white
[docker-url]: https://www.docker.com/
[node.js]: https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white
[node-url]: https://nodejs.org/
