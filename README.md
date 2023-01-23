<pre>
##   ██████╗ ██╗      █████╗  ██████╗██╗  ██╗██╗  ██╗ █████╗ ████████╗
##   ██╔══██╗██║     ██╔══██╗██╔════╝██║ ██╔╝██║  ██║██╔══██╗╚══██╔══╝
##   ██████╔╝██║     ███████║██║     █████╔╝ ███████║███████║   ██║   
##   ██╔══██╗██║     ██╔══██║██║     ██╔═██╗ ██╔══██║██╔══██║   ██║   
##   ██████╔╝███████╗██║  ██║╚██████╗██║  ██╗██║  ██║██║  ██║   ██║   
##   ╚═════╝ ╚══════╝╚═╝  ╚═╝ ╚═════╝╚═╝  ╚═╝╚═╝  ╚═╝╚═╝  ╚═╝   ╚═╝   
##                                                                    
##   MM'""""'YMM          dP                         MP""""""`MM                                     oo   dP            
##   M' .mmm. `M          88                         M  mmmmm..M                                          88            
##   M  MMMMMooM dP    dP 88d888b. .d8888b. 88d888b. M.      `YM .d8888b. .d8888b. dP    dP 88d888b. dP d8888P dP    dP 
##   M  MMMMMMMM 88    88 88'  `88 88ooood8 88'  `88 MMMMMMM.  M 88ooood8 88'  `"" 88    88 88'  `88 88   88   88    88 
##   M. `MMM' .M 88.  .88 88.  .88 88.  ... 88       M. .MMM'  M 88.  ... 88.  ... 88.  .88 88       88   88   88.  .88 
##   MM.     .dM `8888P88 88Y8888' `88888P' dP       Mb.     .dM `88888P' `88888P' `88888P' dP       dP   dP   `8888P88 
##   MMMMMMMMMMM      .88                            MMMMMMMMMMM                                                    .88 
##                d8888P                                                                                        d8888P  
## 
##  ░▐█▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄█▄☆
##  ░███████████████████████  CEO & AMBASSADOR FOR DIGITAL PRIVACY
##  ░▓▓▓▓▓▓▓▓▓▓▓▓██▓▓▓▓▓▓▓▓◤        ░▒▓█►─═ Mr.Rico ═─►█▓▒░
##  ╬▀░▐▓▓▓▓▓▓▌▀█░░░█▀░             mr.rico@ethosprivacy.org
##  ▒░░▓▓▓▓▓▓█▄▄▄▄▄█▀╬░               --- & his team & ---
##  ░░█▓▓▓▓▓▌░▒▒▒▒▒▒▒▒▒
##  ░▐█▓▓▓▓▓░░▒▒▒▒▒▒▒▒▒           ...who shall remain anonymous
##  ░▐██████▌╬░▒▒▒▒▒▒▒▒      presenting you a choice for privacy & freedom
##  Always hunting for talented persons in the privacy space. coders, ethical hackers
##  UI, Design, software, Android, Asterix, security experts and hobyists alike!
##  If you have any skills listed above. HMU always open to support up and coming talent too!
</pre>

# privatechat server images

This is the source repository for building [privatechat service]
Docker images.

privatechat (thanks to snikket) is an open-source self-hosted personal messaging service. It aims to
provide an alternative to proprietary and centralized messaging platforms
while supporting all the expected features and being easy to use.

## Getting Started with Snikket

For instructions on getting started with Snikket, see the [Snikket installation
guide](https://snikket.org/service/quickstart/) on our website.

## Building images

This section is for people who want to build their own images of Snikket, e.g.
for development purposes.

### Requirements

 - GNU make
 - docker (tested on 19.03.5)
 - ansible (tested on 2.7 (debian buster))

### Building

Run `make`

### Running

The easiest way is to use docker-compose. Copy the file `snikket.conf.example` to
`snikket.conf` and edit the values in it. Then run:

```console
docker-compose up -d
```
