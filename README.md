###### <h2 align="center"> Void linux with LVM/LUKS encryption </h2>

**This script based on the official [Full Disk Encryption](https://docs.voidlinux.org/installation/guides/fde.html) guide from void linux**


**Warning**

###### While partitioning with cfdisk, create two partitions only ie, EFI and ROOT. Or make your own tweaks before running it


###### To, run the script from live iso:

```bash
xbps-install -Syu xbps git
```

```bash
git clone https://github.com/yperta/voidlvm
```

```bash
chmod +x baseLVM && ./baseLVM
```
