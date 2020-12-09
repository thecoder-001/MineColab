<p align="center"><a href="https://github.com/thecoder-001/MineColab"><img src="https://github.com/thecoder-001/MineColab/blob/master/Logo.png" alt="Logo" height="80"/></a></p>
<h1 align="center">MineColab</h1>
<p align="center">Run Minecraft Server on Google Colab</p>
<a href="https://colab.research.google.com/github/thecoder-001/MineColab/blob/master/MineColab.ipynb" target="_parent"><img align="right" src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"></a>

## :hear_no_evil:  First of all, what is google Colab?
As the official FAQ says, colaboratory, or “Colab” for short, is a product from Google Research. Colab allows anybody to write and execute arbitrary python code through the browser, and is especially well suited to machine learning, data analysis and education. More technically, Colab is a hosted Jupyter notebook service that requires no setup to use, while providing free access to computing resources including GPUs.
In short, it is a vm provided for learning, running python code, machine learning or for general purpose.
## :moneybag:  Is it really free to use?
Yes, Colab is free to use. But there are some points which, according to me one should keep in mind:
1. Though colab is a free service, it shouldn't be exploited indiscriminately or without any care. One should value that its a resource offered for no cost and can get depleted/restricted if the demand increases out of control.
2. If it isn't obvious, one shouldn't run mission-critical services (like large and important servers/databases/python programs) on it. Its resources are not guaranteed and not unlimited, and the usage limits sometimes fluctuate. Also, the notebook has a maximum runtime of 12 hours, after which, it should be manually restarted.
3. One should not try to spread it as wildfire (in my opinion), that there's a free service available to every living being out there. If such a sudden boom in user base happens, Google would be forced to close down the free teir of google colab, devoiding many hobbists of the free service. Keep it like a secret, telling it to only those who are worthy and know how to use it.

In the end, it is just my personal opinion and can be ignored safely. Just ask your heart whats right and whats wrong. Also, please try to use it as a once in a while resource and not 24x7 so that others can avail the free resources too.
## :zap:  So, how does it actually work?
As Google Colab is a VM running Ubuntu server as base OS, it can be easily used as a Minecraft server. Here are the steps which the notebook performs to setup the server:
1. Update the system's apt cache.
2. Install Openjdk-15 (Java) through apt-get.
3. Mount Google Drive to access the minecraft folder (Drive is used here to provide persistent storage).
4. Setup Ngrok (by asking for key by user and opening a tunnel at port 25565).
5. Change directory to the minecraft-server folder on google drive (I have here used "Minecraft-server" as the server folder in the root directory of my Google Drive.
6. List/Print the file list on the screen to indicate succesful directory change.
7. Startup the Minecraft server (with optimized JVM parameters from [Aikar's guide)](https://aikar.co/2018/07/02/tuning-the-jvm-g1gc-garbage-collector-flags-for-minecraft/)

## 👍 Tips
- Use [RaiDrive](https://www.raidrive.com/) to manage your server's files

[![ForTheBadge built-with-love](http://ForTheBadge.com/images/badges/built-with-love.svg)](https://github.com/thecoder-001)

[![test](https://user-images.githubusercontent.com/25097841/101589531-a2c98100-3a0e-11eb-872e-fefa791aaaf6.gif)](https://github.com/thecoder-001/MineColab)

