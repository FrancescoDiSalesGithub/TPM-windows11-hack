# TPM-windows11-hack
TPM bypass for windows 11 virtualbox images

# How to use

Download the the tpm-windows11-hack iso at this URL: https://github.com/FrancescoDiSalesGithub/TPM-windows11-hack/releases/tag/tpm1.0

Start virtualbox and create a new machine choosing windows 10 x64. After that, go to settings and attach the tpm-windows11-hack iso  by doing:

* Storage -> Controller:SATA -> Adds optical drive (the icon that looks like a cd-rom)

Then do the same with the windows 11 installation iso.

Other settings for your VM:

 * System: Enable EFI; Processors >= 2

Run you VM.

At the boot you should press a key to go to the windows installation screen. When you reach the installation screen press **shift** and **F10**. As soon as you press this key combination, a terminal should appear. Now you should check the disk where there's the tpm bypass. 

```
D:\
dir 

E:\
dir 

```

when you run the command **dir** you should be able to see this file: **tpmpwn.bat**
If so run the script by doing:

`tpmpwn.bat`

Wait for the correct run of the script and then close the terminal. Now continue the installation and you should be able to bypass the tpm block and start to test your windows 11 virtual machine.

# Donation

If you want to support me donate monero coins at: 4B9WQivaHfd3miDfPKEfCianocGpBx9d8FXycz2vmNW3aBDVKHgkBd9Gmapt4RBVEpTwnehujsiUBBehUiLvnEHs7VFstCC

# Sponsor

Exciting News: Introducing Hack The Box Academy! lock

fire Calling all cybersecurity enthusiasts and aspiring hackers! fire

I'm thrilled to announce an incredible opportunity for you to take your skills to the next level. Today, I proudly sponsor Hack The Box Academy, an innovative online platform dedicated to cybersecurity education and practical training.

Hack The Box Academy has earned a stellar reputation for its cutting-edge approach to teaching real-world hacking techniques and cybersecurity principles. With a mission to empower individuals with the knowledge and skills necessary to succeed in the ever-evolving world of cybersecurity, this platform is an absolute game-changer.

Start now: https://referral.hackthebox.com/mzwyliz
