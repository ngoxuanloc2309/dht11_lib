To use this library. First of all, add two files in your projects then in main.c: 
- include "dht11.h"
- STEP TWO:    /* USER CODE BEGIN 0 */

                  logan dht11;

              /* USER CODE END 0 */


- In while loop, code:
    dht11_completed();
		delay_ms(200);

- Observe the changes of temp and hum by selecting "dht11" you declared in step two. 
