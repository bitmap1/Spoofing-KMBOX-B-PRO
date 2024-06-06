# Spoofing-KMBOX-B-PRO

Step 1:
Install uPyCraft - https://randomnerdtutorials.com/install-upycraft-ide-windows-pc-instructions/

Step 2:
Go to **tools** then on **serials** after choose the comport you want to use.
Now press on **device** and the **file** that pops up after clicking on **device**.

Step 3:
Find the Vendor ID (VID) and Product ID (PID), of your mouse.
You can do this by going into **device manager** on your pc.
Once there go to the mouse section, unplug your kmbox and any other mice or keyboards you have in your pc. Just have the one main mouse you play with.
Right click and go to properties
Then go to details, then select the Hardware IDs tab in the drop down menu
It should say VID_XXXX & PID_XXXX (where it says XXXX, it will be your mouse VID and PID, its a hexidecimal number 13AC for example)
Heres some screenshots to explain:
![image](https://github.com/bitmap1/Spoofing-KMBOX-B-PRO/assets/153444846/91300937-d402-4aa8-a3d8-eb5bac8efe20)
![image](https://github.com/bitmap1/Spoofing-KMBOX-B-PRO/assets/153444846/3063141f-efbd-45a9-b0f2-3b2bbbb39aaa)
![image](https://github.com/bitmap1/Spoofing-KMBOX-B-PRO/assets/153444846/87180c27-c212-428c-99a5-4c1b4d675035)
![image](https://github.com/bitmap1/Spoofing-KMBOX-B-PRO/assets/153444846/17268578-4189-4f9f-90fe-5afab7633ca6)
![image](https://github.com/bitmap1/Spoofing-KMBOX-B-PRO/assets/153444846/1221c230-6abe-48a0-9a9a-e5f7906b218c)
![image](https://github.com/bitmap1/Spoofing-KMBOX-B-PRO/assets/153444846/27101c11-d1a5-4fc0-a476-0031f1b8664d)
![image](https://github.com/bitmap1/Spoofing-KMBOX-B-PRO/assets/153444846/ed4b467b-974b-4d59-8050-2e8db42a1a5d)
![image](https://github.com/bitmap1/Spoofing-KMBOX-B-PRO/assets/153444846/627026e8-99b8-4f53-b5e9-7dba0796e2c5)

Step 4:
Navigate to the Boot.py file in uPyCraft
Scroll down unil you see VID and PID lines.
Remove the # before it if there is one. Then put your VID and PID there.
Press cntrl + s on your keyboard to save
Then type the command km.reboot() in the window below.
Heres a video going through this - https://youtu.be/8gk885n_o7g

Advice:
Always plug your mouse into the kmbox port to be sure your safe, dont plug into pc
![image](https://github.com/bitmap1/Spoofing-KMBOX-B-PRO/assets/153444846/0d58da18-4a6e-4d8e-82f9-2cc0f53acbbf)


You have now sucessfully spoofed your kmbox, good job!

