When setting up AdGuard or similar DNS ad blocking service, Ubuntu requires that you turn off the stub listener service

```
systemctl stop systemd-resolved
sudo nano /etc/systemd/resolved.conf

	Uncomment and change to no (everything is commented out by default):

	DNSStubListener=no

systemctl start systemd-resolved
```