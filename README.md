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

