How it works
=======

- Scan the networks.
- Select network.
3. Capture handshake (can be used without handshake)
4. We choose one of several web interfaces tailored for me (thanks to the collaboration of the users)
5. Mounts one FakeAP imitating the original
6. A DHCP server is created on FakeAP
7. It creates a DNS server to redirect all requests to the Host
8. The web server with the selected interface is launched
9. The mechanism is launched to check the validity of the passwords that will be introduced
10. It deauthentificate all users of the network, hoping to connect to FakeAP and enter the password.
11. The attack will stop after the correct password checking# WOLFTOOL

How to use
=======

```
$ chmod +x wolf
$ ./wolf
```
