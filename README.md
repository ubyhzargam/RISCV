# RISCV basic core - 
I will be implementing this block using Verilog HDL. I won't be implementing all the R-type instructions. I will be just implementing a few instructions and other instructions are implmented in the same way. 
![WhatsApp Image 2024-11-18 at 22 35 06](https://github.com/user-attachments/assets/3633f2df-be18-4ac4-bb77-2cb16d79c519)






# I will be synthesizing the codes below and estimating the area of each block using Yosys 

# 1. Program counter -
<br>
Generic Netlist : 
<img width="1470" alt="Screenshot 2024-11-17 at 4 55 12 PM" src="https://github.com/user-attachments/assets/f5ec38dc-6f0e-4772-b14b-2b3abc0b2b12">
<br>
Technology mapped netlist (Using 45 nm pdk of typical process) :
<img width="282" alt="Screenshot 2024-11-21 at 10 39 50 PM" src="https://github.com/user-attachments/assets/467a060f-557a-4474-a4e1-c17c02e7792b">
<br>
<br>
The area estimated using the information provided in the pdk is - 
<br>
<img width="472" alt="Screenshot 2024-11-21 at 10 40 28 PM" src="https://github.com/user-attachments/assets/a0666ed9-2bc5-43d6-b002-0fc2ceb26c60">

<br><br>

# 2. PC_adder -
<br>
Generic Netlist : 
<img width="1470" alt="Screenshot 2024-11-17 at 5 08 56 PM" src="https://github.com/user-attachments/assets/b930fe2a-0ed1-4f19-80ea-be5c7d02d07f">
<br>
Technology mapped netlist (Using 45 nm pdk of typical process) :
<br>
<img width="943" alt="Screenshot 2024-11-21 at 10 41 30 PM" src="https://github.com/user-attachments/assets/d4d8efe0-b37c-4f18-b1fa-8c26286be555">
<br>
The area estimated using the information provided in the pdk is - 
<br>
<img width="494" alt="Screenshot 2024-11-21 at 10 42 03 PM" src="https://github.com/user-attachments/assets/c1796624-db90-45c0-acd1-e29d63e1421c">


<br><br>

# 3. MUX -

<br>
Generic Netlist : 
<img width="1470" alt="Screenshot 2024-11-17 at 5 18 27 PM" src="https://github.com/user-attachments/assets/376ae3cc-ffa0-44ae-bde0-78e2e31588ab">
<br>
Technology mapped netlist (Using 45 nm pdk of typical process) :
<br>
<img width="131" alt="Screenshot 2024-11-21 at 10 42 51 PM" src="https://github.com/user-attachments/assets/e8ca1e53-4625-4672-833c-48b892298139">

<br>
The area estimated using the information provided in the pdk is - 
<br>
<img width="438" alt="Screenshot 2024-11-21 at 10 43 15 PM" src="https://github.com/user-attachments/assets/f000a697-586b-4cc7-b22b-595ed71e644f">

<br><br>

# 4. Main decoder - 
<br>
Generic Netlist : 
<img width="568" alt="Screenshot 2024-11-17 at 5 31 49 PM" src="https://github.com/user-attachments/assets/aedd4738-757f-4853-9440-a21e99c61c0d">
<br>
Technology mapped netlist (Using 45 nm pdk of typical process) :
<br>
<img width="1051" alt="Screenshot 2024-11-21 at 10 43 49 PM" src="https://github.com/user-attachments/assets/8da7d415-a70e-4fec-a14b-778273aa085e">
<br>
The area estimated using the information provided in the pdk is - 
<br>
<img width="440" alt="Screenshot 2024-11-21 at 10 44 12 PM" src="https://github.com/user-attachments/assets/d06a5623-f187-4867-bb8a-1f819beef42f">
<br><br>

# 5. ALU decoder -
<br>
Generic Netlist : 
<img width="1178" alt="Screenshot 2024-11-17 at 5 39 00 PM" src="https://github.com/user-attachments/assets/b4c604b9-0e71-4440-a799-a50e5e5e178a">
<br>
Technology mapped netlist (Using 45 nm pdk of typical process) :
<br>
<img width="1462" alt="Screenshot 2024-11-21 at 10 46 35 PM" src="https://github.com/user-attachments/assets/6a61d96a-1b68-4aa3-a9e4-6558e3b09ca2">


<br>
The area estimated using the information provided in the pdk is - 
<br>
<img width="509" alt="Screenshot 2024-11-21 at 10 46 54 PM" src="https://github.com/user-attachments/assets/b29cb53f-c8c0-4c1a-a737-10ec6966946a">

<br><br>

# 6. Register file -
<br>
Generic Netlist : 
<img width="869" alt="Screenshot 2024-11-17 at 5 47 32 PM" src="https://github.com/user-attachments/assets/3aa90b17-a4f1-4023-8cb3-2ee0731d76ac">
<br>
Technology mapped netlist (Using 45 nm pdk of typical process) :
<br>
<img width="36" alt="Screenshot 2024-11-17 at 5 49 06 PM" src="https://github.com/user-attachments/assets/d2b97bc7-86e6-42a8-a70f-2dab68691ff8">
<br>
The area estimated using the information provided in the pdk is - 
<br>
<img width="461" alt="Screenshot 2024-11-17 at 5 49 54 PM" src="https://github.com/user-attachments/assets/6c8d61e6-26de-4f16-9855-d9a5260e2d1c">
<br><br>

# 7. Sign extend -
<br>
Generic Netlist : 
<img width="1462" alt="Screenshot 2024-11-17 at 5 53 02 PM" src="https://github.com/user-attachments/assets/362b26da-7cb8-4816-a725-0575226f686f">
<br>
Technology mapped netlist (Using 45 nm pdk of typical process) :
<br>
<img width="352" alt="Screenshot 2024-11-21 at 10 48 22 PM" src="https://github.com/user-attachments/assets/58795d2a-5033-4879-82c2-858edba3b040">

<br>
The area estimated using the information provided in the pdk is - 
<br>
<img width="437" alt="Screenshot 2024-11-21 at 10 48 39 PM" src="https://github.com/user-attachments/assets/d2948943-815c-47e9-b491-227fbda81583">

<br><br>

# 8. ALU - 
<br>
Generic Netlist : 
<img width="1470" alt="Screenshot 2024-11-17 at 5 59 34 PM" src="https://github.com/user-attachments/assets/06662754-0229-4a90-b456-a34e874d0d96">
<br>
Technology mapped netlist (Using 45 nm pdk of typical process) :
<br>
<img width="815" alt="Screenshot 2024-11-21 at 10 45 10 PM" src="https://github.com/user-attachments/assets/a265bad5-7ac7-4826-8e05-434e86f7e37a">
<br>
The area estimated using the information provided in the pdk is - 
<br>
<img width="479" alt="Screenshot 2024-11-21 at 10 45 55 PM" src="https://github.com/user-attachments/assets/08b6ddbd-69d1-45c7-a0d7-a355a958c3c1">

<br><br>




