# Resolving-DefaultUser0-Error

`DefaultUser0` is a bug found in Windows where this "user" does not have a valid profile. This is a temporary account that Windows creates when an existing user account is not detected.

A screenshot of the error:
![1 Showing error](https://github.com/johnnyh209/Resolving-DefaultUser0-Error/assets/33064730/cce162be-b14e-476c-9810-367bef7f009a)

**Step 1**<br>
On the login page of Windows, hold `shift` and click on the power button located on the bottom right corner of the screen. While still holding `shift`, click on `restart`. This should open up a blue menu screen. 
![2 Hold shift, click on power and then click on restart](https://github.com/johnnyh209/Resolving-DefaultUser0-Error/assets/33064730/191eb36f-6650-49b4-89f0-decb71c1ddba)

**Step 2**<br>
On the first page of the blue menu screen, click on `Troubleshoot`.
![3 Click troubleshoot](https://github.com/johnnyh209/Resolving-DefaultUser0-Error/assets/33064730/b43f9128-c4ff-4437-a282-0d0ff77402f8)

**Step 3**<br>
You will be presented with two options in the troubleshooting page. Click on `Reset this PC`.
![4 Reset this pc](https://github.com/johnnyh209/Resolving-DefaultUser0-Error/assets/33064730/82ec3126-af19-439d-a025-377aa877695a)

**Step 4**<br>
You will be presented with two options. If you have important files, but do not have a back up or that you want to keep all of your files, choose `Keep my files`. Otherwise, choose `Remove everything`. I chose remove everything since I encountered this error on a fresh installation of Windows, and thus I do not have any important files.
![5 Choose either depending on your situation](https://github.com/johnnyh209/Resolving-DefaultUser0-Error/assets/33064730/ded3ecd6-4fa8-4ba6-be3c-106e5e01ae5d)

**Step 5**<br>
You are presented with two options again. It does not matter which option you choose (unless you have a metered connection). `Cloud download` will install Windows through the Internet. `Local reinstall` will use the bootable media you inserted into your computer. I chose `Local reinstall`.
![6 local reinstall](https://github.com/johnnyh209/Resolving-DefaultUser0-Error/assets/33064730/0896af27-5de5-479b-9c3d-98a05fd36a08)

After, your computer should start the process automatically.
![7](https://github.com/johnnyh209/Resolving-DefaultUser0-Error/assets/33064730/6f5ca82f-2c0a-497e-b929-e203401e206c)

**Step 6**<br>
You are once again presented with two options. Choose `Just removed my files` since you will most likely be keeping the computer. 
![8 Just remove my files](https://github.com/johnnyh209/Resolving-DefaultUser0-Error/assets/33064730/1a46a1e0-c9cd-4ded-8d62-3a72a8f141dd)

**Step 7**<br>
You are asked to confirm that you want to reset the computer. Click on `reset`.
![9 Click reset](https://github.com/johnnyh209/Resolving-DefaultUser0-Error/assets/33064730/2649e518-0f02-44ff-b77e-44cc226bcbdf)
![VirtualBoxVM_TRRahbqnPB](https://github.com/johnnyh209/Resolving-DefaultUser0-Error/assets/33064730/8ce15a24-0926-42f9-aa1d-c1dc552363c6)

**Step 8**<br>
Once the reset is complete, you should be brought back to the beginning of the Windows configuration, the region selection page. Go through all of the configurations, and you should be able to boot into Windows with a valid user account.
![VirtualBoxVM_hUtSHaVNMy](https://github.com/johnnyh209/Resolving-DefaultUser0-Error/assets/33064730/08063478-a8ee-49c1-b547-214270bcf6ea)

