# MailCow-Pixel-Flood-Attack
#### Description:
The application is vulnerable to pixel flood attack, once the payload has been successfully uploaded in the logo the application begans to slow and the admin page doesn't respond.

#### Affected Version: 2023-12a

#### Steps to reproduce:
1. Set up an mailcow-docerized SMTP server.
2. Login to the admin page and navigate to the "customize" functionality.
3. Now change the logo to "lottapixel.jpg" and wait until it gets fully uploaded. Note: It will take some minutes to upload the lottapixel.jpg
  <img src="POC-1.png"/>
  <img src="POC-2.png"/>
  <img src="POC-3.png"/>
4. After the successful upload it can be observed that the mail server will not respond properly and if the server spec is low it will also make the server go down and collapse.

