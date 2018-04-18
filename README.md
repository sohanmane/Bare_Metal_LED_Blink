# Bare_Metal_LED_Blink
Blinking an LED on a Bare-metal Raspberry Pi

Compile Using:-

arm-none-eabi-gcc -O2 -mfpu=vfp -mfloat-abi=hard -march=armv6zk -mtune=arm1176jzf-s -nostartfiles blinky.c -o kernel.elf

arm-none-eabi-objcopy kernel.elf -O binary kernel.img

