# Experiment--02-Implementation-of-combinational-logic
Implementation of combinational logic gates
 
## AIM:
To implement the given logic function verify its operation in Quartus using Verilog programming.
 F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D
F2=xy’z+x’y’z+w’xy+wx’y+wxy
 
 
 
## Equipments Required:
## Hardware – PCs, Cyclone II , USB flasher
## Software – Quartus prime


## Theory
 

## Logic Diagram
## Procedure
## Program:
/*module cl(a,b,c,d,w,x,y,z,F1,F2);
input a,b,c,d,w,x,y,z;
output F1,F2;
wire A1,A2,A3,A4,A5,B1,B2,B3,B,B5;
assign A1=(~a&(~b)&(~c)&(~d));
assign A2=(a&c&(~d));
assign A3=((~b)&c&(~d));
assign A4=(~a&b&c&d);
assign A5=(b&(~c)&d);
assign F1=A1|A2|A3|A4|A5;
assign B1=(x&(~y)&z);
assign B2=(~x&(~y)&z);
assign B3=(~w&x&y);
assign B4=(w&(~x)&y);
assign B5=(w&y&z);
assign F2=B1|B2|B3|B4|B5;
endmodule

Program to implement the given logic function and to verify its operations in quartus using Verilog programming.
Developed by: DANUSH REDDY
RegisterNumber:212223040029  
*/
## RTL realization

## Output:
## RTL:![Screenshot 2024-01-02 202624](https://github.com/danushreddy7/Experiment--02-Implementation-of-combinational-logic-/assets/149035740/35c7ff49-938a-43b1-84f6-0a72b90fe59f)
Trueth table:![WhatsApp Image 2024-01-02 at 20 39 42_d77b9cc8](https://github.com/danushreddy7/Experiment--02-Implementation-of-combinational-logic-/assets/149035740/06208a49-3e7b-4b4b-8a8a-81d4d708e3d7)


## Timing Diagram:![WhatsApp Image 2024-01-02 at 20 39 42_7a5bf64c](https://github.com/danushreddy7/Experiment--02-Implementation-of-combinational-logic-/assets/149035740/5445707d-fc81-4309-a30d-881657ee4b29)

## Result:
Thus the given logic functions are implemented using  and their operations are verified using Verilog programming.
