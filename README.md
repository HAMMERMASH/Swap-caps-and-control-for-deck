# My keyboard mapping

# In file /etc/default/keyboard
add XKBOPTIONS="ctrl:nocaps"

# .Xmodmap
keycode 37 = Caps_Lock NoSymbol Caps_Lock
keycode 9 = grave asciitilde
keycode 49 = Escape

# Another way
setxkbmap -option ctrl:nocaps
