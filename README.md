# Pirates

A mobile studio discovery and reservation app designed for musicians to explore rehearsal spaces, view promotions, save favourite studios, and manage upcoming bookings.

## Overview

Pirates is a React Native mobile application inspired by modern rehearsal studio platforms.

The app provides a central place for musicians to:

* Browse available rehearsal studios
* View studio information and facilities
* Save favourite locations
* Select reservation dates and times
* Manage upcoming studio bookings
* Receive local notifications for appointments
* Explore current studio promotions
* Contact the studio directly through the app

The project focuses on creating a clear and convenient mobile booking experience for musicians, podcasters, dancers, and other creative users.

## Interface Preview

<p align="center">
  <img src="./assets/images/Interface.png" width="90%" alt="Pirates mobile app interface preview" />
</p>

## Built With

* React Native
* Expo
* JavaScript
* Redux Toolkit
* Redux Persist
* React Navigation
* React Native Elements
* Expo Notifications
* Expo Secure Store
* AsyncStorage

## Core Features

### Studio Discovery

Users can browse a directory of rehearsal studios and open individual studio pages to view additional information.

### Reservations

The reservation flow allows users to select a studio, choose a date and time, and manage upcoming appointments.

### Favourites

Studios can be saved to a dedicated favourites section for quick access later.

### Promotions

The home experience presents current promotions and featured studio content.

### Notifications

Local notifications remind users about upcoming studio reservations.

### Contact

A dedicated contact screen allows users to reach the studio directly from the application.

## Project Structure

```text
pirates/
├── assets/
│   └── images/
├── components/
├── features/
│   ├── comments/
│   ├── favourites/
│   ├── promotions/
│   └── studios/
├── redux/
├── screens/
│   ├── ContactScreen.js
│   ├── DirectoryScreen.js
│   ├── FavouritesScreen.js
│   ├── HomeScreen.js
│   ├── LoginScreen.js
│   ├── ReservationScreen.js
│   └── StudioInfoScreen.js
├── shared/
├── App.js
├── app.json
└── package.json
```

## Getting Started

### Prerequisites

Make sure the following tools are installed:

* Node.js
* npm
* Expo Go, an iOS simulator, or an Android emulator

### Installation

Clone the repository:

```bash
git clone https://github.com/hreisis/pirates.git
cd pirates
```

Install the dependencies:

```bash
npm install
```

Start the Expo development server:

```bash
npm start
```

## Inspiration

The project was inspired by [Pirate Studios](https://pirate.com/), a platform providing creative studio spaces for musicians, podcasters, producers, and dancers.

## Project Status

This project was developed as a mobile application and portfolio project. It is no longer actively maintained, and some dependencies use earlier versions of React Native and Expo.

## Author

**Charlene Chen**

* GitHub: [@hreisis](https://github.com/hreisis)
* Repository: [hreisis/pirates](https://github.com/hreisis/pirates)
