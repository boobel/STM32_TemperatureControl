# **STM32_TemperatureControl**

This is a simple project for temperature control with discrete PID implementation in a STM32F476ZG Microprocessor.
The general aim of this project is for the PID regulator to reacg a goal temperature with upto 5% maximum oscillations in steady state.

A PWM signal is used to control a NPN transistor that operates in common emitter configuration, which in turn, relays adequate voltage onto a thermistor, it's quite a simple circuit.


