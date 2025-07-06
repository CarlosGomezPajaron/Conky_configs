# My .conkyrc configs
These are my configurations of the wonderful ["conky"]( https://en.wikipedia.org/wiki/Conky_(software)) utility made public to not only share with everyone but also have easy access to them in case I were to change computers in the future. 

This software allows the user to display certain information on the desktop, such as component performance, system usage and even the time and date.

I would like to take this opportunity to thank [this guide](https://en.wikipedia.org/wiki/Conky_(software)](https://aprendolinux.com/monitoriza-con-estilo-en-linux-guia-completa-de-conky/)) for teaching me the the basics of using this software and allowing me to make these configurations based on the examples shown in the article. It was really helpful and I recommend checking it out.

----------------------------
<h2> How to apply the configs </h2>

<h3> Step 1: Install conky in your OS </h3>

Arch/Arch based: `sudo pacman -S conky`

Debian/Debian based: `sudo apt update; sudo apt install conky`

----------------------------
<h3> Step 2: Create (or open) a file named ".conkyrc" in your home directory </h3>

 `sudo nano ~/.conkyrc`

 ![Created file being correctly displayed](https://github.com/CarlosGomezPajaron/Conky_configs/blob/main/steps_images/conkyfile.png)
 
(NOTE: To edit how conky displays information, it is necessary to create the configuration file corresponding to it, here the changes to what it displays will be made)


----------------------------
(ADDITIONAL NOTE: Keep in mind that files that have a name which starts with a "." are hidden, therefore activating the visibility of hidden files is neccessary to open it from a DE or any kind of GUI)

----------------------------
<h3> Step 3: Once inside the file, copy and paste one of the various configs to your ".conkyrc" file </h3>

 ![Pasted conky config file](https://github.com/CarlosGomezPajaron/Conky_configs/blob/main/steps_images/pastedconfig.png)

(NOTE: To edit how conky displays information, it is necessary to create the configuration file corresponding to it, here the changes to what it displays by default will be made)

----------------------------

<h3> Step 4: Restart conky </h3>

`sudo pkill conkyrc`
 
`conky`
  
(NOTE: It is most likely that conky will restart itself automatically when changing the configuration file but this step is just in case it does not do so for you.)
  
----------------------------
<h3> Done: When restarted, conky should be working </h3>

Example of a basic conky config:

![Working conky with config file applied](https://github.com/CarlosGomezPajaron/Conky_configs/blob/main/steps_images/conkyfinal.png)
  
----------------------------


