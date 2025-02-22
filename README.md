Fluxion is the future of MITM WPA attacks

Fluxion is a security auditing and social-engineering research tool. It is a remake of linset by vk496 with (hopefully) fewer bugs and more functionality. The script attempts to retrieve the WPA/WPA2 key from a target access point by means of a social engineering (phishing) attack. It's compatible with the latest release of Kali (rolling). Fluxion's attacks' setup is mostly manual, but experimental auto-mode handles some of the attacks' setup parameters. Read the FAQ before requesting issues.

If you need quick help, fluxion is also available on gitter. You can talk with us on Gitter or on Discord.
Installation

Read here before you do the following steps.
Download the latest revision

git clone git@github.com:FluxionNetwork/fluxion.git

# Or if you prefer https 

git clone https://www.github.com/FluxionNetwork/fluxion.git

Switch to tool's directory

cd fluxion 

Run fluxion (missing dependencies will be auto-installed)

./fluxion.sh
