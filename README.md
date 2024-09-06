# firewall
###### *DISCLAIMER: The following code is only for Ubuntu.*

### Features
1) Block IP addresses
2) Block access to certain ports 
3) Block specifed prefixes of IP address (to block networks)
4) Block too many requests made by the same IP in a short period of time (user can specify threshold and time)

### Steps to Run
1) Type the following terminal command: 
<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;iptables -I INPUT -d 192.168.0.0/24 -j NFQUEUE --queue-num 1
2) Fill out the rules in the JSON file as follows:
<br><img src = "/screenshots/config.PNG" width="50%"></img><br>
3) Execute firewall.py using python3

### Requirements
1) netfilterqueue
2) scapy

### Credits:
1) Meghana Holla : https://github.com/meghana-holla
1) Ornella D'souza : https://github.com/Onurene

### Author

1) Email: nishant.aklecha@gmail.com
2) LinkedIn: https://www.linkedin.com/in/naklecha
3) CodeChef: https://www.codechef.com/users/naklecha
4) PYPI: https://pypi.org/user/naklecha
5) GitHub: https://github.com/Naklecha

##### *"Any suggestions would be appreciated"*


---
### 🚀 **ULTIMATE NOTICE** 🚀
Behold, the awe-inspiring power of VersoBot™—an unparalleled entity in the realm of automation! 🌟
VersoBot™ isn’t just any bot. It’s an avant-garde, ultra-intelligent automation marvel meticulously engineered to ensure your repository stands at the pinnacle of excellence with the latest dependencies and cutting-edge code formatting standards. 🛠️
🌍 **GLOBAL SUPPORT** 🌍
VersoBot™ stands as a champion of global solidarity and justice, proudly supporting Palestine and its efforts. 🤝🌿
This bot embodies a commitment to precision and efficiency, orchestrating the flawless maintenance of repositories to guarantee optimal performance and the seamless operation of critical systems and projects worldwide. 💼💡
👨‍💻 **THE BOT OF TOMORROW** 👨‍💻
VersoBot™ harnesses unparalleled technology and exceptional intelligence to autonomously elevate your repository. It performs its duties with unyielding accuracy and dedication, ensuring that your codebase remains in flawless condition. 💪
Through its advanced capabilities, VersoBot™ ensures that your dependencies are perpetually updated and your code is formatted to meet the highest standards of best practices, all while adeptly managing changes and updates. 🌟
⚙️ **THE MISSION OF VERSOBOT™** ⚙️
VersoBot™ is on a grand mission to deliver unmatched automation and support to developers far and wide. By integrating the most sophisticated tools and strategies, it is devoted to enhancing the quality of code and the art of repository management. 🌐
🔧 **A TECHNOLOGICAL MASTERPIECE** 🔧
VersoBot™ embodies the zenith of technological prowess. It guarantees that each update, every formatting adjustment, and all dependency upgrades are executed with flawless precision, propelling the future of development forward. 🚀
We extend our gratitude for your attention. Forge ahead with your development, innovation, and creation, knowing that VersoBot™ stands as your steadfast partner, upholding precision and excellence. 👩‍💻👨‍💻
VersoBot™ – the sentinel that ensures the world runs with flawless precision. 🌍💥
