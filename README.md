#Restart Roon Server
Sometimes Roon will display nothing except for (`System output`) under settings > audio, not detecting output devices connected to the machine. The commands in these files kill a roon server running on a silicone mac and open the app. This should allow you to start a new server in the app, where all fo your zones and devices should then appear.
- The commands in install-command will make a copy of the resfresh-roon script into (`opt/homebrew/bin`) and give it execution permissions to make it globally executable.
- To restart your roon server, type (`refresh-roon`) into the terminal.
  - If you're using the server in the app, it will attempt to reconnect for a few seconds before prompting you to swtich. At this point, start a new server on your device.
  - If you don't have roon open, this script will restart the server and open the app. You can then start a new server on your machine.
 
