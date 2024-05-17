# ZeroDoS

## Introduction

ZeroDoS is a powerful Denial-of-Service (DoS) tool written in C++. It introduces multithreading and customization options, making it a more efficient and versatile tool for conducting DoS attacks.

## Installation
```bash
Linux
sudo apt install gcc g++ -y
git clone https://github.com/Mr-Pstar7/ZeroDos
cd ZeroDos
g++ ZeroDoS.cxx -o zerodos
./zerodos www.example.com 80 1000 200

Termux:
pkg install gcc g++ -y
git clone https://github.com/Mr-Pstar7/ZeroDos
cd ZeroDos
g++ ZeroDoS.cxx -o zerodos
./zerodos www.example.com 80 1000 200
```
## Features
* **Multithreading:** ZeroDoS utilizes multiple threads to establish connections, significantly improving the speed and efficiency of the attack.
* **Customization:** With this tools, you have control over various parameters to tailor the attack according to your needs:
    * **Target:** The IP address or hostname of the target.
    * **Port:** The target port number.
    * **Max_socks:** The maximum number of sockets to open.
    * **Threads:** The number of threads to use.
    * **Min_delay:** [Optional] The minimum delay between each character (default:5ms).
    * **Max_delay:** [Optional] The maximum delay between each character (default:10ms).
    * **Delay_keep_alive:** [Optional] The delay between sending Keep-Alive headers (default:1 second).
    * **Delay_print_details:** [Optional] The delay for printing attack details (default:10 seconds).
* **Random User-Agent:** Each request sent by ZeroDoS includes a randomly generated User-Agent header, making it more challenging to detect and mitigate the attack.
* **Proxies (Coming Soon):** In future updates, ZeroDoS will include a proxy feature, allowing you to use multiple proxies simultaneously, further enhancing anonymity and making detection even harder.

## Usage

To use ZeroDoS, follow the instructions below:

```bash
Usage: ./zerodos target port max_socks threads
Example : ./zerodos www.example.com 80 1000 15

Options:
  -h, --help            Show help message and exit

Input Information:
  target        : The target IP address or hostname
  port          : The target port number
  max_socks     : The maximum number of sockets to open
  threads       : The number of threads to use
  min_delay     : [Optional] The minimum delay between each character (default:5ms)
  max_delay     : [Optional] The maximum delay between each character (default:10ms)
  delay_keep_alive : [Optional] The delay between sending Keep-Alive headers (default:1 second)
  delay_print_details : [Optional] The delay for printing attack details (default:10 seconds)



## Disclaimer

Please note that the use of ZeroDoS or any other DoS tool for malicious purposes is strictly prohibited. This tool is intended for educational and testing purposes only. The author and contributors are not responsible for any misuse or damage caused by this tool.

## Get Involved

If you are interested in contributing to ZeroDoS or have any suggestions, feel free to reach out. Together, let's make it an even more powerful tool!

## MY SOCIAL MEDIA
<p align="left">
<a href="https://wa.me/+6285728337030?text=Assalamualaikum+Warahmatullahi+wabarakatuh" target="blank"><img align="center" src="https://github.com/rahuldkjain/github-profile-readme-generator/blob/master/src/images/icons/Social/whatsapp.svg" alt="Mr. Pstar7" height="30" width="40" /></a>
<a href="https://www.facebook.com/profile.php?id=100089457192279" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/facebook.svg" alt="Mr. PSTAR7" height="30" width="40" /></a>
<a href="https://www.instagram.com/pstar7.dev?igsh=MXQxczFlb2FmMXV5cA==" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="Mr. Pstar7" height="30" width="40" /></a>
<a href="https://www.youtube.com/@Mr_Pstar7" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/youtube.svg" alt="Mr. Pstar7" height="30" width="40" /></a>
<a href="https://www.github.com/Mr-Pstar7/" target="blank"><img align="center" src="https://cdn-icons-png.flaticon.com/512/25/25231.png" alt="Mr. Pstar7" height="30" width="30" /></a>
<a href="https://t.me/@Mr_Pstar7" target="blank"><img align="center" src="https://github.com/gauravghongde/social-icons/blob/master/SVG/Color/Telegram.svg" alt="Mr. Pstar7" height="30" width="40" /></a>
<a href="tiktok.com/@pstar7.py" target="blank"><img align="center" src="https://github.com/gauravghongde/social-icons/blob/master/SVG/Color/Tik%20Tok.svg" alt="Mr. Pstar7 height="30" width="40" /></a>
</p>



🌟 Star the project and show your support!
