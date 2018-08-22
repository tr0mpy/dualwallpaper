# dualwallpaper
Fetches images from URL and combines them into a single n-image wallpaper

Supported sites:
  - [unsplash](https://www.unsplash.com) (any size)
  - [mikedrawsdota](http://mdd.hirshon.net/) (1920x1080 only)
  
# Usage

## Windows
  - get/install [python 2.7](https://www.python.org/downloads/)
  - download dualwallpaper.pyw above
  - change config at line 26 in dualwallpaper.pyw (example below)
  - run dualwallpaper.pyw to get a new wallpaper
  
  
## Linux - doesn't work yet
  - Install python 2.7 and pip
    - `sudo apt install python python-pip -y`
 ```
 avalon@leroy:~$ python -V
 Python 2.7.15rc1
 ```
  - Clone this repo 
    - `git clone https://github.com/plomdawg/dualwallpaper.git`
  - Go into the directory
    - `cd dualwallpaper`
  - change line 26 in dualwallpaper.pyw (example below
  - Run the script
    - `python dualwallpaper.pyw`
  
```
# # # CONFIG # # #
# 2 monitors with dimensions 1920x1080
monitors = ["1920x1080", "1920x1080"]

# 3 monitors with various dimensions (from left to right)
# monitors = ["1280x720", "1920x1080", "1366x768"]

# uncomment to choose a website
#website = "mikedrawsdota"
website = "unsplash"
```
