SANS SEC555 Wiki
==================

---

Welcome to the SANS SEC555 Wiki
----------


![Cyber Defense](CyberDefense_logo.jpg)
### **`SEC555 Portal Version: 1.0.0`**
### **`Course Version C01_02`**

---

The goal of the SEC555 wiki is to increase the **in-class**, and, most importantly, **after-class** value of the course material. This wiki is, and likely always will be, very much a work in progress.

Contained in the wiki, you will find:
- Electronic Copies of the Lab Guides (**copy and paste, FTW!!!**) (**Digital labs are only available on student VM**)
- Tool and technique cheat sheets
...and more

Note: If you are using the student VM included when taking SEC555 you have the capability of turning on automatic wiki/lab updating.

In order to enable automatic wiki/lab updating run the following command:

```bash
sudo crontab -e
```

Then uncomment the cron job for either the 9 AM automatic update or the update after reboot (or both):

```bash
# Uncomment the below entry to automatically update the SEC555
# wiki. The default check occurs at 9 AM but can be changed.
#0 9 * * * powershell -file /home/student/wiki_update.ps1

# Uncomment the below entry to automatically update the SEC555
# wiki after each reboot.
#@reboot powershell -file /home/student/wiki_update.ps1
```

When finished the cron entry should look similar to this:

```bash
# Uncomment the below entry to automatically update the SEC555
# wiki. The default check occurs at 9 AM but can be changed.
0 9 * * * powershell -file /home/student/wiki_update.ps1

# Uncomment the below entry to automatically update the SEC555
# wiki after each reboot.
@reboot powershell -file /home/student/wiki_update.ps1
```

---


Course/Lab/Wiki Bugs or Suggestions
----------

---

Please let us know if you find any bugs in the courseware/labs/wiki we need to squash. Also, reach out if you have suggestions to improve the course (e.g. content/labs/tools that should be added, removed, or updated). The easiest way to submit these improvements is by sending an email to **<justin@hasecuritysolutions.com>**

---

Alumni Mailing List
----------

---

Join the 555 alumni mailing list:

[http://sec555.com/555group](http://sec555.com/555group)

---
