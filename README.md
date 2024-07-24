Include Libraries: Import `HTTPClient` and `WiFi` libraries.
![‏‏لقطة الشاشة (72)3](https://github.com/user-attachments/assets/c90e6649-362f-4b8e-b7e4-4d7961e411c4)


Define Variables: Set the URL, WiFi credentials, and LED pin.

![‏‏لقطة الشاشة (72)4](https://github.com/user-attachments/assets/64cc32aa-038d-4de4-b3d0-bfa0423c98b0)

Setup Function:
   - Initialize serial communication, Connect to WiFi using (connectWiFi), and Set LED pin mode and turn off the LED.
Loop Function:
   - Reconnect to WiFi if disconnected.
   - Print loop start message.
   - Create an HTTP client and make a GET request to the URL.
   - If the response is "stop", turn on the LED for 2 seconds.
   - Handle HTTP errors and connection issues.
   - Turn off the LED and wait for 500 milliseconds.
connectWiFi Function:
   - Set WiFi mode to station and connect using credentials.
   - Print connection progress and details upon success.
![‏‏لقطة الشاشة (74)](https://github.com/user-attachments/assets/2a7c81c0-6f82-4ed8-a9bb-7df2c43264d7)

     
