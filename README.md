# Realtek-RTL8812AU
<h1>Full Process to install RTL8812AU chipset</h1>

<h2>Dependencies Commands✨</h2>
<p>wget https://kali.download/kali/pool/main/l/linux/linux-headers-6.6.15-common_6.6.15-2kali1_all.deb<p>
<p>wget https://kali.download/kali/pool/main/l/linux/linux-kbuild-6.6.15_6.6.15-2kali1+b1_amd64.deb</p>
<p>wget https://kali.download/kali/pool/main/l/linux/linux-headers-6.6.15-amd64_6.6.15-2kali1+b1_amd64.deb</p>
<br>

<h3>Install 😉</h3>
<p>sudo apt update</p>
<p>apt-cache search linux-headers-$(uname -r | sed 's/-.*//')</p>
<p>sudo apt-get install linux-image-amd64</p>
<p>sudo apt-get install linux-headers-$(uname -r)</p>
<p>sudo apt install -f</p>
<p>sudo apt install bc</p>
<p>sudo apt install realtek-rtl88xxau-dkms </p>

<h2>If you get any error</h2>
<p>sudo dpkg --remove linux-headers-6.6.15-amd64 </p>
<p>apt --fix-broken install</p>
<p>sudo apt remove realtek-rtl88xxau-dkms</p>
