# 🌋 TerraQuake API

<div align="center">

[![License](https://img.shields.io/badge/License-AGPL%203.0-blue.svg)](https://github.com/nagcas/TerraQuakeApi/blob/main/LICENSE.md)
[![GitHub Stars](https://img.shields.io/github/stars/nagcas/TerraQuakeApi)](https://github.com/nagcas/TerraQuakeApi/stargazers)
[![GitHub Issues](https://img.shields.io/github/issues/nagcas/TerraQuakeApi)](https://github.com/nagcas/TerraQuakeApi/issues)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](./CONTRIBUTING.md)

A modern, open-source seismic data platform providing real-time earthquake information through a RESTful API and interactive visualization interface.

[Getting Started](#getting-started) • [Features](#features) • [API Reference](#api-reference) • [Use Cases](#use-cases) • [Contributing](#contributing)

</div>

## 📑 Overview

TerraQuake is a comprehensive seismic data platform that combines a powerful REST API with an intuitive web interface. It provides researchers, developers, and organizations with easy access to real-time earthquake data, advanced filtering capabilities, and interactive visualizations.

---

## Project Overview

- **Backend (TerraQuake API)** — Node.js + Express REST API to serve earthquake data.
- **Frontend** — React + TailwindCSS interface for visualizing seismic events.
- **Data Source** — INGV (Istituto Nazionale di Geofisica e Vulcanologia) and synthetic demo data.
- **API Access** — Public endpoints for querying earthquakes by time, magnitude, location, and more.

---

## Technologies Used

### Backend

- **Node.js**
- **Express**
- **MongoDB** (planned for persistent data)
- **JWT** (for secure access, future feature)
- **Custom earthquake generator** (for demo/testing)

### Frontend

- **React 19**
- **Vite**
- **Tailwind CSS 4**
- **React Router**
- **Hero sections, maps, charts** (via Leaflet, Chart.js – if added)

---

## API Features

### Available Endpoints

#### `GET /v1/earthquakes`

Returns all recorded earthquakes.

#### `GET /v1/earthquakes/month/:year/:month`

Filter earthquakes by year and month.

#### `GET /v1/earthquakes/range-time?starttime=YYYY-MM-DD&endtime=YYYY-MM-DD`

Filter earthquakes within a time range.

#### `GET /v1/earthquakes/demo`

Returns 100 demo earthquakes (randomized for testing and UI display).

#### `GET /v1/earthquakes/stats`

Returns statistics such as:

- Total earthquakes
- Strongest event
- Average magnitude

---

## Frontend Features

- Visualize earthquakes on an interactive map
- Filter events by date
- View statistics in chart format
- Educational UI: earthquake basics and seismic zones (planned)
- Search and filter functionality

---

## Author

Dr. Gianluca Chiaravalloti
Web Developer & Geologist
[Linkedin]() [Portfolio](https://portfolio-gianluca-phi.vercel.app/)

## 🤝 Contributing

Contributions are welcome!  
If you’d like to improve TerraQuake API, please fork the repository and open a pull request.  
Whether it’s fixing a bug, improving documentation, or adding a feature — all contributions are appreciated!

Please make sure to follow the [contributing guidelines](CONTRIBUTING.md).

## 💬 Community

Join our community on [Discord](https://discord.gg/RDBp8KJB) to connect, share ideas, and collaborate with other contributors.

## 🎉 Hacktoberfest 2025

This project is participating in Hacktoberfest 2025!  
Contributions count toward the event. Feel free to submit PRs and join us in building TerraQuake API together 🌍

## � Credits

### Core Team

- **Dr. Gianluca Chiaravalloti** - Project Lead & Founder
  - Web Developer & Geologist
  - [Portfolio](https://portfolio-gianluca-phi.vercel.app/)

### Key Contributors

- International team of 5 collaborators contributing to:
  - Backend Development
  - Frontend Enhancements
  - Testing & Quality Assurance
  - Documentation
  - Community Support

### Data Sources & Partners

- **INGV** (Istituto Nazionale di Geofisica e Vulcanologia)
  - Primary source of seismic data
  - Technical consultation on seismological aspects

### Technologies & Resources

- **Frontend Technologies**

  - React.js Documentation & Community
  - Tailwind CSS Framework
  - Vite Build Tool
  - OpenStreetMap for geographical data

- **Backend Technologies**
  - Node.js & Express.js Communities
  - MongoDB Documentation & Support
  - JWT Authentication Resources
  - ESLint & StandardJS

### Special Thanks

- Open Source Community
- Early Adopters & Testers
- Bug Reporters & Feature Requesters
- Documentation Contributors

## �💖 Support the Project

TerraQuake API is an open-source initiative aimed at making real-time seismic data accessible for developers, researchers, and communities.

If you find this project useful and would like to support its development, consider becoming a sponsor.
Your contribution helps:

Maintain and improve the API

Add new features and documentation

Keep the project open and accessible to everyone

Even a small donation makes a big difference in keeping the project alive and growing.

[![Sponsor](https://img.shields.io/badge/Sponsor-GitHub-ff69b4?style=flat-square&logo=github)](https://www.paypal.com/paypalme/magcas)

Thank you for supporting open source and helping TerraQuake API reach more people! 🌍
