This fork contains some changes for private use!
=============





REMOTE WAKE/SLEEP-ON-LAN SERVER *(RWSOLS)*
==========================================
The Remote Wake/Sleep-on-LAN Server (RWSOLS) is a simple webapp that runs on your Raspberry Pi to turn it into a remotely accessible Wake/Sleep-On-LAN Server. This is very useful when you have a high-powered machine that you don't want to keep on all the time, but that you want to keep remotely accessible for Remote Desktop, SSH, FTP, etc. Wake-On-LAN packets cannot be forwarded through a router, so to wake up a remote machine behind a router, you need to have something on its local network to wake it up. That's where RWSOLS comes in. RWSOLS can control an unlimited number of remote machines on its local network, and is capable of waking them up (any OS) or putting them to sleep (only Windows remote machines). It can be configured to use SSL encryption or it can be run over traditional HTTP.
  
A very detailed set of [installation instructions](https://github.com/sciguy14/Remote-Wake-Sleep-On-LAN-Server/wiki/Installation) can be found in the GitHub Wiki.
  
You'll also find a description of [how it works](https://github.com/sciguy14/Remote-Wake-Sleep-On-LAN-Server/wiki/How-it-Works), [an FAQ](https://github.com/sciguy14/Remote-Wake-Sleep-On-LAN-Server/wiki/Notes-and-FAQs), and a list of [relevant terminology](https://github.com/sciguy14/Remote-Wake-Sleep-On-LAN-Server/wiki/Terminology) on the Wiki.
  
For more info, see [my blog post about RWSOLS](http://www.jeremyblum.com/2013/07/14/rpi-wol-server/) on my website.
  
If you're having problems with getting RWSOLS working, check the [FAQ](https://github.com/sciguy14/Remote-Wake-Sleep-On-LAN-Server/wiki/Notes-and-FAQs) first, or [the comments](http://www.jeremyblum.com/2013/07/14/rpi-wol-server/#comments) on my blog. If you still can't get it to work, please [create a GitHub issue](https://github.com/sciguy14/Remote-Wake-Sleep-On-LAN-Server/issues) with specific details.

License
-------
This work is licensed under the [GNU GPL v3](http://www.gnu.org/licenses/gpl.html).
Please share improvements or remixes with the community, and attribute me (Jeremy Blum, <http://www.jeremyblum.com>) when reusing portions of my code.

Other contributors to this work include:
- Felix Ryan (https://www.felixrr.pro)
