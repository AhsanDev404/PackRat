# PackRat 🎒

PackRat is the ultimate adventure planner designed for those who love to explore the great outdoors. Our app helps users plan and organize their trips with ease, whether it's a weekend camping trip, a day hike, or a cross-country road trip.

With PackRat, you can create and manage trips, discover new destinations, and stay informed with up-to-date weather forecasts. Our app integrates with Mapbox to provide you with accurate maps and directions to your destinations, as well as suggestions for popular outdoor activities based on the location and season of your trip.

So pack your bags, grab your friends, and get ready for your next adventure with PackRat!

## Features 🚀

- Create and manage trips: users can create new trips and manage existing ones by adding details such as dates, locations, and activities.
- Map integration: PackRat integrates with Mapbox to provide users with accurate maps and directions to their destinations.
- Activity suggestions: the app suggests popular outdoor activities based on the location and season of the trip.
- Packing list: users can create and manage packing lists for their trips to ensure they have everything they need.
- Weather forecast: PackRat provides up-to-date weather forecasts for the trip location to help users prepare accordingly.
- User authentication: the app uses user authentication to ensure privacy and data security.

## Technologies used 💻

PackRat is built using the following technologies:

- React Native: a JavaScript library for building user interfaces.
- Expo: a set of tools and services for building and deploying React Native applications.
- MERN stack: a collection of technologies including MongoDB, Express.js, React, and Node.js for building full-stack web applications.
- Redux: a predictable state container for JavaScript apps.
- Mapbox: a location data platform for mobile and web applications.

## Installation and Usage 📲

PackRat consists of two main components: a client and a server. Follow the steps below to install and run both components.

### Client

1. Navigate to the `client` directory: `cd client`.
2. Create a new file called `.env` and add the necessary environment variables. You can copy the `.env.example` file and replace the values with your own.
3. Install dependencies using `npm install`.
4. Start the app using `npm start`.

### Server

1. Navigate to the `server` directory: `cd server`.
2. Create a new file called `.env` and add the necessary environment variables. You can copy the `.env.example` file and replace the values with your own.
3. Install dependencies using `npm install`.
4. Start the server using `npm start`.

Make sure to start the server before starting the client, as the client relies on the server for data.

Note that the client and server are designed to run concurrently in development mode. To do so, follow these steps:

1. Navigate to the root directory.
2. Install dependencies using `npm install`.
3. Start the app using `npm run dev`.

This will start both the client and server simultaneously.

## Contributing 🤝

Contributions to PackRat are welcome! To contribute, follow these steps:

1. Fork the repository.
2. Create a new branch for your changes.
3. Make your changes and commit them.
4. Push your changes to your fork.
5. Create a pull request.

## License 📝

PackRat is licensed under the MIT License. See `LICENSE` for more information.
