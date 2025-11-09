# FACTORIAL-OF-A-NUMBER-USING-8051-KEIL

**AIM:**

To write and execute Assembly language Program to perform factorial of a number using 8051 keil.
APPARATUS REQUIRED: Personal computer with Keil software

**ALGORITHM:**

• Start  

• Input: Read the number n.  

• Initialize:  

•Set factorial to 1.  

•Set i to 1.  

• Loop: While i is less than or equal to n:  

•Multiply factorial by i.  

•Increment i by 1.  

• Output: Store or print the value of factorial.  

• End

**FLOW CHART:**
<img width="261" height="308" alt="image" src="https://github.com/user-attachments/assets/bffe89f6-3ba9-4294-b817-8b545f680e66" />

**Program:**

ORG 0000H   

MOV A,#04H  

MOV R0,A  

ACALL FACTORIAL  

MOV 40H,A  

SJMP THIN  

FACTORIAL:DEC R0  

CJNE R0,#01H,PRODUCT  

SJMP THICK   

PRODUCT:MOV B,R0  

MUL AB  

ACALL FACTORIAL  

THICK: RET  

THIN:  

END


**Input:**
<img width="979" height="534" alt="image" src="https://github.com/user-attachments/assets/bab9136c-2511-4290-bd0a-82921ed7fea4" />

**Output:**  
<img width="966" height="532" alt="image" src="https://github.com/user-attachments/assets/1bd5cebc-b1f5-46df-8346-f08ac402a4ff" />



**Manual Calculations:**  
![WhatsApp Image 2025-11-09 at 16 49 50_c374cb41](https://github.com/user-attachments/assets/4a70234b-09ba-44a9-b282-dbc40495619f)



**Result:**

Thus the factorial of a number using 8051 keil was calculated and shown the output.
