The goals of the Mini-Project are to work with Raspberry Pi hardware and Python to use the Raspberry Pi as a wireless sensor for WiFi and Bluetooth.

After setting up the Raspberry Pi through installing the software onto the microSD card, the functions provided on the Senior Design Github page were utilized.
First, we collected nearby WiFi signals wirelessly using the Raspberry Pi. We collected data in BU's GSU and in the ECE Senior Design Lab for about 15 minutes each.
Once the scanning was complete, the data was saved to a JSON file which we saved to our Laptop's Desktop. We initally tried to copy the file over SSH; however, we could not get the command to work correctly. Therefore, we copied the JSON files via Google Drive.
After copying the files to our laptop's desktop, we were able to run the function **wifi_scan.py** in our laptop's terminal.

GSU Result:
![Figure_1](https://user-images.githubusercontent.com/55505652/133662423-a322d3da-cd5d-4e0f-8ef1-e844e4ca7895.png)

ECE Lab Result:
![Figure_2](https://user-images.githubusercontent.com/55505652/133662450-d2283e5e-bba1-4a01-827c-caf6bbd4fd0c.png)