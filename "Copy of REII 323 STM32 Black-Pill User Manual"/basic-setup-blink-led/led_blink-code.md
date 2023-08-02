---
description: In this section the code will be written to taggle the LED to make it blink
---

# 👨💻 LED\_BLINK Code

1. Open the "**main.c**" file located under "**LED\_BLINK->Core->Src->main.c**".
2.  In this file, there is already code provided. The LED\_BLINK code will be written in the "**while (1)**" loop located around line\_95 as shown below.

    <figure><img src="../.gitbook/assets/2. while loop.png" alt=""><figcaption></figcaption></figure>
3. Write the code between the defined space, otherwise, it will be deleted when changes are made to the configuration.
4. When unsure of a function/ command press "**ctrl + space**" for a list of possible commands.
5.  The figure shown below is the finished "**while (1)**" loop as needed to toggle the LED every 1 second. Below the figure are the finished "**while (1)**" loop in code format.

    <figure><img src="../.gitbook/assets/2. finished while loop.png" alt=""><figcaption></figcaption></figure>

```c
  /* Infinite loop */
  /* USER CODE BEGIN WHILE */
  while (1)
  {
    HAL_GPIO_TogglePin(Onboard_LED_GPIO_Port, Onboard_LED_Pin);		//First parameter is the Port, and the second is the pin
    HAL_Delay(1000);		//Delay in mili-seconds
    /* USER CODE END WHILE */

    /* USER CODE BEGIN 3 */
  }
  /* USER CODE END 3 */
```

6.  Next, the code needs to be built. To build the code, press the following icon -> ![](<../.gitbook/assets/Code Builder.png>). From the "**Console Output**" shown below, it can be seen that the build has finished and that there are zero errors and also zero warnings.

    <figure><img src="../.gitbook/assets/2. Console Output.png" alt=""><figcaption></figcaption></figure>
7. In the [connecting-the-debugger-programmer-to-the-stm32f411-black-pill.md](connecting-the-debugger-programmer-to-the-stm32f411-black-pill.md "mention") section, the ST-Link V2 will be connected to the STM32F411 Black\_Pill to get ready to upload the first program to the STM32F411.
