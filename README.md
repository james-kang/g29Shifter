# Arduino G29 Shifter

The shifter Internally uses 2 potentiometer and a button for the reverse gear

# Requeriments

* Logitech G29 Shifter
* Arduino Leonardo or ProMicro
* DB9 male connector
* DB9 breakout board for pro micro
<img src=https://github.com/james-kang/g29Shifter/blob/93500ec4c2540d870335489fedcaf29a87e1c554/breakout_board.png" />
  

# Shifter Pinout

The logitech uses a female shifter, let's see the pinout

<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSu9WPtlZwppyEhPwWwFBGUPpkCjzNeYiPBXw0HjFjio9QPhMz0" title="DB9 female port" />

1&nbsp;2&nbsp;3&nbsp;4&nbsp;5 <br />
.&nbsp;.&nbsp;.&nbsp;.&nbsp;.  <br/>
&nbsp;.&nbsp;.&nbsp;.&nbsp;.<br/>
&nbsp;6&nbsp;7&nbsp;8&nbsp;9<br/>


Pin 4 -> X Axis <br />
Pin 8 -> Y Axis <br />
Pin 2 -> Reverse Button<br />
Pin 3,7 -> Vcc<br />
Pin 6 -> Ground<br />

# Arduino Pinout

After soldering the wires to the male DB9 make the connections to match according to this

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; DB9 <br />
A0 -> Pin 4 <br/>
A2 -> Pin 8 <br />
D2 -> Pin 2 <br />
Vcc -> Pin 3,7<br />
GND -> Pin 6 <br />


# Contributors

based on this project <https://github.com/functionreturnfunction/G27_Pedals_and_Shifter/>


