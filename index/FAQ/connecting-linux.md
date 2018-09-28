# How to connect to Verge

### IMPORTANT: If you are using Windows, see [here](/index/FAQ/connecting.md)

[Video Tutorial](https://youtu.be/CoPyJt2QTHc)

## Modifying the hosts file

For this, you will need to modify your hosts file. To do so, run nano /etc/hosts as root/with sudo.

When you’ve got it open, paste the following at the bottom:

163.172.71.251 osu.ppy.sh a.ppy.sh b.ppy.sh c.ppy.sh c1.ppy.sh s.ppy.sh
51.15.222.176 bm6.ppy.sh

CTRL+X and then Enter to save the file.

## Installing the certificate

1. Download the certificate.

2. Open the Internet Explorer configuration by running wine control.

3. Double click the Internet Settings icon, navigate to the Content tab, then click the Certificates… button.

4. Click on Import, then Next.

5. Click Browse… then select the Verge certificate.

6. Click Next.

7. Select Place all certificates in the following store, and click Browse.

8. Select Trusted Root Certification Authorities, and click Ok.

9. Click Next, Finish.

10. You should get a message saying The import was successful.

## After that is done, you can start the client up, and log in with your Verge credentials.