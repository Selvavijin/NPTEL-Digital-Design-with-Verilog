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

The number of variables in an expression can be given as 'n'. The number of minterms can be given as 2^n. And the the value of the minterm can be 0 or 1 so it can be given as 2^(2^n).

![image](https://github.com/user-attachments/assets/a5e60bf0-aaec-45d4-886a-f383a9a61678)

![image](https://github.com/user-attachments/assets/568d6236-23df-4d25-b19c-670c5d873c91)

![image](https://github.com/user-attachments/assets/775f0fb0-e8d4-4a00-b6b4-35849091430c)

![image](https://github.com/user-attachments/assets/173d39a2-fe97-4f0c-927e-d25abe729e7c)

Week 1
  Lecture 4 - Number systems

  ![image](https://github.com/user-attachments/assets/0d2af51d-6f3f-49b9-bcaf-928030223f40)

![image](https://github.com/user-attachments/assets/bd3fd1dd-1dfd-4771-b4a4-67b165c96ccd)

![image](https://github.com/user-attachments/assets/a673bb91-d985-4ef7-ab4c-eb4a98057126)

![image](https://github.com/user-attachments/assets/6d441408-5348-4ee4-bbf2-3dd43ba588af)

![image](https://github.com/user-attachments/assets/9a3f6cb6-0d34-4903-a0c9-61886527563a)

![image](https://github.com/user-attachments/assets/beadf954-5165-43dc-a16a-104cf760b07b)

![image](https://github.com/user-attachments/assets/cb853e7d-7912-47d4-9440-82e5af06ff19)

![image](https://github.com/user-attachments/assets/afffdf26-36a9-485d-b0de-aee6df1197e8)

![image](https://github.com/user-attachments/assets/573ab56b-f0af-411d-95ae-0d5d5b468c1e)

![image](https://github.com/user-attachments/assets/9e5a1a42-3870-4691-a653-8a8b2fbcf7e2)

![image](https://github.com/user-attachments/assets/627b7dd4-5b72-4e39-8c47-f2588c66de8e)

![image](https://github.com/user-attachments/assets/36565f46-7378-41db-921e-d9e60c9d79d2)

Week 2
  Lecture 5 - Binary Arithmetic

 r's complement and (r-1)'s complement.

  ![image](https://github.com/user-attachments/assets/3fd8747b-884c-4446-8f44-b5c52b455310)

![image](https://github.com/user-attachments/assets/1017475b-28f2-41bc-87e5-89158005cc5b)

![image](https://github.com/user-attachments/assets/2b822e23-5ba9-41ef-a2a8-9bf8125e98f2)

![image](https://github.com/user-attachments/assets/8623f2d3-fff3-4069-9073-ef6ff3344901)

![image](https://github.com/user-attachments/assets/4257426e-b319-4276-bc83-d69f0d49acec)

![image](https://github.com/user-attachments/assets/47cd8a5a-065f-48e7-978d-98e67f6d8598)

![image](https://github.com/user-attachments/assets/f9449be1-1362-4357-ae01-e004f3c2a423)

Let us consider 4 bit and the range for it in unsigned form is from 0 to 15(0 to 2^(n-1)). In the signed form, the range is -7 to 7( -2^(n-1) to 2^(n-1)). The three ways of representing a negative sign number is shown below.

![image](https://github.com/user-attachments/assets/9c898190-46eb-471d-b73c-e18865ebce64)

If we are using 2's complement, we don't need to treat the sign bit(MSB) separately. We can treat it as other bits.

![image](https://github.com/user-attachments/assets/1c4ace7b-7012-4637-9c3e-39ead8107ce3)

![image](https://github.com/user-attachments/assets/e4e2f902-f494-422f-954c-62529260f01b)

![image](https://github.com/user-attachments/assets/eb646e62-4907-4729-bac2-959caaec311d)

![image](https://github.com/user-attachments/assets/18dc9554-4c8c-4318-b446-0ec2acbbb5f3)


