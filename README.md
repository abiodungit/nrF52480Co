This project uses nordic nrF52480 development kit on nRF5_SDK_15.3.0_59ac345 SDK to implement beacon transmitter application such that can be identified by nRF Connect or nRF Beacon android applications. In addition, Device name is displayed and it also allows GPS coordinates to be given to the beacon via command from PC using C programming language.

The Device name to advertise is defined by "DEVICE_NAME " as "COMODL". Advertisement was initialised using "advertising_init(void)" to display manufacturer specific data on nRF Connect or nRF Beacon android applications. Function "advertising_start(void)" was used to initiate advertisement and " ble_stack_init(void)" was used to initialise the BLE event interrupt and softdevice. Power management was initialised using "power_management_init(void)", while the main() method serve as application entry. APP_BEACON_UUID contains the beacon proprietry user application UUID. 

A start code can be obtained from the nRF5_SDK_15.3.0_59ac345 examples.


