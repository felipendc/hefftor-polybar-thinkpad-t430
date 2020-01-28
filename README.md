![logo](https://raw.githubusercontent.com/adi1090x/polybar-themes/master/previews/logo.png) <br />
Down below you will find a modified version of the Polybar baked-in [Arcolinux-Hefftor-HLWM](https://www.youtube.com/watch?v=iwWSqCDeWgk). 
##

***Hmmm... I know you also want to listen to this song... Hey, [Don't](https://www.youtube.com/watch?v=wVd0s7scl5U) tell [anybody](https://www.youtube.com/watch?v=hQ4r_kcvClE)...*** <br />
![Demo](https://i.imgur.com/pveWRoI.jpg) <br />
##

***I added my city to the weather moduled, & Bye bye, Discord... Chromium is in the building!!!***<br />
I just did some light changes on its weather module, I changed the Discord module to Browser (Chromium). <br />
![Demo](https://i.imgur.com/j9PV0Cj.jpg) <br />
##

***Yeah, my laptop screen is prety small... So, I did what I had to do. I know, It's sad..***<br />
The padding between the Modules had to be resized to '1' to fit on my Thinkpad-T430 Screen. <br />
![Demo](https://i.imgur.com/szQaf0Z.jpg) <br />
##

***Without that awesome font, I wouldn't be able to enable the browser icon... It was close...***<br />
I Imported the Icomoon font to the 'config' file, so that, I was able to enable the Chromium Browser Icon. <br />
![Demo](https://i.imgur.com/YPpJtqX.jpg) <br />
##

***Hm... as I sad, my laptop screen is pretty small. It was needed.*** <br />
And to wrap it up, I also removed the Memory Ram Module, just to get more room on the Polybar. <br />
##


In order to use that 'Browser Icon' on the Polybar, don't forget to install 'Chromium'.

<pre>trizen -S chromium</pre>


## Hey, bruh, what if I don't want to use Chromium Browser? <br />

Well, It's pretty simple. You just need to go to:<br />

<pre> cd ~/.config/polybar/</pre>

And edit the *'Config'* file. <br />

## Oh, God! How can I connect to a wifi connection? Where's the wifi icon? <br />

Relax, You just need to open your lovely "Terminal" and type: <br />

<pre>nmcli d wifi list</pre>

This command above will list all the wifi connections available. So, you just need to copy the name of the wifi you want to connect. You will find it under 
*SSID* row. <b />
##

Then, use this command: <br />

<pre>nmcli d wifi connect *'YYYYY'* password *'XXXXX'* </pre>

Instead of *'YYYYY'* you will put the name of your wifi <br />
Instead of *'XXXXX'* you will put your password <br />


## Now, take a look at the screenshot below down below and see it's done:






