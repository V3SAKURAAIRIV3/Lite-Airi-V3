Debian 10 Only

<pre><code>apt update -y && apt upgrade -y && apt dist-upgrade -y && reboot
</code></pre>


Ubuntu 20.04 

<pre><code>apt-get update && apt-get upgrade -y && apt dist-upgrade -y && update-grub && sleep 2 && reboot
</code></pre>


Install Full

<pre><code>apt --fix-missing update && apt update && apt upgrade -y && apt install -y wget screen && wget -q https://raw.githubusercontent.com/V3SAKURAAIRIV3/Lite-Airi-V3/main/setup.sh && chmod +x setup.sh && screen -S setup ./setup.sh
</code></pre>
