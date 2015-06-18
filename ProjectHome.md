This is a small program written in python to automate network devices configuration. The user will update a devices list file with and point to a configuration file to be applied for each device. The program will telnet into each device applying the configuration assigned to that device.

Currently only Cisco Routers and Switches are supported over telnet. More devices/protocols to come soon.

The script is good for those who study CCIE, as it can be used in loading initial configurations for study Labs or backup of configuration files when the LAB is finished.

Its also useful when you need to apply the same piece of configuration to multiple devices at once.

It also can be scheduled to apply configuration on a given time while you are not there.