# RiftADBMenu
riftadbmenu is a simple terminal-based script designed to make interacting with your Oculus device via ADB commands easier. It provides an interactive menu where you can list connected devices, run custom ADB commands, or reboot your device with just a few keystrokes.

This script is perfect for developers or advanced users who want to streamline their ADB workflow without typing long commands manually every time.

Features
Interactive Menu: Select from a list of ADB commands to execute on your Oculus device.

List Devices: Quickly list all devices connected via ADB.

Run Custom Commands: Run any ADB command on the connected Oculus device.

Reboot Device: Reboot your device directly from the menu.

Color-Coded Output: Enjoy a visually intuitive experience with different colors for each menu item and feedback message.

Installation
Clone or Download the repository to your machine.

If you're using Git:

bash
Copy code
git clone im too lazy go find it yourself in releases!!!
Navigate to the project folder in your terminal:

bash
Copy code
cd riftadbmenu
Make the script executable:

bash
Copy code
chmod +x riftadbmenu
Ensure ADB is installed: The script requires ADB (Android Debug Bridge) to interact with your Oculus device. You can install ADB with the following command:

macOS:

bash
Copy code
brew install android-platform-tools
Linux:

bash
Copy code
sudo apt install android-tools-adb
Windows: Download the ADB platform tools from the official website.

Usage
Connect your Oculus device to your computer via USB and enable Developer Mode (make sure ADB debugging is enabled on the device).

Run the script:

bash
Copy code
./riftadbmenu.sh
Select an option:

1: List connected devices.

2: Run a custom ADB command.

3: Reboot your Oculus device.

4: Exit the script.

Example Usage
bash
Copy code
$ ./riftadbmenu.sh
1. List devices
2. Run command
3. Reboot
4. Exit
Select option: 1
Listing devices...
List of devices attached
your-oculus-device-id  device
You can run custom ADB commands by choosing option 2, entering your desired command, and seeing the output directly in the terminal.

License
This project is licensed under the MIT License.

Contributing
Feel free to fork the repository, make changes, and create pull requests. If you have any suggestions or find any bugs, please open an issue.

Credits
This script was created by Atlee W.
