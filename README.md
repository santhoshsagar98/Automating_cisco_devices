# Program_to_configure_cisco_devices

This is a python program that uses paramiko module to connect to cisco devices one at a time and shows the present configuration. Then, it gives a menu to help configure the devices using information from CDP protocol.

This program does a number of things :

       1. Gets the running configuration.
       2. Gets the SSH credential.
       3. Gets CDP output.
       4. Analyses the CDP output and configures port status.
       5. Enables the user to overwrite the configuration to set up manually.
       6. Find the disabled ports in a device.
