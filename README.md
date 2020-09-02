# Unrestricted File Upload on SiteMagic CMS 4.4.2

This repo describe how to exploit unrestricted file upload vulnerability on SiteMagic CMS 4.4.2

________________________________________________________________________________________________

## About SiteMagic CMS 4.4.2

Website: https://sitemagic.org/
Download: https://sitemagic.org/Download.html

________________________________________________________________________________________________

## PoC - Exploiting unrestricted file upload vulnerability on SiteMagic CMS 4.4.2

The FrmUpload.class.php doesn't handle the file types that can be uploaded to the website, allowing the upload of application/x-php files such as ".php"


![01](http://sejalivre.org/poc4/1.png)




http://sejalivre.org/sitemagic/files/images/info.php
