HackSys Extreme Vulnerable Driver
=================================

               ooooo   ooooo oooooooooooo oooooo     oooo oooooooooo.   
               `888'   `888' `888'     `8  `888.     .8'  `888'   `Y8b  
                888     888   888           `888.   .8'    888      888 
                888ooooo888   888oooo8       `888. .8'     888      888 
                888     888   888    "        `888.8'      888      888 
                888     888   888       o      `888'       888     d88' 
               o888o   o888o o888ooooood8       `8'       o888bood8P'   

------------------------------------------------------------------------

**HackSys Extreme Vulnerable Driver** is **intentionally** vulnerable **Windows** driver developed for security enthusiasts to learn and polish their exploitation skills at **Kernel** level. 

**HackSys Extreme Vulnerable Driver** caters wide range of vulnerabilities ranging from simple `Buffer Overflows` to complex `Use After Frees` and `Pool Overflows`. This allows the researchers to explore the exploitation techniques for every implemented vulnerabilities.


Blog Post
---------
[http://www.payatu.com/hacksys-extreme-vulnerable-driver/](http://www.payatu.com/hacksys-extreme-vulnerable-driver/)


Author
------

> **Ashfaq Ansari**

> ashfaq[at]payatu[dot]com

> **[@HackSysTeam](https://twitter.com/HackSysTeam) | [Blog](http://hacksys.vfreaks.com/ "HackSys Team") | [null](http://null.co.in/profile/411-ashfaq-ansari)**

> ![Payatu Technologies](http://www.payatu.com/wp-content/uploads/2015/04/Payatu_Logo.png "Payatu Technologies Pvt. Ltd.")

> [http://www.payatu.com/](http://www.payatu.com/wp-content/uploads/2015/04/Payatu_Logo.png "Payatu Technologies Pvt. Ltd.")


Screenshots
-----------

![Driver Banner](http://www.payatu.com/wp-content/uploads/2015/05/2015-05-27_20h14_33.png "Driver Banner")

![Help](http://www.payatu.com/wp-content/uploads/2015/05/2015-06-03_22h27_24.png "Help")

![Exploitation](http://www.payatu.com/wp-content/uploads/2015/05/2015-05-27_20h22_35.png "Exploitation")

![Driver Debug Print](http://www.payatu.com/wp-content/uploads/2015/05/2015-05-27_20h28_07.png "Driver Debug Print")


Vulnerabilities Implemented
---------------------------

* **Pool Overflow**
* **Use After Free**
* **Type Confusion**
* **Stack Overflow**
* **Integer Overflow**
* **Stack Overflow GS**
* **Arbitrary Overwrite**
* **Uninitialized Variable**
* **Null Pointer Dereference** 


Building Driver
---------------

1. [Install Windows Driver Kit](https://www.microsoft.com/en-in/download/details.aspx?id=11800)
2. Change `%localSymbolServerPath%` in `Build_HEVD_Secure.bat` and `Build_HEVD_Vulnerable.bat` driver builder
3. Run the appropriate driver builder `Build_HEVD_Secure.bat` or `Build_HEVD_Vulnerable.bat`


Installing Driver
-----------------

Use [**OSR Driver Loader**](https://www.osronline.com/article.cfm?article=157) to install **HackSys Extreme Vulnerable Driver**


Testing
-------

The **HackSys Extreme Vulnerable Driver** and the respective exploits have been tested on **Windows 7 SP1 x86** 

Presentations
-------------

Presentation will be uploaded `soon`.


Sessions Conducted
------------------

* [Windows Kernel Exploitation 1](http://null.co.in/event_sessions/156-windows-kernel-exploitation)
* [Windows Kernel Exploitation 2](http://null.co.in/event_sessions/186-windows-kernel-exploitation-2)
* [Windows Kernel Exploitation 3](http://null.co.in/event_sessions/226-windows-kernel-exploitation-3)
* [Windows Kernel Exploitation 4](http://null.co.in/event_sessions/234-windows-kernel-exploitation-4)
* [Windows Kernel Exploitation 5](http://null.co.in/event_sessions/309-windows-kernel-exploitation-5)
* [Windows Kernel Exploitation 6](https://null.co.in/event_sessions/482-windows-kernel-exploitation-6)


Workshops Conducted
-------------------

* [Windows Kernel Exploitation Humla Pune](http://null.co.in/event_sessions/280-windows-kernel-exploitation)
* [Windows Kernel Exploitation Humla Mumbai](http://null.co.in/event_sessions/327-windows-kernel-exploitation)


TODO
----

1. Test the Driver on Windows 10 x64
2. Add the exploit support for Windows 10 x64
3. Add `Memory Disclosure` Vulnerability
4. Add `Time-Of-Check-To-Time-Of-Use` (**TOCTOU/Race Condition**) Vulnerability
5. Refactor and clean-up the driver and exploit source code


License
-------

Please see the file `LICENSE` for copying permission


Contribution Guidelines
-----------------------

Please see the file `CONTRIBUTING.md` for contribution guidelines


Bug Report
----------

Please file any bug report via GitHub Issue Tracker at the below given address: [https://github.com/hacksysteam/HackSysExtremeVulnerableDriver/issues](https://github.com/hacksysteam/HackSysExtremeVulnerableDriver/issues)

------------------------------------------------------------------------

[http://hacksys.vfreaks.com](http://hacksys.vfreaks.com)

![HackSys Team](http://hacksys.vfreaks.com/wp-content/themes/Polished/images/logo.png)

