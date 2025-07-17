#add this shortcut command for volume up, you can use every shortcut combination if it do not overlap

pactl set-sink-volume @DEFAULT_SINK@ +5%

# also add this shortcut command for volume down

pactl set-sink-volume @DEFAULT_SINK@ -5%

#if you get an error you should download pulse audio 

apt-get install pulseaudio
