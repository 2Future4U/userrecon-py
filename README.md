## userrecon-py
Find usernames in **187** social networks.

<p align="center">
    <img alt="userrecon-py" src="https://i.imgur.com/6ms6lIe.gif"/>
    <p align="center">
        <a href="https://github.com/decoxviii/userrecon-py/releases/latest"><img alt="Release" src="https://img.shields.io/github/tag/decoxviii/userrecon-py.svg"></a>
        <a href="https://github.com/decoxviii/userrecon-py/blob/master/LICENSE"><img alt="Software License" src="https://img.shields.io/badge/license-MIT-brightgreen.svg"></a>
         <a href="https://twitter.com/decoxviii"><img alt="Twitter" src="https://img.shields.io/badge/twitter-@decoxviii-blue.svg"></a>
    </p>
</p>

---

#### Installation

1. Install dependencies (Debian/Ubuntu):
```
sudo apt install python3 python3-pip
```

2. Install with `pip3`:
```
sudo -H pip3 install git+https://github.com/decoxviii/userrecon-py.git
userrecon-py --help
```

---

#### Building from Source

Clone this repository, and:
```
git clone https://github.com/decoxviii/userrecon-py.git ; cd userrecon-py
sudo -H pip3 install -r requirements.txt
python3 setup.py build
sudo python3 setup.py install
```

---

#### Update

To update this tool to the latest version, run:
```
sudo -H pip3 install git+https://github.com/decoxviii/userrecon-py.git --upgrade
userrecon-py --version
```

---

#### Usage
Start by printing the available actions by running `userrecon-py --help`. Then you can perform the following tests:

```
userrecon-py --target decoxviii -o test_one
```

---

#### Thanks

This program is possible thanks to:

+ [userrecon](https://github.com/thelinuxchoice/userrecon)
+ [WhatsMyName](https://github.com/WebBreacher/WhatsMyName)

---

**decoxviii**

**[MIT](https://github.com/decoxviii/userrecon-py/blob/master/LICENSE)**

