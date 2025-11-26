## ARCurrencyTimeline 

> Visualize Forex market trends in Augmented Reality on a vertical plane.

**ARCurrencyTimeline** is a Unity-based Augmented Reality application that generates a linear graph of Forex (Foreign Exchange) rates. Using the Alpha Vantage API, it fetches real-time data and visualizes currency timelines directly on your wall or any vertical surface.


## 🌟 Features

* **AR Visualization:** Projects a 3D line graph of currency data onto the real world.
* **Vertical Plane Detection:** Optimized for walls and vertical surfaces.
* **Live Data:** Integrates with **Alpha Vantage API** for accurate market data.
* **Interactive UI:** (Add any specific UI features here, e.g., "Select different currency pairs").

## 🛠 Tech Stack

* **Engine:** Unity 3D
* **AR Framework:** AR Foundation / ARCore / ARKit (Specify which one you used)
* **Data Source:** Alpha Vantage API
* **Language:** C#

## 📥 Download & Install

You can download the latest `.apk` file from the **[Releases](../../releases)** section of this repository.

1.  Download the `ARCurrencyTimeline.apk` file to your Android device.
2.  Enable "Install from Unknown Sources" in your settings if prompted.
3.  Install and run the application.
4.  Point your camera at a textured vertical surface (like a wall) to detect the plane and place the graph.

## ⚙️ For Developers: Build from Source

If you want to clone and edit the project, follow these steps:

1.  **Clone the repo:**
    ```bash
    git clone [https://github.com/YourUsername/ARCurrencyTimeline.git](https://github.com/YourUsername/ARCurrencyTimeline.git)
    ```
2.  **Open in Unity:**
    * Open Unity Hub and add the cloned folder.
    * *Note: This project was built with Unity Version 20XX.X.X (Insert your version).*
3.  **API Key Configuration:**
    * Get a free API Key from [Alpha Vantage](https://www.alphavantage.co/).
    * Open the script `ForexDataManager.cs` (or wherever your API logic is).
    * Paste your API key into the `apiKey` variable.
4.  **Build:**
    * Go to `File -> Build Settings`.
    * Switch platform to **Android**.
    * Click **Build and Run**.

**Screenshot**
![WhatsApp Image 2025-11-24 at 15 46 33_b0bcb797](https://github.com/user-attachments/assets/1182f868-3b5a-4e42-b320-8cfc1928d085)

## ⚠️ Important Note

The API Key is sensitive data. The key included in the source code (if any) is a placeholder. Please use your own Alpha Vantage API key to ensure rate limits are not exceeded.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Contact

* **Developer:** Rehan Shamim , Priyanshu Tiwari
* **GitHub:**
* **Email:**
* **LinkedIn**
