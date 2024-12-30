- Name : AMEYA PRASHANT ABHANG
- Company : CODTECH IT SOLUTIONS
- ID : CT08DST
- Domain :  C PROGRAMMING
- Duration :  DECEMBER TO JANUARY 2025
- Mentor : NEELA SANTHOSH KUMAR

![TEMPERATURE CONVERTER - 1](https://github.com/user-attachments/assets/129c3e20-e4c2-42fd-9b40-354f41790b4e)
![TEMPERATURE CONVERTER - 2](https://github.com/user-attachments/assets/9e7a4e06-9b7d-47a4-8a5f-21f8a0f16ffd)

Overview of the Code:
The code is a temperature converter program implemented in C. It provides a menu-driven interface for users to perform temperature conversions between Celsius and Fahrenheit. The program runs in a loop, allowing the user to repeatedly choose an option until they decide to exit.

Key Activities in the Code:
1. Menu Display:
  - The program shows a menu with three options:
  - Convert Celsius to Fahrenheit.
  - Convert Fahrenheit to Celsius.
  - Exit the program.
  - This menu is displayed by the displayMenu function.

2. User Input Handling:
  - The user inputs their choice of operation (1, 2, or 3).
  - If the input does not match any valid option, the program displays an error message and prompts the user again.

3. Celsius to Fahrenheit Conversion:
  - If the user selects option 1:
  - The program asks for a temperature in Celsius.
  - The input is processed by the CelToFah function, which uses the formula:
  - F = (C * (9/5)) + 32
  - The converted temperature in Fahrenheit is displayed.

4. Fahrenheit to Celsius Conversion:
  - If the user selects option 2:
  - The program asks for a temperature in Fahrenheit.
  - The input is processed by the FahToCel function, which uses the formula:
  - C = (F - 32) * (5/9)
  - The converted temperature in Celsius is displayed.

5. Exit Option:
  - If the user selects option 3, the program terminates with a thank-you message.

6. Error Handling:
  - If the user enters an invalid choice, an error message is displayed, and the program continues to prompt the user.

7. Looping Mechanism:
  - The program runs in a do-while loop, ensuring the menu is displayed and operations can be performed repeatedly until the user chooses to exit.

![TEMPERATURE CONVERTER - 3](https://github.com/user-attachments/assets/4d845209-0d3e-4f34-b3da-c9c75daf5c8d)
