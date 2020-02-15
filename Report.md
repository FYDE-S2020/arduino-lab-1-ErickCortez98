Name: Erick I. Cortez Valdez

EID: eic366

Team Number: 14

## Questions

1. Why does your program need a setup and a loop?

    In an embedded system the setup is code executed only once and on it we configure the input/output pins. While the in loop the actual behavior of  
    the system is determined and of course it needs to be executed continuously because and embedded system is always running when connected to power. 

2. What is the downside to putting all your code in a loop?

   Probably we would have some level of inefficiency in regards to execution time.   

3. Why does your code need to be compiled?

   In need to be converted from the high level language we are using, in this case C++ into a lower language, like binary, so that finally the program is
   converted to machine code for machine execution. 

4. When lowering the frequency in procedure A, step 4, what is going wrong? Brainstorm some solutions. Dimmers exist in the real world. What is their solution?

    When we lower the frequency it is easier to visualize the change in duty cycles. Having a high frequency makes it harder for us to distinguish the duty cycles
    changes. 

5. Why do you need to connect the logic analyzer ground to the ESP32 ground?

   All the signals that are coming out of the board need of course a ground to complete the ciruit. 

6. What is the difference between synchronous and asynchronous communication?

    In synchronous communication we having parties that are sending signals/messages using the same clock, while on asynchronous communication there is no clock,
    so the parties have to agree on a common data transfer speed. 

7. Profile of UART: Sent X bytes in Y time 

    4 bytes in 5.52ms

8. Profile of SPI: Sent X bytes in Y time

    4 bytes in 3.32ms

9. Why is SPI so much faster than UART?

    Due to the master-slave method

10. list one pro and one con of UART

    Pro: No clock needed
    Con: Speed

11. list one pro and one con of SPI

    Pro: Cost
    Con: More pins needed

12. list one pro and one con of I2C

    Pro: Multiple masters
    Cons: More space due to resistor

13. Why does I2C need external resistors to work?

    To connect a power supply so that when the bus is idle, the lines are on high power. 

## Screenshots

Procedure A, step 1:
(img/Lab 1 Image 1.png)

Procedure A, step 4:
(img/Lab 1 Image 2.png)

Procedure B, UART:
(img/Lab 1 Image 3.png)

Procedure B, SPI:
(img/Lab 1 Image 4.png)
