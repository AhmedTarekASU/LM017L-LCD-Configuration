# LM017L-LCD-Configuration
Must #include <util/delay.h> . 
connect PORTA PIN0 to RS pin on LCD,
connect PORTA PIN1 to RW pin on LCD,
connect PORTA PIN2 to  E pin on LCD,
connect PORTA PINs 4,5,6,7 to Pins DB 4,5,6,7 on LCD ,
if you want to change to any port: edit .c file ,
in main function -> lcd_init();
in while(1) loop -> lcd_gotoxy(1,1); lcd_print("YOURSTRING");
