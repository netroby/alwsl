This project provides an easy way to install a custom, minimal, arch linux distribution as the WSL host.

If you want to try it right now, clone and run the alwsl batch file from a non-admin command prompt. 


## Install

To install archlinux  for windows 10. just download raw alwsl.bat to local. named as alwsl.bat

Then open windows CMD/powershell command, execute it 

```
alwsl.bat install
```

You will see like this :

```
alwsl (warn): There's already a WSL rootfs installed. We need to remove that. If you have data there,
alwsl (warn): cancel this and backup your rootfs.
Proceed with alwsl install and remove old rootfs now? [Y,N]?Y
alwsl (info): Cleaning old files.
alwsl (info): Installing base lxss fs from trusty server image. This will take A WHILE.
```

Choose yes to remove old rootfs then install new.



###### Update Mar 2017

We are happy to announce Fastly as a sponsor for a reliable and global delivery of alwsl root images and future updates. Fastly commited a monthly four-figure credit to the alwsl project which will help with alwsl's transition into a new version later this month.

Checkout Fastly's Open-Source efforts [here](https://www.fastly.com/open-source).

![](http://i.imgur.com/rjcltwk.png)

---

###### Update Jan 2017

We are currently negotiating with potential sponsors for a more stable delivery system for rootfs images and future updates to guarantee availability in all region at all times. In the meantime I have temporarily switched to a different internal CDN that should be faster. **If you still have an old copy of the batch script, where the CDN URL is not ___"antiquant.com"___, please download the current one!**

The next version will be released if a sponsor contract is signed. Current status: signing.

![](http://imgur.com/1T2dyE5.png)
