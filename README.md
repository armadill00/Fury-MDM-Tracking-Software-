# 🖥️ MDM Laptop Tracking Device
![furyyyyy-02](https://github.com/user-attachments/assets/d1181a51-c5de-4ba2-a718-4b4b5ca71ee9)


Welcome to the **MDM Laptop Tracking Device** repository! This project was developed from scratch, utilizing geocoding and geolocation APIs to provide **100% accurate** tracking for laptops. The solution is built using Python, C#, and Firebase, and is designed to run seamlessly in the background.

## 🌟 Features

- **Geocoding & Geolocation API Integration**: Provides precise tracking of laptops.
- **Real-Time Location Monitoring**: Updates the laptop's location in real-time.
- **Geofence**: Updates the laptop's locGeofence feature with PagerDuty alert when fence is crossed.
- **Firebase Integration**: Logs and stores location data securely.
- **Background Execution**: The script runs silently in the background, ensuring continuous monitoring.
- **Cross-Platform Compatibility**: Built with Python and C#, making it versatile and easy to deploy.

## 🚀 Getting Started

### Prerequisites

Before you begin, ensure you have the following installed:

- [Python](https://www.python.org/downloads/)
- [C# (.NET Core)](https://dotnet.microsoft.com/download)
- [Firebase Account](https://firebase.google.com/)

### Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/your-username/mdm-laptop-tracking-device.git
    ```

2. **Install Python dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

3. **Set up Firebase:**

    - Create a new project on Firebase.
    - Set up Firestore for real-time data logging.
    - Download the `google-services.json` file and place it in the project directory.

4. **Build the C# application:**

    - Open the project in your preferred IDE (e.g., Visual Studio).
    - Build the solution to generate the executable.

5. **Run the tracker:**

    ```bash
    python main.py (COMMING SOON!)
    ```

## 📈 Usage

Once the setup is complete, the tracking script will run in the background, logging location data to Firebase. You can monitor the location of your laptops via the Firebase console.

## 🛠️ Built With

- **Python** - The core language used for scripting.
- **C#** - Used for building the desktop application.
- **Firebase** - For real-time database and data logging.

## 🤝 Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

## 📄 License

This project is licensed under the MIT License.

## ✨ Acknowledgments

- **Geocoding & Geolocation API** - For providing precise location data.
- **Firebase** - For offering an excellent platform for real-time data storage.

---

Made with ❤️.
