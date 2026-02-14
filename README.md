# Ultimate-TTS-Studio-SUP3R-Edition

A Pinokio script for https://github.com/SUP3RMASS1VE/Ultimate-TTS-Studio-SUP3R-Edition

Install this version of the pinokio script if you want to be able to use Ultimate TTS Studio 
in 2026, until a more permanent fix arrives to an app-breaking issue caused by changes to the site-package 
called setuptools in versions 81 and above which causes a failure to install many of this app's best TTS 
model options. 

Due to the fact that this app's requirements.txt file lists a large number of required modules without specifying
many of their version numbers, as well as a failure to include Qwen3-TTS and Chatterbox-TTS as required modules 
in the first place, it is highly possible that this install script will break again in the near future. If that happens 
the chances of me coming back here to fix it again are low due to the stupidly long amount of time it took me to
even diagnose what was going wrong in the first place. Thankfully my fix was easy to implement, but who knows
if that'll be the case next time all of the dependencies break.

If you can't tell, I'm slightly baffled by what turned out to be the problem with this app, mainly because 
trying to run this after my first install attempt caused some kind of wild installation-failure-loop that resulted
in a .txt file being created in my "pinokio/logs" folder that grew from 1Kb to 204GB in size in the time it took me to
notice that my SSD had suddenly been filled to the brim. I have genuinely never seen that happen with any piece of software
and I've also never seen a .txt file with a size of 204GB. Imagin trying to open that thing in notepad. That would be a 
sure-fire GG gamers.

Anyway, rant over. Peace out!

- Kassandra G.
