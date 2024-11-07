# UART-Utility

A package to directly send and execute commands from the terminal to MPU via UART link. I used STM32MP157f-DK2, but you can try any other MPU. If you want to run a series of commands in the MPU, don't have Tera Term, and don't want to get into the fuss of cross-compiling every time before sending any command, here's a one-stop solution. Using a UART cable and setting the baud rate like Tera Term, you can pass commands to the MPU. 

Very helpful in testing as you can send a command hundreds of times just by entering the count and the command. Initially, I wrote the code in C, where I had set all the UART flags. Now I have made it a Python module so that all you need to do is import `UARTInterface`. You can always use Minicom to check if the command was transferred and executed. I have attached an example code for your reference and the required files in a separate folder.

![image (1)](https://github.com/user-attachments/assets/034faa1f-e999-4134-a75f-7667cd3e31e8)
![image (2)](https://github.com/user-attachments/assets/b4bf6a2b-4717-4ca8-80ba-4881a8d89203)
![image (3)](https://github.com/user-attachments/assets/5ddd56d0-9bd9-4718-a154-98b880341506)
