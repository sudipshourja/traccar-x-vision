### Configuration Process for TraccarXvision

#### **1. Configuring Traccar Client Devices**

1. **Install the Traccar Client App:**

   - Download the app from the following link: [Traccar Client App v7.7](https://github.com/traccar/traccar-client-android/releases/download/v7.7/app-regular-release.apk).
   - Install it on your Android device.

2. **Open the App:**

   - Upon opening the app, you will see a unique **Device Identifier**.

3. **Set Device Name:**

   - Type a name for the device.
   - Use the **Device Identifier** displayed in the app and click **OK**.

4. **Set Server URL:**

   - Tap **Server URL** and enter: `https://traccar-x-vision.duckdns.org/`.

5. **Activate the Service:**

   - Turn on **Service Status** by toggling the switch.
   - Tap the **Status** button in the top-right corner of the navigation bar.

6. **Verify Status:**

   - Ensure all statuses are positive (e.g., GPS, Network, and Service) to confirm proper configuration.

7. **Check Location:**

   - After a short while, the device’s latest location will appear in the system.

#### **2. Configuring the Telegram Bot**

1. **Access the Bot:**

   - Open the bot using this link: [TraccarXvisionBot](https://t.me/TraccarXvisionBot).

2. **Generate a Token:**

   - Log in to the **TraccarXvision Admin WebApp** and navigate to **Settings**.
   - Go to the **Token** tab and generate a new token.
   - Copy the generated token.

3. **Initialize the Bot:**

   - Send the `/start` command to the bot in Telegram.
   - Paste the copied token in the chat.

4. **Use Commands:**

   - Use `/location` to see the recent location of a device.
   - Use `/live` to get a live streaming link for a specified device.

#### **3. Configuring WebRTC Live Streaming**

1. **Install the Application:**

   - Download and install the application from the provided link: [TraccarXvision App](https://drive.google.com/file/d/1qWnmTNHPEF8E_YbFM3zxrkxFYNwn4e_Z/view?usp=sharing).

2. **Set Up the App:**

   - Open the app and tap the **Settings** icon in the top-right corner.
   - Enter the **Device Identifier** from the Traccar Client app.
   - Click **Connect** to establish a connection. The app will indicate when the connection is successful.

3. **Prevent Screen Lock:**

   - Ensure the screen stays on. The app prevents screen lock to maintain a continuous video feed without driver interaction.

4. **Access Live Streaming:**

   - Log in to the **Admin WebApp**.
   - Select a device and click the **Live Streaming** button on the floating tab below.
   - Alternatively, use the `/live` command in the Telegram bot and choose the device for which you want to view the live feed.

By following these steps, you can successfully configure Traccar devices, the Telegram bot, and the WebRTC live streaming system for seamless operation.

