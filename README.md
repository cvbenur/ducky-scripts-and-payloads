# **Ducky Scripts and Payloads**

A collection of original or modified Rubber Ducky scripts.
All of these scripts are written in Ducky Script and are free to use.

<br>



## **What's in there ?**

In this archive are Rubber Ducky scripts, all sorted by OS.<br/>

**NOTE :** Some linux distributions have specificities, therefore distribution-specific scripts are stored in directories labeled as the name of the distribution. <br>
>   **E.g.** For Kali Linux, which has a different terminal, the scripts are stored in the `/payloads/linux/kali/` directory.

<br>



## **What do these scripts do ?**

Each of these scripts is named according to what it does on the target machine. <br>
>   **E.g.** The `/payloads/linux/HelloWorld.txt` script will open up a new terminal instance and echo **"Hello World!"** on most linux machines.

<br>



## **How do I make these scripts work ?**
Just copy and adapt the scripts you need, or just download the files and do whatever you want with them.

Some scripts will need to be modified according to your needs. <br>
>   **E.g.** In the following snippet :
>   ```
>   ...
>   REM     ###     Launching the URL in Firefox
>   STRING firefox <URL HERE>
>   DELAY 200
>   ENTER
>   ...
>   ```
>   Just replace the `<URL HERE>` tag with the URL you wish to launch inside of firefox.<br>
> For example, **the following script :**
> ```
> ...
> REM       ###     Launching the URL in Firefox
> STRING firefox https://www.google.com/
> DELAY 200
> ENTER
> ...
> ```
> Will **open up google.com in a new instance of Firefox.**

<br>


### **Disclaimer**
I am not responsible of what you do with these scripts. You are the one responsible of your own actions.
Should you do anything illegal with any one (or part) of these scripts, you would be the only one responsible.

<br>



Written and compiled by **benur**.
