# LocationDetails
# Location Details Project

This project consists of a **Frontend (Angular)** and a **Backend (Spring Boot)** that fetch location-based data and provide various features related to nearby places and weather conditions.

## Features

### General Features:
1. Fetches your current location and provides temperature details.
2. Displays nearby places with available categories.
3. Lists closest places first, sorted by distance (in km).
4. Provides a button to open locations directly in Google Maps.

### Search Feature:
- Allows searching for places.
- For each searched place, it provides:
  1. Temperature and weather conditions.
  2. Nearby places categorized appropriately.
  3. Distance-based sorting of locations.
  4. Option to open in Google Maps.

## Deployment
- **Frontend** is hosted on **Netlify**: [Location Details](https://locationdetails.netlify.app/)

## Frontend Setup (Angular)
1. Clone the repository:
   ```sh
   git clone https://github.com/your-repo/frontend.git
   ```
2. Navigate to the project folder:
   ```sh
   cd frontend
   ```
3. Install dependencies:
   ```sh
   npm install
   ```
4. Run the development server:
   ```sh
   ng serve
   ```
5. Open the browser and navigate to:
   ```
   http://localhost:4200
   ```

## Backend Setup (Spring Boot)
1. Clone the backend repository:
   ```sh
   git clone https://github.com/haneeth25/LocationDetailsBackend.git
   ```
2. Navigate to the project folder:
   ```sh
   cd LocationDetailsBackend
   ```
3. Run the Spring Boot application:
   ```sh
   mvn spring-boot:run
   ```
4. The backend will start on:
   ```
   http://localhost:8080
   ```

## Technologies Used
- **Frontend**: Angular, Bootstrap
- **Backend**: Spring Boot
- **Hosting**: Netlify (Frontend), GitHub (Backend Code)

