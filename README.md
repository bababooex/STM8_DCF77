# STM8_DCF77
Universal library for decoding DCF77, allows you to decode timesignal, I haven't succeeded to make it working on real DCF77 yet, only from generator via flipper zero. 

> [!IMPORTANT]
> If you use stm8s103 or similar, you need to set AFR0 option byte to map PC6 and PC7 to timer1 channels in STVP, otherwise it will not detect anything

# What is in repo
- Example code for decoding DCF77 and displaying time on VFD
- Library for decoding DCF77 via TIM1 and TIM4 (TIM1 for edges and TIM4 for spaces)
