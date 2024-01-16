# Switcher board for Apple II Dead Test RAM Diagnostic ROM

I was using another Diagnoctics card, but the other day when I was repairing my Apple II Plus, I accidentally inserted it backwards. The card's microcontroller and ROM were fried...Then I found out about this project and tried it right away and it was really great!<BR><BR>I used a 2KB ROM with the Apple II Plus F8, but I redesigned the PCB so that I could switch between the autostart monitor ROM and the 4KB ROM.<BR><BR>

The prototype worked fine, but I will upload everything once the PCB is completed.<BR>

<img src="Pictures/DTS_V1.1-a.png" width="520px"><BR><BR>

- Uses 2732 EPROM. In this case, 2 ROMs can be switched between pull up and pull down.<BR>
- Uses 2716 EPROM. Connect the middle two of the 6p switch and use no parts other than the EPROM, inverter, and capacitor. In this case, it can be used for repairs as a substitute for ROM from D0 to F0.<BR>
- Of course, when 2716 is installed on the Dead test switcher board, it is compatible with ROMs from ROM-D0 to ROM-F8.
