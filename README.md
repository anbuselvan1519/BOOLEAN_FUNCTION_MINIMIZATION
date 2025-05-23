# BOOLEAN_FUNCTION_MINIMIZATION

## Name: Anbuselvan S
## Reg no: 212223240008

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

Boolean Algebra is a branch of algebra that deals with boolean values-true and false.It is fundamental to digital logic design and computer science,providing a mathamatical framework for describing logical operation and expressions.

**Logic Diagram**

1.F1

![image](https://github.com/user-attachments/assets/5cdd08df-5bfc-4a66-a41f-2c779dabcca4)


2.F2

![image](https://github.com/user-attachments/assets/323c707e-4bac-4d3e-84ab-c608db7aad35)


**Boolean Function Minimization**

1.F1

![image](https://github.com/user-attachments/assets/0502bd9b-dd8b-4a2a-8f84-962b172b25c9)


2.F2

![image](https://github.com/user-attachments/assets/29b96269-56bd-4ae6-95b3-217f24fca82e)


**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

1.F1

```verilog
module function1(a,b,c,d,fun1);
input a,b,c,d;
output fun1;
assign fun1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule
```

2.F2

```verilog
module function2(w,x,y,z,fun2);
intput w,x,y,z;
output fun2;
assign fun2=((~y & z)|(w & y)|(x &y));
endmodule
```
```
Developed by    : Anbuselvan S
Register Number : 212223240008
```
**RTL**

1.F1

![image](https://github.com/user-attachments/assets/e016b503-f362-4de9-8761-dcca0be1648e)


2.F2

![image](https://github.com/user-attachments/assets/ad98383a-9b61-41a3-9f9d-91876bae4e53)


**Timing Diagram**

1.F1

![image](https://github.com/user-attachments/assets/2b28f1c1-cc36-431d-9d5a-dd45081e0616)


2.F2

![image](https://github.com/user-attachments/assets/b77eb36a-0369-4d09-a5a4-eda0decfeb63)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

