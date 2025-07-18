# EVverse: Electric Vehicle Route Planner

EVverse is a responsive web application built with React and TypeScript, utilising Vite for fast development and the Google Maps API for electric vehicle (EV) route planning and charging station lookup. It empowers users to plan efficient EV routes with optimized charging stops based on vehicle battery range and charge level, and locate nearby charging stations with detailed information such as connector types, power output, and user ratings. The project is actively developing a **booking feature** to allow users to reserve chargers in advance, addressing the charger shortage problem with a practical and user-first approach.

## Features

- **Route Planning**: Generate EV routes with automatic suggestions for charging stops tailored to the selected EV model, battery range, and current charge level.
- **Charging Station Lookup**: Search for nearby charging stations, displaying details like connector types (e.g., CCS, CHAdeMO), power output (kW), and user ratings.
- **Charger Booking (In Development)**: Enable users to reserve charging stations in advance, tackling charger shortages with a seamless, user-centric interface.
- **Round-Trip Support**: Plan round trips with a comprehensive route summary, including total distance, estimated time, and required charging stops.
- **Type-Safe Development**: Leverage TypeScript for robust, type-safe components and logic, ensuring maintainable and error-free code.
- **Responsive UI**: Deliver an intuitive and modern user interface with Lucide React icons for enhanced user experience across devices.
- **Secure Configuration**: Manage Google Maps API key securely using environment variables to protect sensitive data.
- **Fast Development**: Utilize Vite for rapid builds, hot module replacement, and an efficient development workflow.

## Setup

To run EVverse locally, follow these steps:

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/username/evverse.git
   cd evverse
   ```

2. **Install Dependencies**:

   ```bash
   npm install
   ```

3. **Configure Environment**:

   - Create a `.env` file in the project root.
   - Add your Google Maps API key (with Maps JavaScript API, Places API, Geocoding API, and Directions API enabled):

     ```env
     VITE_GOOGLE_MAPS_API_KEY=your_key_here
     ```
   - Obtain a key from Google Cloud Console.

4. **Build the Project**:

   ```bash
   npm run build
   ```

5. **Run Locally**:

   ```bash
   npm run dev
   ```

   Open `http://localhost:5173` in your browser.

## Technologies

- **React**: Frontend framework for building dynamic and interactive user interfaces.
- **TypeScript**: Static typing for robust and maintainable code.
- **Vite**: Next-generation build tool for fast development and optimized production builds.
- **Google Maps API**: Enables route planning, charging station lookup, and geocoding functionality.
- **Lucide React**: Icon library for a modern and consistent UI design.
- **Node.js**: Runtime environment for development and build processes.
- **Git**: Version control for collaborative development and deployment.

## License

This project is licensed under the MIT License.
