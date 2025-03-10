# Travel App

## 📌 Project Summary

This project is a custom-built travel application that integrates multiple APIs to provide weather forecasts and location images. Users can enter their travel destination and departure date to receive weather forecasts and relevant location images.

The project focuses on JavaScript while ensuring clean and appealing HTML/CSS. It incorporates DOM manipulation, object handling, and API integration. The application runs in a Webpack environment with an Express server and service workers.

---

## ✨ Features

- **User Input:** Enter a destination and departure date.
- **Weather Forecast:**
  - Current forecast for trips within a week.
  - Predicted forecast for future trips.
- **Location Image:** Displays an image of the destination.
- **API Integrations:**
  - [Geonames API](http://www.geonames.org/) for location coordinates.
  - [Weatherbit API](https://www.weatherbit.io/) for weather data.
  - [Pixabay API](https://pixabay.com/api/docs/) for location images.
- **Service Workers:** Caches assets for a better user experience.
- **Express Server:** Manages API requests securely.
- **Webpack Environment:** Bundles and optimizes assets.

---

## 🔧 Technologies Used

- JavaScript (ES6+)
- HTML5 & CSS3 (SCSS)
- Node.js & Express.js
- Webpack
- Service Workers
- Fetch API & Async/Await

---

## 🚀 Installation & Setup

### **1️⃣ Clone the Repository**

```sh
git clone https://github.com/dana-akesh/travel-app.git
cd travel-app
```

### **2️⃣ Install Dependencies**

```sh
npm install
```

### **3️⃣ Set Up Environment Variables**

Create a `.env` file in the root directory and add your API keys:

```
GEONAMES_USERNAME=your_username
WEATHERBIT_API_KEY=your_api_key
PIXABAY_API_KEY=your_api_key
```

### **4️⃣ Start the Development Server**

```sh
npm run start
```

### **5️⃣ Build for Production**

```sh
npm run build
```

---

## 📌 Usage

1. Enter a destination and travel date in the input fields.
2. Click the "Search" button to fetch travel details.
3. View the weather forecast and location image.

---

## 🔍 Project Structure

```
travel-app/
│-- src/
│   │-- client/
│   │   ├── js/ (JavaScript functions)
│   │   ├── styles/ (SCSS files)
│   │   ├── views/ (HTML templates)
│   │   ├── index.js (entry point)
│   │-- server/
│   │   ├── index.js (Express server)
│   │   ├── routes.js (API handling)
│-- webpack.config.js
│-- .env (API keys)
│-- package.json
│-- README.md
```

---

## 🛠 Future Improvements

- Add user authentication.
- Implement a database for saving trips.
- Enhance UI/UX with animations and responsiveness.
- Optimize performance using lazy loading.

## 🛠 Node.js Version

This project uses Node.js version `v20.17.0`.

## Project Dependencies

This project requires the following dependencies to run:

### Dependencies

- `body-parser@^1.20.2`
- `cors@^2.8.5`
- `dotenv@^16.4.7`
- `express@^4.19.2`
- `webpack@^5.94.0`

### Dev Dependencies

- `@babel/core@^7.5.4`
- `@babel/preset-env@^7.5.4`
- `@testing-library/dom@^10.4.0`
- `@testing-library/jest-dom@^6.5.0`
- `babel-loader@^8.0.6`
- `body-parser@^1.20.2`
- `clean-webpack-plugin@^4.0.0`
- `cors@^2.8.5`
- `css-loader@^3.6.0`
- `css-minimizer-webpack-plugin@^7.0.0`
- `dotenv@^16.4.7`
- `express@^4.19.2`
- `file-loader@^6.2.0`
- `html-webpack-plugin@^5.6.0`
- `jest-environment-jsdom@^29.7.0`
- `jest-fetch-mock@^3.0.3`
- `jest@^29.7.0`
- `mini-css-extract-plugin@^2.9.1`
- `sass-loader@^10.0.0`
- `sass@^1.56.0`
- `style-loader@^0.23.1`
- `supertest@^7.0.0`
- `terser-webpack-plugin@^5.3.10`
- `webpack-cli@^5.1.4`
- `webpack-dev-server@^5.0.4`
- `webpack@^5.94.0`
- `workbox-webpack-plugin@^7.1.0`
