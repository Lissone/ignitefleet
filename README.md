<h1 align="center">
  Ignite Fleet
</h1>

<p align="center">
  <a href="#description">Description</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#demonstration">Demonstration</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#requirements">Requirements</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#technologies">Technologies</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#layout">Layout</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#usage">Usage</a>

</p>
<br />
<p align="center">
  <img src="https://img.shields.io/static/v1?label=license&message=MIT" alt="License">
  <img src="https://img.shields.io/github/repo-size/Lissone/ignitefleet" alt="Repo size" />
  <img src="https://img.shields.io/github/languages/top/Lissone/ignitefleet" alt="Top lang" />
  <img src="https://img.shields.io/github/stars/Lissone/ignitefleet" alt="Stars repo" />
  <img src="https://img.shields.io/github/forks/Lissone/ignitefleet" alt="Forks repo" />
  <img src="https://img.shields.io/github/issues-pr/Lissone/ignitefleet" alt="Pull requests" >
  <img src="https://img.shields.io/github/last-commit/Lissone/ignitefleet" alt="Last commit" />
</p>

<p align="center">
  <a href="https://github.com/Lissone/ignitefleet/issues">Report bug</a>
  ·
  <a href="https://github.com/Lissone/ignitefleet/issues">Request feature</a>
</p>

<br />

## Description

Ignite Fleet is a mobile app designed for small businesses that manage transport vehicles used for product pick-up and delivery services. It allows users to track the history of their vehicles' departures and arrivals in real-time, making it easier to manage fleet logistics and control operations.

This project also marked my first experience using Realm (MongoDB Atlas) as a cloud database, with an offline-first approach that enables data synchronization stored locally on the mobile device, ensuring information is cached and accessible even without an internet connection. Additionally, I integrated the Google Maps API from Google Cloud Platform to retrieve and display location data, providing accurate and efficient visualization of vehicle routes and stops. These technologies together enabled a robust and reliable solution for fleet management.

## Demonstration

## Requirements

- [Nodejs](https://nodejs.org/en/)
- [Yarn](https://classic.yarnpkg.com/lang/en/docs/install/#windows-stable)
- [Expo](https://docs.expo.io/)
- [Android Studio](https://react-native.rocketseat.dev/virtual-devices/android-emulator)

## Technologies

- React Native
- Expo
- Typescript
- Styled Components
- Async Storage
- Realm (MongoDB Atlas)
- Google Cloud Platform
  - Google Maps API
- Expo Location
- Expo Task Manager
- Testing Library
- Phosphor

## Layout

You can view the project layout via this <a href="https://www.figma.com/design/Ax0M2OdiDwM1Gw6clv3t79/Ignite-Fleet?node-id=47-2&t=CQYKzsJDJgu8pa0J-1" target="_blank">link</a>.

## Usage

You can clone it on your pc using the command:

```bash
git clone https://github.com/Lissone/ignitefleet.git
cd ignitefleet
```

### Add environment variables

```bash
# .\.env

# MongoDB Atlas
REALM_APP_ID=

# Google Cloud Platform
ANDROID_CLIENT_ID=
IOS_CLIENT_ID=
WEB_CLIENT_ID=

GOOGLE_MAPS_API_KEY=
```

### Install dependencies

```bash
yarn
#or
expo install
```

### Run project

```bash
yarn start
#or
expo start
```

## License

Distributed under the MIT License. See `LICENSE` for more information.

<h4 align="center">
  Made with ❤️ by <a href="https://github.com/Lissone" target="_blank">Lissone</a>
</h4>

<hr />
