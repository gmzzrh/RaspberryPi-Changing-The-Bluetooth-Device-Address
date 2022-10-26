# Changing-RaspberryPi-Bluetooth-Device-Address

Changing Raspberry Pi Bluetooth Device Address
It is aimed to change the address of the bluetooth device attached to the Raspberry Pi with bdaddr. It was needed to distinguish between devices that came with the same address.
First, bdaddr is installed on the Raspberry Pi. The first command is to install the prerequisite packages. Continue by typing "E".

![1](https://user-images.githubusercontent.com/13950138/198032544-fec17082-2e48-43b5-8857-b3e2a9f0eada.png)

The bdaddr archive file is downloaded and unarchived.

![2](https://user-images.githubusercontent.com/13950138/198032549-b9ba3c80-53c5-45c0-b6a9-6fde4a8fe1b2.png)
![3](https://user-images.githubusercontent.com/13950138/198032552-ab6260dd-b26e-41b0-880d-35d20fdfc858.png)
 
The upload is complete.

![4](https://user-images.githubusercontent.com/13950138/198032555-0754ff79-fc9e-4618-a490-a20e0a0ec7f1.png)
 
Connected bluetooth devices are listed and go to the installed bdaddr directory.

![5](https://user-images.githubusercontent.com/13950138/198032557-0d161362-482d-4a4b-bd02-3c29163476b2.png)
 
hci0 belongs to the bluetooth device we just plugged in and its information is displayed. With the written command, a new address is given to hci0.

![6](https://user-images.githubusercontent.com/13950138/198032559-6c0a1ce3-9575-4492-b4ca-1437a424e94c.png)
 
hci0 is reset and bluetooth services are restarted.

![7](https://user-images.githubusercontent.com/13950138/198032561-bb979052-60ef-452b-bc13-f97aac87be05.png)
 
When bluetooth devices are listed again, it is seen that the address has been updated.

![8](https://user-images.githubusercontent.com/13950138/198032563-6cdabb23-a424-42b0-88a1-c8941bdf8601.png)
 
Details of Bluetooth devices can also be accessed with the following command. The port number is 2 in the section indicated by 1-1.4.2.

![9](https://user-images.githubusercontent.com/13950138/198032564-36664e64-ce40-437f-bfac-cd56c26d050f.png)
