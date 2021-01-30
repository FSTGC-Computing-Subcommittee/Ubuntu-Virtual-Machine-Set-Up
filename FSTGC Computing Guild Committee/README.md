# Foreword on Alternatives

Please note that depending on your computer's RAM and processor, running a virtual machine may be too difficult for it and dual booting or WSL(Windows Subsystem for Linux) would be a better option. (I personally wouldn't recommend trying to run a virtual machine if you have less than 8GB of RAM, especially if you are a Windows user).

# Prequisites

- VirtualBox
- An Ubuntu iso file
- about 10GB of free space at minimum



## Install VirtualBox

Download and install VirtualBox:

https://www.virtualbox.org/wiki/Downloads

## Download an Ubuntu ISO file.

You can download the iso file here. It's around 2GB.
https://ubuntu.com/download/desktop

If you prefer, you can get the torrent for the iso from alternative downloads:
https://ubuntu.com/download/alternative-downloads

If you feel like trying one of the flavours, you can download them here.
https://ubuntu.com/download/flavours
The process is pretty much the same but for the purposes of this guide, We'll be using plain Ubuntu.

# Setting up the Virtual Machine

1. Open VirtualBox. (Yours will probably look different from mine because of theming)
![228e405e83605a5c3f74b1ccc4c9c58f.png](../_resources/91703358587d435d958bf23d83d5daae.png)
3. Click `New`
![3ab482b5aa95221cb6304902466e2eb4.png](../_resources/89b7e77962c74d4d83a452e85e77a671.png)
Give the Virtual Machine a name (I just called it Ubuntu) and the other settings you see there were defaults. Just double check that the `Type` is Linux and version is Ubuntu (64-bit).
5. Set the amount of RAM
![860d01996bff473e71a5bf2142d78693.png](../_resources/302e6774c7c2484284fa15c1894395dc.png)
Be mindful of how much RAM you give the Virtual Machine. Follow the guide underneath the slider and you should be fine (i.e. keep within the green region).
1. Set Storage
![790fe51446725a3a43ac3269f02e55ab.png](../_resources/08917a82b45d46cb98f6dadf80182a79.png)
Make sure `Create a virtual hard disk now` is selected...
![67d31ad606cfe604eed3e2ae47ea1510.png](../_resources/39c1cf74bce94859b7c0781cbe5f0a0f.png)
and `VDI(VirtualBox Disk Image)` is selected...
![fd91a079642fed2c7f397260e38ab2f3.png](../_resources/4d96e4ea89c742fcb2459507dc93daff.png)
and that it is set to dynamically allocated to allow the storage size to increase as you use it up.
1. Press Create!

# Add the ISO

You should now see the Virtual Machine in the list on the left.
![ee694258535c1a649c1376b6fa9886ef.png](../_resources/405a06a019d54bbeae7467e216178cf9.png)

Select it and then select settings.
![2340ed6314184aeb552e33867d333859.png](../_resources/b655edca0dcd411f8c48e410c6e535fb.png)

Go to storage, under settings:
![584d82c4aff554161e4cb4344e62e820.png](../_resources/4bbb403c3bc04ca385058fc82d7810e8.png)

![aa1d20cfa44fcecdbaf7fa154a767c02.png](../_resources/0ffbc504e80f4f87b96cb8e2b04021cf.png)

![8b1b84d9db83a4a09d255ca0c7d2b77c.png](../_resources/efc5fb50e60c419bac9aa7ad5fa660c7.png)

Select empty and then choose disk file from the CD icon. Find the location of the iso file you downloaded and select it. It should now appear instead of empty:

![c8a5e05c4f85620818b5aeb78b105100.png](../_resources/1596dc6fce1e4b27a136af8467a529d0.png)

Press Ok and then start the Virtual Machine.

![c8544eff9de4f1d0e3ed355118d92a2a.png](../_resources/e488551e21714d6fb12b520a7446cc51.png)
# Install Ubuntu

_After you start the Virtual Machine you may see another window asking you to reselect the iso. You can select it and press okay._

You will see something like this:
![8f7c8d24009f3272ee1c74435bb0d1c8.png](../_resources/45ed9f53bbc9442384742138eecaea28.png)

The next part can take a while to come up:
![0de9c4c6a932edae0321e39701ebeb06.png](../_resources/1f1f99d2042648f5b854dccc5e52ac5d.png)

Choose Install.

![02f1afc4023574a79b2a19f8400cce62.png](../_resources/6480b713b5014e339d2cc415e03c4d73.png)

Choose Continue

![8e0b84eb54bc0a649d041634fd381603.png](../_resources/0bb275c26d3c47cb950bcb6535434cf3.png)

Ensure the above options are selected and choose continue.

![c2cdb0ef1154a1d3f5ba6423422531fa.png](../_resources/b0779ab04fcc4877bc672d83a021ca5c.png)

You can continue with Erase disk and install Ubuntu since only the virtual hard disk will be affected.

![336d0f2f8efce455898f724a319fbbd0.png](../_resources/4d178fd45c2244f8816a7e8939cc197f.png)

and continue.

![b91ef19c6ac36b4fbadfa188c77197b9.png](../_resources/2294f42f40e34e6990f5f5ca7aaa38aa.png)

Ensure the correction location is selected and continue.

![36e3660760d0b78e9a265ea935373f58.png](../_resources/6b6a338453ae4e97a07d716fd68e3480.png)
Create your account...

...and wait for installation to finish. 
![6ea01b3f6ce49bd717d77a1935e773ea.png](../_resources/6f1fc50f243249aba90bc37ce53114b0.png)


![ce4783a55023a3e72f15905c6b095289.png](../_resources/c179ed204daa429ba6fe6d660e84babb.png)

# Finishing Up

Shut down the Virtual Machine.

Ensure that the iso is removed and it goes back to empty.
![5a610635e73531db519df695438473c7.png](../_resources/44839362a62247a3b4d098fb4a956fd9.png)

Then restart and login 
 ![a9fb278950be12c472875fc2c6db72b4.png](../_resources/2cfa2f5a2aca406482624f25c0380fc7.png)
