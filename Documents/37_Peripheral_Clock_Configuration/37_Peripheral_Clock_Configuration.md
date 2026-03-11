- In modern MCUs, you must enable its peripheral clock using peripheral clock registers before using a peripheral.
- Peripheral clocks of all peripherals will be disabled to save power
- A peripheral won't respond to your configuration until you enable its peripheral clock
- In STM32 MCUs, peripheral clocks are managed through **RCC** (reset and clock control) registers.

# Enable RCC_APB2 Bus
<img width="291" height="25" alt="image" src="https://github.com/user-attachments/assets/1ba7536a-6d76-4d6e-8863-cd8b3d937994" />
<img width="688" height="262" alt="image" src="https://github.com/user-attachments/assets/52f39e7a-44f8-4a3e-8e36-ede7f2f076d8" />

# Example: Set SCAN (8th bit of ADC_CR1) to high
<img width="343" height="163" alt="image" src="https://github.com/user-attachments/assets/4e172686-f765-481a-9e0d-d4cbada6f3f2" />
<img width="667" height="224" alt="image" src="https://github.com/user-attachments/assets/0252a595-6b84-4ead-bb3b-46baa3196258" />
