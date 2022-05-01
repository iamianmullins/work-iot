# work-iot
WorkIOT is a resistance training IOT project which is comprised of two separate components. An android mobile application and a sensor centric hardware component. The hardware component is comprised of a Raspberry Pi device which is embedded in a barbell weight plate. Core code for the hardware and any peripherals is programmed in Python and is designed to utilize gyroscope and accelerometer sensors attached via the GPIO pins. These sensors generate useful data whilst a user performs key compound weightlifting movements. The data is then sent to Firebase real-time database for consumption. A companion android mobile application written in Kotlin is then used to access analytics derived from the data stored in Firebase. This provides a lifting history for a user and displays useful information to help the user identify aspects to their training regime which may require work. The android application also serves to facilitate manually adding , viewing, editing and deleting workouts.

Link to [Work-IOT-mobile](https://github.com/iamianmullins/work-iot-mobile)

Link to [Work-IOT-device](https://github.com/iamianmullins/work-iot-device)
