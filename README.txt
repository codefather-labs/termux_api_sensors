Contains script for calling Android SensorAPI as well as the manifest for creating a package

Example Usage:

	termux-sensor -a
		* Listen to all sensors

	termux-sensor -s Accel,Gyro,Light
		* Listen to accelerometer, gyroscope, and light

	termux-sensor -s Accel -d 500
		* Listen to accelerometer and get updates every half second

	termux-sensor -l
		* Receive list of all sensors on device

	termux-sensor -c
		* Cleanup sensor resources... (Performed automatically on ^C interrupt)
