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

**Output:**  

INPUT
<img width="945" height="270" alt="Screenshot 2025-11-06 203425" src="https://github.com/user-attachments/assets/4ee9675e-4374-4a27-a379-3981112fcacf" />
OUTPUT
<img width="955" height="270" alt="Screenshot 2025-11-06 203512" src="https://github.com/user-attachments/assets/aaa9a7d5-6665-46d0-b613-362fe5809ed6" />




**Manual Calculations:**  

![WhatsApp Image 2025-11-07 at 09 14 57_c476006f](https://github.com/user-attachments/assets/3f86f90b-2d41-4ccc-a967-f04474a53ee3)





**Result:**

Thus the factorial of a number using 8051 keil was calculated and shown the output.
