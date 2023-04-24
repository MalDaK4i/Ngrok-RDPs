## Ngrok-RDPs
- Perform With RDPs Using Ngrok [Forwading]
## What is this?
- RDPs using ngrok is a technique used to remotely access a computer via a public internet network with the help of the Ngrok network addressing protocol routing. Ngrok will create a secure tunnel between the client (the computer that wants to access) and the Ngrok server connected to the public internet. Once the tunnel is established by Ngrok, clients can establish an RDP connection to the Ngrok IPs address provided by the Ngrok server and connect to the device via the public internet network.
## How To Use?
``` 
FIRST STEP:
$ Create an account on ngrok.com (SKIP THIS IF ALREADY OWN)
$ Find Your Authoken on NGROKs dashboard and copy it to your clipboard.

SECOND STEP:
$ Click on "Fork" to create a copy of the "Ngrok-RDPs" repository in your own GitHub account.
$ Click on "Settings" => "Secrets" => "New repository secret".
$ In the "Name" field, type "NGROK_AUTH_TOKEN".
$ Paste the authtoken from NGROKs dashboard (FIRST STEP) into the "Value" field on GitHub, and then click "Add Secret".
$ Go to "Actions" => "AWS" => "Run Workflow".
$ Reload the page & go to "AWS" => "Build"
$ You will get the Ngrok Domain:Port & Username:Password

LAST STEP:
$ Find "Remote Desktop Connection (RDP)" From Windows Start Menu.
$ PUT our Ngrok Domain:Port & Username. It's will popup credentials/authorized.
$ PUT our password & KONEK. Donttttt suyyyyyyyyyyyyyyyyyyy me!
``` 
## Screenshot:
![Screenshot_1](https://user-images.githubusercontent.com/25004320/234003488-14abdf67-19f2-43b3-9452-04e6d52f3355.png)
![speedtest](https://user-images.githubusercontent.com/25004320/233995465-2dbeba9a-bb77-4c24-835d-5a8cb5b7076d.png)
## Footprints Notes:
- By using this tool, you agree that you are using it for educational purposes only and that you will not use it for any illegal activity. You also agree to bear all risks associated with the use of this tool. I will not be responsible for direct or indirect damage caused by the use of this tool.
## Author:
- Pari Malam
## Contacts:
[![Telegram](https://img.shields.io/badge/-Telegram-blue)](https://telegram.me/SurpriseMTFK)
[![Forum](https://img.shields.io/badge/-Forum-red)](https://dragonforce.io)
