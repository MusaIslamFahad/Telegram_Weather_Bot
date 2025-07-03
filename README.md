# 🌤️ Telegram Weather Bot – Real-Time Weather Updates for Dhaka

![Python](https://img.shields.io/badge/Python-3.x-blue.svg)
![PyTelegramBotAPI](https://img.shields.io/badge/PyTelegramBotAPI-Powered-blue.svg)
![APScheduler](https://img.shields.io/badge/APScheduler-Scheduled-green.svg)
![OpenWeatherMap](https://img.shields.io/badge/OpenWeatherMap-API-orange.svg)
![License](https://img.shields.io/badge/License-MIT-yellow.svg) 

This is a simple yet powerful Python-based Telegram bot that delivers real-time weather updates for Dhaka, Bangladesh using the OpenWeatherMap API. The bot is built with `pyTelegramBotAPI` (telebot) and scheduled using `APScheduler` to send hourly weather reports directly to your Telegram chat.

## 🚀 Features

* **📡 Live Weather Data:** Get current weather updates including temperature, humidity, wind speed, pressure, visibility, and more.
* **⏱️ Hourly Updates:** Automatically delivers weather information every hour using a background scheduler.
* **📍 City-Specific:** Currently configured for Dhaka, Bangladesh (can be easily customized).
* **🔒 Environment Variables:** Secures your API keys using environment variables (`BOT_TOKEN` & `WEATHER_API_KEY`).
* **🛠️ Start/Stop Control:** Start and stop weather notifications anytime with simple Telegram commands (`/start`, `/stop`).
* **🧪 Test Command:** Use `/test` to check if the bot is running correctly and to get an immediate weather report.

## 🧰 Technologies Used

* **Python 3:** The core programming language.
* **PyTelegramBotAPI (telebot):** A simple and easy-to-use Telegram bot API library for Python.
* **APScheduler:** A flexible library for scheduling tasks in Python.
* **OpenWeatherMap API:** Provides current weather data.

## 🔧 How to Use

Follow these steps to set up and run your Telegram Weather Bot:

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/your-username/telegram-weather-bot.git](https://github.com/your-username/telegram-weather-bot.git)
    cd telegram-weather-bot
    ```

2.  **Install Dependencies:**
    ```bash
    pip install -r requirements.txt
    ```
    (You'll need to create a `requirements.txt` file in your project with `pyTelegramBotAPI` and `APScheduler` listed).

3.  **Set Environment Variables:**
    Before running the bot, you need to set up two environment variables:
    * `BOT_TOKEN`: Your Telegram Bot token obtained from [@BotFather](https://t.me/BotFather).
    * `WEATHER_API_KEY`: Your API key from [OpenWeatherMap](https://openweathermap.org/api).

    **Example (Linux/macOS):**
    ```bash
    export BOT_TOKEN="YOUR_TELEGRAM_BOT_TOKEN"
    export WEATHER_API_KEY="YOUR_OPENWEATHERMAP_API_KEY"
    ```
    **Example (Windows - Command Prompt):**
    ```cmd
    set BOT_TOKEN="YOUR_TELEGRAM_BOT_TOKEN"
    set WEATHER_API_KEY="YOUR_OPENWEATHERMAP_API_KEY"
    ```
    (For persistent environment variables, refer to your operating system's documentation.)

4.  **Run the Script:**
    ```bash
    Telegram Weather Bot.py
    ```

5.  **Interact with your Bot on Telegram:**
    * Send `/start` to begin receiving hourly weather updates.
    * Send `/stop` to stop receiving hourly weather updates.
    * Send `/test` to get an immediate weather report and check if the bot is running.

## 📌 Future Improvements

* **Multi-city weather support:** Allow users to specify and receive weather updates for multiple cities.
* **Custom update intervals:** Enable users to set their preferred frequency for weather reports (e.g., every 3 hours, daily).
* **Forecast reports:** Provide hourly or daily forecast reports in addition to current weather.
* **Support for inline queries and buttons:** Enhance user interaction with inline queries for quick weather lookups and interactive buttons.

## 🤝 Contributing

Contributions are welcome! If you have suggestions for improvements or new features, please open an issue or submit a pull request.


