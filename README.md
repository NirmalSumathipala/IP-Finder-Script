# IP-Finder-Script
This script creates a socket and then connects to a public DNS server at IP address 8.8.8.8 on port 80. The IP address of the computer is then returned by calling getsockname() on the socket object.

You can also use the ipaddress module to find the IP address of a computer.
This script uses the gethostname() function to get the hostname of the computer and then calls gethostbyname() to get the IP address associated with that hostname. The ip_address() function from the ipaddress module is then used to convert the IP address to an IPv4Address object, which can be printed or formatted as a string.
