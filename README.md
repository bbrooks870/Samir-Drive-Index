# Google Personal/Shared Drive Index

* Supports Both My and Team/Shared Drives.
* Code that should be deployed is [here](https://github.com/SamirJanaOfficial/Shinobi-Drive-Index/blob/master/worker/dist/goindex.js)

## Demo Sites

* [Demo-Light](https://https://demo-light.shinobicloud.workers.dev/0:/)
* [Demo-Dark](https://demo-dark.shinobicloud.workers.dev/0:/)

## Screenshots
[![Screenshot](https://raw.githubusercontent.com/SamirJanaOfficial/Samir-Drive-Index/master/images/light-screenshot2.png)](https://github.com/SamirJanaOfficial/Samir-Drive-Index)

[![Screenshot](https://raw.githubusercontent.com/SamirJanaOfficial/Samir-Drive-Index/master/images/Demo-Dark2.PNG)](https://github.com/SamirJanaOfficial/Samir-Drive-Index)

## How to

* Open https://gdindex-code-builder.maple3142.net/ and Get Your Authorize Code And change in [Worker Line 6,7 & 8 Respectively](https://github.com/SamirJanaOfficial/Samir-Drive-Index/blob/master/worker/dark-theme.js)
* Demo is at [Jana Cloud](https://janacloud.ga)
* If you want to deploy main drive leave the option ROOT as it is.
* If you want to deploy your Team Drive/Shared Drive/Folder then copy the ID and replace it with ROOT.
* Eg. if you open [this shared drive](https://drive.google.com/drive/u/0/folders/0ACJgTKpEpTmHUk9PVA) 0ACJgTKpEpTmHUk9PVA is its ID.
* Authenticate and copy the code from Google and paste it into Authorization Code Box.
* Click on Get Code to Generate Code and Copy it for later use.
* Now Create Cloudflare account and verify email or login with existing account.
* Find Workers and Open it.
* Create your sub-domain or continue if already done.
* Select the Free Plan.
* Click on Create a Worker.
* You can rename the workers at top of the page.
* Now paste the code you copied before.
* Click on Save and Deploy.
* Done. (May take time for some users due to new account or cache issues)
* [Watch Video](https://www.youtube.com/watch?v=8WMddzVX1Dw&feature=youtu.be)

## Design/UI Development (Based on Main Code)

* [Worker JS](https://github.com/SamirJanaOfficial/Shinobi-Drive-Index/blob/master/worker/dist/custom-worker.js)
* [Custom MDUI css](https://github.com/SamirJanaOfficial/Shinobi-Drive-Index/blob/master/worker/dist/custom.css) required for Model.
* [Source of Design](https://github.com/SamirJanaOfficial/Shinobi-Drive-Index/blob/master/worker/dist/custom-dev.js)
* Fork and Test and make Pull Request.

## Credits

* Source: [maple3142](https://github.com/maple3142/GDIndex)
* Source: [yanzai](https://github.com/yanzai/goindex)
* New Design: [Bootstrap](https://getbootstrap.com)
* Cloudflare: Workers
