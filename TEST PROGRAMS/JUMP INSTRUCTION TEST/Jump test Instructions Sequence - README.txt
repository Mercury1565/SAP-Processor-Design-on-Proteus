Continously increment 3 on content of reg_A and display
------------------------------------------
0:LD_IMM 3
1:STOR 15
2:LD_IMM 0
3:ADD 15
4:DISP
5:JUMP 3
-------------------------------------------
0000: 0110 0011 -> 63
0001: 0101 1111 -> 5F
0010: 0110 0000 -> 60
0011: 0010 1111 -> 2F
0100: 0100 XXXX -> 4X
0101: 1001 0011 -> 93