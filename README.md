# Integer Games Public Key Listener
This repository represent the authorized Listener of a integer in the Integer Games Server.


For the moment, there is only one owner of a integer and so one Public key.  
But you may want to share or not share your integer with the community.  

If there is only your key, only you can read it.  
If there is several keys, you share the read with other public key.  

Example of why you would allows this:
Game:
  - Trigger a sniper macro on a team of 2-4 to fire at the same time.
  - Trigger allows a friend to copilote your keyboard for healing or specific power.

Iot: 
  - Allow to turn on the light and share the notification to a friend or service without sharing your private key.

**Important: **
- You can't listen to a integer value without RSA key on the server.
- All the byte return sent to listener are added on the owner account.

