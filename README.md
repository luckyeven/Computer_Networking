# Computer_Networking

# Environment Set up
* Install VirtualBox
* Install Ubuntu
* Set up SSH prot forwarding to VM
    * Network settings -> advanced
    * Add a port forwarding rule
Give it a name, and use the following settings:
    ```BUSH
    protocol: TCP
    Host IP: 127.0.0.1
    ost Port: 2222
    Guest IP: (leave blank)
    Guest Port: 22```