# youtube-tew

***youtube To ElseWhere*** · a simple script to download a video from youtube, save its thumbnail and print its title and description on your terminal.

>#### Dependencies:
>Be sure to install [**youtube-dl**](https://github.com/rg3/youtube-dl/) as this script heavily depends on it.  
You should find it quite easily on any Distro, for Arch Linux users:  
`sudo pacman -S youtube-dl`

I wrote it to easily move videos from my YouTube channel to BitChute, anyway youtube-dl supports many other websites therefore it should be able to get videos and info from many other youtube-like websites.

Here are 2 versions:
* the ***standard*** one which is spiced up with colors by using **tcat**.  
* a ***simple*** version that does what you need without any thrills.

#### To get the script:

`wget https://raw.githubusercontent.com/manero666/youtube-tew/master/youtube-tew`  
or  
`wget https://raw.githubusercontent.com/manero666/youtube-tew/master/youtube-tew-simple`

#### To use it:

`. youtube-tew URL`  
or make it executable and then:  
`./youtube-tew URL`

By default video and thumbnail are saved in your ~/Video/ directory and named with the video title (spaces between words are replaced by _ ).


---
TA SALÜDE
