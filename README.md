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

Week 2
  Lecture 6 - Binary codes

  ![image](https://github.com/user-attachments/assets/894ba980-a9cd-4881-8981-b8d8d7a02752)

![image](https://github.com/user-attachments/assets/0c201313-fa9f-4a46-81da-4d8fed78fdf0)

![image](https://github.com/user-attachments/assets/6dc8e6a5-299d-4020-8987-7978906ce2d8)

The difference with the 8421 code and the other weighted code is uniqueness. ie) in 8421 code, we can represent '2' in only one way '0010'. Whereas in 2421 code we can represent '2' as '1000' or '0010'. But for 2421 and 642-3 codes, they have self-complementing property. Eg: let us take 0001 in '2421' code and complement it, we get 1110. 0001=1 and 1110=8, so if we subtract 9-8 we get '1' and if we do 9-1 we get '8'. So, it is self-complementing. But, BCD is not self-complementing. If we add 2+4+2+1 we get 9 and 6+4+2-3=9. Thats why we have the self complementing property. If we add 8+4+2+1, we get 15. So, it is not self complementing.

![image](https://github.com/user-attachments/assets/4870d512-1592-4e73-aa65-e9d1e8de5946)

![image](https://github.com/user-attachments/assets/27c23228-3135-4a9a-9a46-bb1a9e2ad77f)

Excess 3 codes are obtained from BCD by adding 3. But it is self-complementing and BCD is not self-complementing.

![image](https://github.com/user-attachments/assets/8ff9c55d-4446-4725-8d8d-6d0884a46b4f)

![image](https://github.com/user-attachments/assets/d6cf6733-cb18-459b-9609-cc44444acc98)

![image](https://github.com/user-attachments/assets/e271540a-b406-456c-af8c-2dbe9272a3dc)

Binary to gray code and gray code to binary conversion.

![image](https://github.com/user-attachments/assets/9653d0bd-d1fb-4ac8-969e-7468e9f8dc9c)

Gray code is cyclic code as well as reflected code.

Week 2
  Lecture 7 - Error Detection and Corrections Codes

In error detectable code, the distance between the valid and the error code is 1. The distance between two valid codes is 2. So, if the the distance between two codes is 1, then it is an error code. 

  ![image](https://github.com/user-attachments/assets/bb14d2cf-36f7-453c-96fa-93e819ff8cae)

![image](https://github.com/user-attachments/assets/047d42dc-fc59-4ee9-a22e-0e8fc24e9c92)

![image](https://github.com/user-attachments/assets/d0741d28-638f-4dca-8325-5fa773c8b0fa)

In error detecting code, we can only detect that a error is occured and we can resend the data. Next we will see the error correcting codes. If we find a error code and if we know that this error code is only reachable from a particular valid code, then we can easily correct it. In error correcting code, the distance between two valid codes is atleast 3.

![image](https://github.com/user-attachments/assets/e692ff57-792a-474b-aee2-420f72bc48a6)

![image](https://github.com/user-attachments/assets/b4078bb6-8c38-45b3-94c8-b07ef2f0a2be)

![image](https://github.com/user-attachments/assets/e8796b00-f1eb-4688-8a2a-30602e6c2c96)

![image](https://github.com/user-attachments/assets/50923778-39b5-4318-88b6-1db6c3f2fa7d)

using this value of 'k', we can find the error that happen in any of the bits.

![image](https://github.com/user-attachments/assets/6f188190-08fa-4633-9547-85cf50ca4e48)

![image](https://github.com/user-attachments/assets/a3252cf8-8451-4623-8cd5-6606de0ebbf7)

![image](https://github.com/user-attachments/assets/041bda43-8748-4535-9468-2d0abc2229bc)

![image](https://github.com/user-attachments/assets/0acc640d-105d-4211-a0c0-ba4fe7e72d28)

![image](https://github.com/user-attachments/assets/33361aae-8c89-4dcd-ab17-04dcd43be73c)

![image](https://github.com/user-attachments/assets/aa97849b-1ede-4b96-b49f-d986048801da)

![image](https://github.com/user-attachments/assets/ebc49463-0ea6-430f-9d53-a712bd92337f)

Week 3
  Lecture 8 - Minimization of Switching functions-Karnaugh Map

  When we implement this in hardware, it will take some time. We can also reduce this time. The main objective is to reduce the time and area. This time that we set depends on the critical path that is present. Here, the time of the critical path is 4 units. The number of gates will depend on the number of literals in the equation. So, the first objective is to reduce the literals present in the switching function so that the AND gate will gets reduced in case of SOP. The next objective should be reducing the number of product terms so that the number of OR gate will gets reduced. Eg: if there are 2 product terms, we need 1 AND gate. And if we have 3 product terms, we need 2 AND gates. This have more impact on delay, because these gates are connected in series and not in parallel. If the gates are in parallel(literals), then there will not be a more issue in delay, but the area will increase.

![image](https://github.com/user-attachments/assets/d9ade6b6-6caf-4d55-9914-b41ae9540408)

![image](https://github.com/user-attachments/assets/f972d63b-b42d-48ed-b6c8-73019e20820f)

If an expression is irredundant, it does not mean that it is the minimal expression. We can have multiple irredundant expression.

![image](https://github.com/user-attachments/assets/5ed62bbb-beca-4539-a890-0373a0b14a54)

![image](https://github.com/user-attachments/assets/524509b3-faf6-4f54-a714-3b666fe3b090)

![image](https://github.com/user-attachments/assets/a1acf724-47fe-4c7a-ba57-109142f76845)

Week 3
  Lecture 9 - Karnaugh Map

  ![image](https://github.com/user-attachments/assets/7345e59e-1c5d-4047-877d-bb2b1ab17cd4)

The best way to do the k-map is finding the smaller cubes(pairs) first and then proceeding to higher levels of grouping(four or eight). The reason is shown below.

![image](https://github.com/user-attachments/assets/8ca2f81c-68b2-421d-b27f-03f5ca66a343)

![image](https://github.com/user-attachments/assets/5977584c-f46b-4677-a82c-931b6a0472b5)

![image](https://github.com/user-attachments/assets/20531b61-8a1e-4e76-b446-34a2e6b87b7a)

![image](https://github.com/user-attachments/assets/7c970b11-739a-43d1-986d-a4dcca734fa9)

![image](https://github.com/user-attachments/assets/06e485b8-6cbd-4802-ab49-7735b885515e)

![image](https://github.com/user-attachments/assets/86aebd7c-1561-4431-bf44-8683068cb294)

![image](https://github.com/user-attachments/assets/88287baa-aaef-4a9b-8aa1-b5413e385fab)

Week 3
  Lecture 10 - Minimization of Switching functions-Properties

  ![image](https://github.com/user-attachments/assets/9293f8f1-224d-483d-b93c-b33ac7dfc5c3)

![image](https://github.com/user-attachments/assets/c4867a13-e260-4c7a-8cda-715955b71abb)

![image](https://github.com/user-attachments/assets/bf7416a9-9193-4d87-ab7c-059729038299)

![image](https://github.com/user-attachments/assets/60ff1d5b-9a36-4063-9424-51bf00dca07c)

![image](https://github.com/user-attachments/assets/05fd301d-f355-4e66-8d1a-6e780cfb6859)

![image](https://github.com/user-attachments/assets/ca2cf9a0-de58-4a92-bf04-dc4500373871)

In the case where all are essential prime implicants, we have one unique minimal expression. Whereas in the second case we will have multiple minimal expressions.

![image](https://github.com/user-attachments/assets/c97cebdc-e765-4f10-ac08-6b2a0a6aa8e2)

![image](https://github.com/user-attachments/assets/0bdf7453-e8c9-46e6-9e3f-14f2222716c7)

![image](https://github.com/user-attachments/assets/e94da5dc-dff2-46bc-8f57-1a4e271a8338)

Week 3
  Lecture 11 - Quine-McCluskey Method

  ![image](https://github.com/user-attachments/assets/1efabd3a-c06c-4f44-8544-7f38f1129600)

![image](https://github.com/user-attachments/assets/481895ff-f381-4d9d-8be6-158722b33592)

![image](https://github.com/user-attachments/assets/30f43462-78a5-4521-8e6d-5fc3e346f478)

![image](https://github.com/user-attachments/assets/9c9f7a01-83db-4d1d-8169-8da67ce53b7c)

![image](https://github.com/user-attachments/assets/c78cb45b-93b4-4039-9eab-18401ca9e166)

![image](https://github.com/user-attachments/assets/b2cc37e0-e297-435f-acf5-32fccfdf1da1)

Essential prime implicants are the terms which are present for any minimal expressions.

![image](https://github.com/user-attachments/assets/49726ef2-70da-43c2-ad7f-41be93a35124)

![image](https://github.com/user-attachments/assets/67ac6c25-dc93-4ee2-beeb-44037bc0b485)

![image](https://github.com/user-attachments/assets/c487972b-b2e9-4543-8ba1-5307f2a9e909)

![image](https://github.com/user-attachments/assets/d87f7a51-1a73-4172-bffe-d82ca13fd6d7)

