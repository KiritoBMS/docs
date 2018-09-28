# How to connect to Verge

If you are using Windows, see [here](/index/faq/connecting-windows.md)
[Video tutorial](https://youtu.be/CoPyJt2QTHc)

### Modifying the `hosts` file

- Open `/etc/hosts` with your favourite editor **as root/with sudo**
- Paste the following at the bottom

```
163.172.71.251 osu.ppy.sh a.ppy.sh b.ppy.sh c.ppy.sh c1.ppy.sh s.ppy.sh
51.15.222.176 bm6.ppy.sh
```

- Save the file

## Installing the certificate

- Download certificate file from [here](https://example.com/)
- Open Internet Explorer configuration by running Wine Control
- Double click the Internet Settings icon, navigate to the Content tab, then click on "Certificates" button
- Click on "Import", then click on "Next"
- Click on "Browse" then select the downloaded file
- Click on "Next"
- Select "Place all certificates in the following store" and then click on "Browse"
- Select "Trusted Root Certification Authorities" from list and click on "Ok"
- Click on "Next" until you reach the end of the process

### After that is done, you can start the client up, and log in with your Verge credentials.