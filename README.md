# todayIlearn

---------Generate IBM Certificate and update the system first time in Rhel 8.3
1. After restart check if the registration process (a dialog box) is open asking a device registration
2. Check if Cisco anyconnect is connected with VPN, by default it should have connected after restart.
3. If the Cisco anyconnect is not able to connect then start the vpn manually
   - Command : /opt/cisco/anyconnect/bin/vpn connect sasvpn03.pok.ibm.com/gettingstarted
4. Start the registration process again if the vpn is started from command line above
   - Command : /opt/ibm/registration/registration.py
