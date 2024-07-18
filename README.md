# inxifetch
inxifetch is an [inxi](https://codeberg.org/smxi/inxi) plugin and need [figlet](http://www.figlet.org/) to run properly<br>
### Required:
```
inxi
figlet
```
### Installation
1. Just download and install in your $PATH `inxifetch` script and make it executable. 
2. Create a folder `/etc/inxifetch` download and place there `inxifetch.conf`
3. Assume you download `inxifetch` script in your `/opt` If `/opt` its not in your user $PATH<br>
add this line in your ~/.bashrc `export PATH=$PATH:/opt` and dont forget to make it executable `sudo chmod +x /opt/inxifetch`


### Usage

```inxifetch```

Output is:<br> 
![](1.png)
<br>
![](ubuntu2.png)
<br>
![](slint.png)

You can modify `etc/inxifetch/inxifetch.conf` as you want to play with custom colors and fonts... <br>
<b>Examples:</b><br>
![](2.png)
<br>
![](3.png)
<br>
![](4.png)
<br>
![](5.png)

<br>Also you can use **all** ```inxi -options``` for more special output.   <br>
something like `inxifetch Fxx`<br>
![](a.png)
![](b.png)<br>
OR `inxifetch r`<br>
![](c.png)
![](d.png)
![](ubuntu1.png)
![](ubuntu3.png)

#### Have Fun  
In case you want to build it...<br>
Download from [release](https://github.com/rizitis/inxifetch/releases) 1.0.tar.gz<br>
md5: `3e5b7ff92c7953a7a1babad240560d97` <br>
And create your build script...<br>
`inxifetch` script should be installed in<br> `/usr/local/bin` **or** `/opt` <br>
and `inxifetch.conf` to `/etc/inxifetch`, so <br>`mkdir /etc/inxifetch` needed before.

--------------------------------------------------------------------------------
#### DONATE
--------------------------------------------------------------------------------
*I do not accept donations, but if you want to make a donation please donate to* **original inxi developer**:<br>
Help support the inxi project with a one time or a sustaining donation.

Paypal: https://www.paypal.com/donate/?hosted_button_id=77DQVM6A4L5E2

LiberaPay (sustaining donations): https://liberapay.com/smxi/<br>

Or to **figlet project**: http://www.figlet.org/




