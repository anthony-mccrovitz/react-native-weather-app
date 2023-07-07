### React Native Weather Search App ⛈️

Welcome to the React Native Weather Search App repository! This app is designed to provide real-time weather updates and weekly forecasts for any location around the world. Built with React Native, Rapid API's weather API, Tailwind CSS, and Expo, this app is sleek, user-friendly, and highly functional.

---

### Installation 💻
Before we get started, make sure you have Node.js installed on your system.

Here are the steps to get this project set up on your local machine:

## 1. Clone the Repository
Start by cloning this repository to your local machine by running:

```
git clone https://github.com/YourUsername/ReactNativeWeatherSearchApp.git
cd ReactNativeWeatherSearchApp
```
Replace "YourUsername" with your actual GitHub username.

## 2. Install Expo CLI
Next, you will need the Expo command line interface. Install it globally with:

```
npm install -g expo-cli
```

## 3. Install Dependencies
Now, navigate into the cloned repository's directory and install the necessary npm packages:

```
npm install
```

## 4. Setup Tailwind CSS
To set up Tailwind CSS with React Native, install the required dependencies using:

```
npm install tailwind-rn
```

Then, generate the tailwind.js file:

```
npm create tailwind-rn
```
This will create a styles.json file in your root directory. Now, import it in your App.js file or wherever you want to use it:

```
import styles from './styles.json'
```

## 5. Run the App
Everything is set up! To start the app, run:
```
npx expo start
```

This will start a dev server for you and print a QR code in your terminal.

---

### Usage 🌐

Once the app is running, you'll see a search bar on the home screen. Here, you can enter the name of any city around the globe to fetch its current weather details and a weekly forecast. Once you submit the city name, the app will display all the weather information for that location.

Stay updated with real-time weather conditions and prepare for the week ahead with our detailed forecasts. Enjoy! 🌤️

If you have any questions or feedback, please feel free to raise an issue here or contact me directly. Contributions are always welcome! Happy coding! 🚀
