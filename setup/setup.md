# Set-up Steps

## Step 1 : Downloading the P4Pi image

The P4Pi image is downloaded from the from the official repo in github.

[Click here](https://github.com/p4lang/p4pi/releases/tag/sigcomm2022) to **Download** the image (download the image with the name looking like "p4pi...lite.zip")
</br>
</br>

---

## Step 2 : Unzip the image

Use the following command to unzip the file:\
`unzip p4pi-image-<version>.zip`
</br>

If the file is tar then use the command to untar
`tar xf p4pi-image-<version>.tar.xz`
</br>
</br>

---

## Step 3 : Use the Raspberry Pi imager

</br>

Install and run the Raspberry Pi imager [ available here](https://www.raspberrypi.com/software/) or [here](https://github.com/raspberrypi/rpi-imager/releases)
</br>
</br>

If you are using a new microSD card, first format your microSD as follows:

a. Under Operating System select Erase

b. Under Storage select your microSD

c. Select Write, and wait for the process to complete

</br>
</br>

Then install on the microSD card the downloaded P4Pi image as follows:

a. Under _Operating System_, select _Use custom_, and point to the P4Pi image file

b. Under _Storage_ select your _microSD_ card
c. Select _Write_, and wait for the process to complete
</br>
</br>

---

## Step 4 : Connecting and running sample program

Connect with the hotspot of the Raspberry Pi

Then connect with the web interface of P4Pi use the url `http://192.168.4.1` and use the default user `pi` with the password `raspberry` to access the console.

Now there are some given sample programs inside like switch , reflector, run one of them and use the `tcpdump` or `ping` command to check whether it was running perfectly or not.
