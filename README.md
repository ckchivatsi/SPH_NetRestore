# SPH_NetRestore
Collection of scripts to restore internet due to switch failure.

Problem:
    A core network switch crashes and goes to "switch>" prompt.

Solution:
    Using a Raspberry Pi or server/computer always connected to the switch, test internet connectivity. If there is internet failure run a script to restore the internet.
    Internet is lost when switch goes to switch> prompt mode.
    Use the console line to connected to the switch to and restore the switch to normal operation mode.
    Commands to use are "flash_init" to initialize the flash and "boot" to boot it up.

This project is meant to:
    - Test for internet availability. 
    (If no internet i.e. switch in switch> prompt mode)
    - Run script to restore the switch.

References: 
    connectivity?, S. (2018). Shell Scripting: Proper way to check for internet connectivity?. Retrieved from https://unix.stackexchange.com/questions/190513/shell-scripting-proper-way-to-check-for-internet-connectivity
    Python for Network Engineers | Articles. (2018). Retrieved from https://pynet.twb-tech.com/blog/automation/pyserial.html 
    ktbyers/pynet. (2018). Retrieved from https://github.com/ktbyers/pynet/blob/master/serial/cisco_serial.py