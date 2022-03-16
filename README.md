# Practical-3
Practical 3
#define STM32F051
#include "stm32f0xx.h"
#include "lcd_stm32f0.h"
#include <string.h>
#include<stdio.h>

struct age_data
{
            uint8_t date;
            uint8_t month;
            uint16_t year;
            uint8_t age;
}my age;


void main(void)
{

/ my_age function /

my_age.date  = 10;
my_age.month = 05;
my_age.year  = 2000;
my_age.age = 21;

/ number of iterations to get to age/

init_LCD();

while(1)




       char str[1];
       for (uint8_t n=0; n<=myage.age; n++)
         {
               sprintf(str, "%d", n);
               lcd_putstring(str);
               delay(500000);

               lcd_command(CLEAR);
          }
}
}
