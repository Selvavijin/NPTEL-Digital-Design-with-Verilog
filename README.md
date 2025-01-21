# NPTEL-Digital-Design-with-Verilog

Week 1
  Lecture 1 - Introduction to digital design with verilog

![image](https://github.com/user-attachments/assets/91e7cd54-d16f-4ae3-907e-e817be2e2a25)

![image](https://github.com/user-attachments/assets/97bfde6c-776f-466a-bd56-99fafe3e821d)

![image](https://github.com/user-attachments/assets/fe96b89a-bb7d-4148-96bf-00b232d586d1)

![image](https://github.com/user-attachments/assets/e7ae03ff-14a5-44d1-ab1b-710239047260)

![image](https://github.com/user-attachments/assets/ca999a60-d34f-44a9-bc9a-44c97761f713)

In olden days we had transistors which occupies rooms. Now a single chip can contains billions of transistors. This is the evolution that happened from the olden days from transistor level to the gate level to the RTL to the Behavioral model.

![image](https://github.com/user-attachments/assets/1073dccd-74b8-49ec-957f-3b1a5ebf53e1)

So, the RTL can be converted to the Gate-level which is called 'logic synthesis' which can be done through EDA tools and then the gate-level can be converted to the transistor level which is called the 'physical synthesis'.
In combinational logic we need understand to represent adders, multipliers, encoders, etc and also to represent the numbers.
In sequential logic we need to understand about storing elements like FFs, registers, counters, etc. Also we should understand that it operates on clock. The combinational logic is the input of the sequential logic. Then we have FSMs which is used for the control purpose. So, if we combine this 3, that will constitute the digital system.

![image](https://github.com/user-attachments/assets/ca90f0db-25ae-46c1-b083-4cf47c092d03)

![image](https://github.com/user-attachments/assets/42122f04-0ea1-4d1e-a722-783c9e82cfa1)

Week 1
  Lecture 2 - Switching algebra

The equation that is mentioned below is said to be a switching expression. Because, a,b,c,d all can switch to 0 or 1.

![image](https://github.com/user-attachments/assets/b75cb236-66c1-4b8b-95f0-6da2fe79310f)

We can apply some rules to manipulate this expression and that is called as switching algebra.

![image](https://github.com/user-attachments/assets/d82582ec-54d7-4dd4-a588-4dc17cfbc71d)

![image](https://github.com/user-attachments/assets/8115e229-1bbb-4338-9a0d-0a34fa4cd2e4)

Let us say that there are two circuits in two different blocks. We need to check whether both are equal. To do that, we can find the expression of both circuits and simplify and if they are equal, we can say that they are equal.

![image](https://github.com/user-attachments/assets/40404619-4499-4d4b-b8c1-c8c7de43cd9f)

![image](https://github.com/user-attachments/assets/11310787-d450-477f-b4c5-bbbbc9f5c9c1)

![image](https://github.com/user-attachments/assets/1a422342-c801-4180-a085-f3fb77922575)

let us take the expression x+x'y = x+y. Here, let us take the LHS, if we substitue, x=1, the entire LHS is 1. Because, 1 + anything is 1. Also, when we substitute x=0, we get, 0+1y which means that the ouput depends on 'y'. So, x' is considered as a redundant value. So, the RHS is x+y.

![image](https://github.com/user-attachments/assets/6445e00b-8877-4ea8-b8b6-cb7c6e2bf28a)

![image](https://github.com/user-attachments/assets/f5e3df02-1371-4d9c-98ae-55a1a52f3614)

![image](https://github.com/user-attachments/assets/aa60cec3-0056-490b-9225-26f2f9b38b84)

![image](https://github.com/user-attachments/assets/13094a07-0ed7-43aa-b311-210ff7d902ae)

Week 1
  Lecture 3 - Canonical forms of switching functions.

  Canonical forms are useful in finding equaliance between two expressions in a unique way than solving it in a normal way.

  The individual terms such as x'y'z' are called the minterms. And a minterm should have all the variables either in the normal or complemented form. 
  ![image](https://github.com/user-attachments/assets/938cd66e-beb8-410a-b36a-156e1834b815)

  ![image](https://github.com/user-attachments/assets/acf966a6-8ec0-42e0-ac99-d1f3b394a2c8)

![image](https://github.com/user-attachments/assets/e75201a7-27b7-4086-b3e9-a2cb87228b6f)

![image](https://github.com/user-attachments/assets/1c3bb333-fff1-4dcf-9cd2-d2e52b06f063)

![image](https://github.com/user-attachments/assets/caf928af-77bb-472e-9848-be43c55ea54b)

Here, T is given and to find the PoS we need the T'. Actually it is a 3 variable expression and there should be 8 minterms. For T, there is only 6 minterms, so, for T' the other minterms should be present. So, that is how it is solved.

![image](https://github.com/user-attachments/assets/a7846427-6c25-44b4-9a2d-2716efc12e85)


