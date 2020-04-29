1. If the start.bat file doesnt work try below methods.  
For Windows -> Add ↓ to a text file and save the text file as start.bat then run file.
java -Xmx4G -Xms4G -jar forge-1.15.2-31.1.25.jar nogui

For Mac -> Add ↓ to a text file and save the text file as start.command then run file.
#!/bin/bash
cd "$(dirname "$0")"
exec java -Xmx4G -Xms4G -jar forge-1.15.2-31.1.25.jar nogui

2. For the first startup, you have to agree to the Mojang EULA. Open eula.txt file, read EULA and change "false" to "true" if you accept it.

PS: Don't worry about the red cross before you connect to the server.
Always remember to back up your server!

If you want to update your server copy "mods" and "config" and replace the old versions of the folders.