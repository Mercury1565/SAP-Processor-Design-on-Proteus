Increment '1' till 255 and decrement '1' till 0(and circulate...)
-----------------------------------------------
0:DISP
1:ADD 15
2:JUMP_CAR 4
3:JUMP 0
4:SUB 15
5:DISP
6:JUMP_IFZ 0
7:JUMP 4

-----------------------------------------------

0000: 0100 0000 -> 40
0001: 0010 1111 -> 2F
0010: 1010 0100 -> A4
0011: 1001 0000 -> 90
0100: 0011 1111 -> 3F
0101: 0100 0000 -> 40
0110: 1011 0000 -> B0
0111: 1001 0100 -> 94
.
.
.
1111: 0000 0001 -> 01