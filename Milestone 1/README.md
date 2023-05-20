# Milestone 1: STM32 Familiarization

## Group Members:
1. Muhammad Uwais Bin Azman (A19EE0432)
2. Izzat Bukhari Bin Zulkefle (A19EE0339)
3. Muhammad Harith Wafi Bin Mohd Rosman (A19EE0375)

## Instruction
1. Make the stm32 blink
2. Record a video
3. In github, report the steps to make the blinky and set a pointer to video
4. Submit the github link

## Steps
1.	Open STM32CubeIDE. Click “Start new STM32 project” and choose STM32f446 in the “Part Number Search” as the microcontroller.
2.	Give the project name as intended (Blink).
3.	Let the “Pinout & Configuration” and “Clock Configuration” as default settings
4.	Click on file>save. 
5.	Click “Yes” when being prompt to generate Code. The IDE will then automatically generate files.
6.	In the “while (1)” which is the forever loop, write the codes “HAL_GPIOA_TogglePin(GPIOA, GPIO_PIN_5); HAL_Delay(1000);”
7.	Click project>build project.
8.	When that completes, click run>Debug As>STM32 Application.
9.	When the Debug Configuration tab appears, leave all the settings as default.
10.	Then, click the “Play” button to run the program on the Nucleo board.
