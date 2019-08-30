# <img src="https://ee5817f8e2e9a2e34042-3365e7f0719651e5b8d0979bce83c558.ssl.cf5.rackcdn.com/python.png" width="48"><img src="https://sucuri.net/images/icons/features/large/malware-detection-website-icon-large.png" width="48">web-application-security-scanner

This program was originally developed using python 2.7 and now upgraded to run on Python 3.x. It makes use of  VirusTotal api v2 to scan urls and get report.


**Program Requirements:**

- Python 3.7.4 [Download link](https://www.python.org/ftp/python/3.7.4/python-3.7.4.exe)
- VirusTotal api [How to obtain API?](https://www.virustotal.com/en/documentation/public-api/)


**How to use?**

Windows:

1. [Download](https://github.com/ComputerMaverick69/web-application-security-scanner/archive/master.zip) & Extract the zipped files.
2. Edit `scan.py` file using any code editor.
3. Update the Api_key to your virustotal api key:
```
Api_Key = "xxxxxxxxxxxxxxxxxxxxxxx"
```
4. Run the program by double click in `scan.py` file.
5. Program window open. Now type the number from the menu and ENJOY..

Linux:

Open new terminal and type this command:

1- Install `Git` & if `git` is aleardy installed, please skip this step.
```
apt-get install git
```
2- Install web-application-security-scanner program and run:
```
git https://github.com/ComputerMaverick69/web-application-security-scanner.git
cp web-application-security-scanner/scan.py ~
```
3- Edit `scan.py` and add your virustotal api:
```
vi scan.py
```
or
```
nano scan.py
```
4- Run `scan.py` file and Enjoy..
```
python scan.py
```

**Output:**

<img src="http://s16.postimg.org/a21wio3k5/Untitled_1.jpg" width="600">

**Have a problem?**

Please open new issue or contact with me via Twitter [@codemaverick69](http://www.twitter.com/codemaverick69)

**License:**

As of August 29, 2019 web-application-security-scanner is licensed under the GPLv3+: http://choosealicense.com/licenses/gpl-3.0
