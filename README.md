## Public_Link
is a simple **Bash-based automation tool** that:

- Creates a **public tunnel** using `localhost.run`.
- **Shortens URLs** automatically
- **Masks URLs** to make them appear as trusted domains for **social engineering demos**

## 🔹 Features

- Public tunnel creation using **localhost.run**
- Automatic **short URL generation** via APIs (TinyURL, is.gd)
- **Masked URL format**: `https://facebook.com-video@is.gd/xyz123`
- Lightweight and works on:
- Built-in cleanup and error handling

## Tested On :
* Kali Linux 
* BlackArch Linux 
* Ubuntu 
* Fedora 
* Kali Nethunter 
* Termux 
* Parrot OS 

## 🛠 Installation
Just Copy Paste this command in your terminal.


```
git clone https://github.com/YOUR_GITHUB_USERNAME/Public_Link.git
cd Public_Link
chmod +x public
sudo mv public /usr/bin/
rm -rf Public_Link
```

## ▶️ Run
Now run this Command.
```
public
```


## Example Workflow
```
====== SSH Tunnel + MaskPhish Automation ======
Enter local port to expose (e.g. 8080): 8080
[*] Starting tunnel on port 8080... Please wait...
[+] Public tunnel URL: https://random123.lhr.life

Do you want to shorten this URL before masking? (y/n): y
[+] Shortened URL: https://tinyurl.com/abcd123

Do you want to mask the URL? (y/n): y
Choose protocol:
1) http
2) https
Enter choice [1-2]: 2

Choose masking domain:
1) Facebook
2) YouTube
3) Instagram
4) Twitter
5) Custom domain
Enter choice [1-5]: 1

Enter social engineering words (e.g. free-gift): free-gift

✅ Masked Phishing URL:
https://facebook.com-free-gift@tinyurl.com/abcd123
```



# Disclaimer


> ⚠️ **Educational Purpose Only:**  
> This tool demonstrates how attackers hide phishing URLs.  
> Misuse for illegal activity is **strictly prohibited**.
The author is not responsible for any misuse or damage caused.
---

