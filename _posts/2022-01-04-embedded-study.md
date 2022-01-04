---
title:  "ADC"
excerpt: "ADC, embedded"

categories:
  - embedded

toc : true
toc_sticky : true
toc_label : "Contents"
---

# ADC

ADC : 아날로그를 디지털로, 전압을 측정.

ADC의 전압범위, AVDC (MCU에서 사용하는 전압이 입력전압)를 디지털로 전환해보는걸 장비를 통하여 한다.  

Cortex M4의 분해능(resolution)은 12bit -> $2^{12}$ = 4096 : 분해능은 4096

아날로그 전압의 범위  
AVR : 0~5V  
MCU : 0~3.3V  

ADC를 Sampling 해서 시간에 대한 디지털 값을 읽어온다.  

입력전압이 3.3V, 분해능은 4096,  

분해능이 높다 -> 더 촘촘하게 샘플링 가능

