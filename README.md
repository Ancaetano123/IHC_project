# IHC Project

Mobile application to explore nearby points of interest (POI), developed in React Native with Expo. Allows you to view locations on the map, search, add new points with photo, description, and category, and get routes.

## Demo

The project can be run locally on Android/iOS devices or emulators using Expo Go.

## Features

- View points of interest on the map (Google Places + user-created locations)
- Smart search with Google Places suggestions
- Add new POIs with photo, name, description, and category
- Select categories to filter locations (restaurants, cafés, hotels, etc.)
- View location details, including image, address, and reviews
- Get routes to the selected location
- Modern and responsive interface

## How to run in development mode

Clone the repository:

```sh
git clone https://github.com/Ancaetano123/IHC_project
cd IHC_project
```

Install dependencies:

```sh
npm install
# or
yarn
```

Start the Expo development server:

```sh
npx expo start
```

Open the app on your mobile device with the [Expo Go](https://expo.dev/client) app or on an Android/iOS emulator.

## How to build for production

To generate a build for Android/iOS:

```sh
npx expo build:android
npx expo build:ios
```

See the [Expo documentation](https://docs.expo.dev/distribution/building-standalone-apps/) for details on publishing.

## Technologies used

- **React Native** — cross-platform mobile development
- **Expo** — tools and bundler for React Native
- **Google Maps & Places API** — maps and location data
- **JavaScript/TypeScript** — main language

## Credits & Inspiration

Developed by António Caetano.

Some ideas and components inspired by examples from the Expo and Google Maps documentation.

Images, graphics, and code are original.

---

Have fun exploring and contributing to the IHC Project!
