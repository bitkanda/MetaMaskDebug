# MetaMaskDebug

[中文版 README](README-cn.md)

MetaMask mobile wallet enables WebView debugging mode, allowing direct debugging of DAPP using Google Chrome.

In addition, based on the official source code, we make the following commitments: We will not collect user's private data, such as private keys or mnemonic phrases, and there are no backdoors. The primary purpose of modifying this wallet is for our own use and to facilitate compatibility testing with applications in the cryptocurrency industry. As a source of revenue, users will be charged for debugging Dapps.

This application has undergone minor modifications based on the official source code, with the following changes.

The version number of MetaMask mobile for Android is v7.3.0.
Two main functionalities are supported:

1.HTTPS DApps do not validate certificates, making it convenient for developers to debug DApps within the local network--free.

2.WebView's DEBUG mode is unlocked, facilitating source code debugging of DApps using "inspect with chrome developer tools" - available for a fee.

Please download our latest version of the application for installation. The file is a bit large, so please use a download manager for assistance, such as Thunder or BitTorrent. The download link is as follows:
https://github.com/bitkanda/MetaMaskDebug/releases

Installation Guide:
1.Installation Interface.
<br>
<img src="pic/1.jpg" alt="Install" width="50%" height="50%"/>
<br>
2.Installation in progress.
<br>
<img src="pic/2.jpg" alt="Install" width="50%" height="50%"/>
<br>
3.Welcome Screen.
<br>
<img src="pic/3.jpg" alt="Install" width="50%" height="50%"/>
<br>
4.Wallet Interface.
<br>
<img src="pic/4.jpg" alt="Install" width="50%" height="50%"/>
<br>
5.Add BNB Smart Chain Network.
<br>
<img src="pic/5.jpg" alt="Install" width="50%" height="50%"/>
<br>
6.Locate BNB Smart Chain and click 'Add'.
<br>
<img src="pic/6.jpg" alt="Install" width="50%" height="50%"/>
<br>
7.Click 'Approve'.
<br>
<img src="pic/7.jpg" alt="Install" width="50%" height="50%"/>
<br>
8.The new network has been added. Do you want to switch to this network? Click 'Switch to network'.
<br>
<img src="pic/8.jpg" alt="Install" width="50%" height="50%"/>
<br>
9.Open the wallet Dapp browser, it prompts to connect to an account. Click 'Connect'.
<br>
<img src="pic/9.jpg" alt="Install" width="50%" height="50%"/>
<br>
10.Here, you can choose to authorize the connection of multiple accounts.
<br>
<img src="pic/10.jpg" alt="Install" width="50%" height="50%"/>
<br>
11.After switching networks, you need to click on the '...' menu and then select 'Reload' to refresh the current page.
<br>
<img src="pic/11.jpg" alt="Install" width="50%" height="50%"/>
<br>
12.After refreshing, you should be able to see your account, the payment gateway, and payment information.
<br>
<img src="pic/12.jpg" alt="Install" width="50%" height="50%"/>
<br>
13.In the input box, enter '1' to subscribe for 1 month. Then click on 'Subscription Device ID'.
Displaying the monthly subscription fee, click 'Confirm.' Please note that this fee is subject to change at any time.
<br>
<img src="pic/13.jpg" alt="Install" width="50%" height="50%"/>
<br>
14.After a successful payment, it will automatically refresh the expiration date.
<br>
<img src="pic/14.jpg" alt="Install" width="50%" height="50%"/>
<br>
15.To connect your phone to your computer via USB, open the Chrome browser and enter 'chrome://inspect/#devices' to access the debugging entry and the DAPP that can be debugged.
<br>
<img src="pic/15.png" alt="Install" width="50%" height="50%"/>
<br>
16.You can enter the address of your application developed in VUE or another DAPP, whether it's on the public internet or on the same local network, to debug and view error messages. These pieces of information are extremely useful for debugging and troubleshooting.
<br>
<img src="pic/16.png" alt="Install" width="50%" height="50%"/>
<img src="pic/17.png" alt="Install" width="50%" height="50%"/>
<img src="pic/18.png" alt="Install" width="50%" height="50%"/>
<br>
If you have any further questions, please visit https://github.com/bitkanda/MetaMaskDebug/issues to submit them. Thank you, and happy coding to everyone!

