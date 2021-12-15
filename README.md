# robosys_device_drivers
This is a repository for doing Task of 1 of Robotics Sysytems.

#  usage environment
Raspberry Pi4 4GB

# Things to prepare
led
resistor
breadboard
jumper wire

# Explanation
You can turn on the LED by connecting the LED to GPIO25 and GND and compiling.

# List of commands to use
make

sudo insmod myled.ko

sudo rmmod myled

sudo chmod 666 /dev/myled0

echo 1 > dev/myled0

echo 0 > dev/myled0



