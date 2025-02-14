
Create an ISO file with a stager in it

```
mkdir iso_root
cp msfstage_https_x64.exe ./iso_root

genisoimage -o meine_iso.iso -J -R -V "MEINE_ISO" iso_root/

```
