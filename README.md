# WorldWise

A web application that helps you track your travels around the world. Click on any city on an interactive map, add notes about your adventures, and never forget your wonderful experiences.

![WorldWise App](https://img.shields.io/badge/React-18.2.0-blue) ![Vite](https://img.shields.io/badge/Vite-4.4.5-purple) ![Leaflet](https://img.shields.io/badge/Leaflet-1.9.4-green)

![WORLD WISE Banner](./Banar_World_Wise.png)

## Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Authentication](#authentication)
- [Current Limitations](#current-limitations)
- [Future Enhancements](#future-enhancements)
- [License](#license)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Features

- **Interactive World Map**: Built with React-Leaflet for smooth map interactions
- **City Tracking**: Click anywhere on the map to add cities you've visited
- **Trip Notes**: Add personal notes and dates for each city
- **Country Overview**: View all countries you've visited at a glance
- **Geolocation Support**: Use your current location to quickly add nearby cities
- **Fake Authentication**: Protected routes with login system (for demo purposes)
- **Responsive Design**: Works seamlessly across different screen sizes

## Tech Stack

### Frontend
- **React 18.2** - UI library
- **React Router DOM 6.30** - Client-side routing
- **Leaflet & React-Leaflet** - Interactive maps
- **React DatePicker** - Date selection
- **CSS Modules** - Scoped styling

### Backend
- **Express 5.2** - Server framework
- **CORS** - Cross-origin resource sharing
- **In-memory storage** - Cities data stored in array

### Build Tools
- **Vite 4.4** - Fast build tool and dev server
- **ESLint** - Code linting

## Authentication

The app uses fake authentication for demonstration purposes:

- **Email**: `jack@example.com`
- **Password**: `qwerty`

## Current Limitations

1. Data is stored in-memory on the server (resets on restart)
2. No real user authentication
3. No persistent database
4. Limited to demo data

## Future Enhancements

- [ ] Add real database (MongoDB/PostgreSQL)
- [ ] Implement actual user authentication with JWT
- [ ] Add user profiles
- [ ] Enable sharing trips with friends
- [ ] Add photo upload functionality
- [ ] Implement search and filter features
- [ ] Add statistics dashboard

## License

This project is open source and available under the MIT License.

## Author

**[Moamen Ashraf]**

- GitHub: [MomenAshraf5](https://github.com/MomenAshraf5)
- Email: moamenashraf533@gmail.com
- LinkedIn: [MoamenAshraf](https://linkedin.com/in/momen-ashraf)

## Acknowledgments

- Map tiles by [OpenStreetMap](https://www.openstreetmap.org/)
- Reverse geocoding by [BigDataCloud](https://www.bigdatacloud.com/)
- Icons by Leaflet

---

**Note**: This is a learning project built to practice React concepts including routing, context API, custom hooks, and external API integration.
