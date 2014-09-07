networkcfgtoolssh
=================

Python script for pushing the same configuration (stored in a predefined file) on multiple devices at the same time via SSHv2.  The script reads the IPs of the devices from the NETWORK_IP file, then gets the SSHv2/Telnet credentials from the SSH_USERPASS file and sends the commands you enter in the CMD_FILE file to all the devices.  The script also checks if all the needed files exist, if all the IP addresses are valid and if all the devices are reachable.  Tools used: Python 2.7.3, GNS3, Linux.
