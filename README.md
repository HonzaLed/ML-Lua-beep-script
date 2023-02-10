# ML-Lua-beep-script
Using this you can play some melodies using the buzzer in Canon cameras with Magic Lantern support  
Based on https://github.com/robsoncouto/arduino-songs  

You can play any song from `arduino-songs` using my code  
The only thing that you have to do is replace the `melody` array and `tempo` variable in my code with the code from the song you have choosen  
(also remember to replace C style commenst with Lua style ones in the `melody` code, just replace any `//` in the `melody` code with `--`)

You can then run the script in any Magic Lantern supporter camera by putting the script into the `ML/SCRIPTS` folder on your SD/CF card and enabling the Lua scripting module in Magic Lantern menu
