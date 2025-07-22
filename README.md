# BITWISE-OPERATORS-

AIM : To study and implement C++ Bitwise Operators

SOFTWARE USED : VS CODE

THEORY : This C++ program demonstrates how to set and reset a specific bit in a given integer using bitwise operations. It takes an integer and a bit position as input from the user. Bits are the binary representation of numbers, and modifying them allows low-level data control. To set a bit (i.e., change it to 1), the program uses the bitwise OR (|) operator with a mask created by left-shifting 1 by the given bit position (1 << bitPosition). This operation ensures only the target bit is set, while others remain unchanged. To reset a bit (i.e., change it to 0), it uses the bitwise AND (&) operator along with the NOT (~) operator to invert the bit mask, ensuring that only the desired bit is cleared. The resulting values after setting and resetting the specified bit are then displayed, helping users understand basic bit manipulation techniques.

Algorithm : 

1. Start

2. Input an integer number from the user.

3. Input the bit position to modify (starting from 0).

4. Calculate the value after setting the bit:

5. Use number | (1 << bitPosition)

6. Display the result after setting the bit.

7. Calculate the value after resetting the bit:

8. Use number & ~(1 << bitPosition)

9. Display the result after resetting the bit.

10. End



