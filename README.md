# Waveshare Raspberry Pi Pico to Raspberry Pi HAT Adapter with TXCO

adapter to convert a waveshare raspberry pi pico lora to a raspberry pi Hat

The Raspberry Pi Pico LoRa has a SX1262 with TXCO whilst the other Waveshare SX126X XXXM does not

![image](https://github.com/user-attachments/assets/ed21061a-646f-4507-8dd1-c7edfd3f9145)


Top
![simulation_image_top](https://github.com/user-attachments/assets/eab25df1-5826-4c83-b44f-7c286ca545f9)

Bottom
![simulation_image_bottom](https://github.com/user-attachments/assets/9b553a82-cf21-410d-ad73-a747bae25e82)

Add female 40 pin GPIO Header and two male 20 pin Headers like this




lora-ws-raspberry-pi-pico-to-rpi-adapter.yaml
```
# https://www.waveshare.com/pico-lora-sx1262-868m.htm
Lora:
  Module: sx1262  # Waveshare Raspberry Pi Pico to Raspberry Pi HAT Adapter
  DIO2_AS_RF_SWITCH: true
  DIO3_TCXO_VOLTAGE: true
  CS: 21
  IRQ: 16
  Busy: 20
  Reset: 18
```
# **JLBPCB Gerber view (online**
https://jlcpcb.com/RGE

# **DISCLAIMER**

# Use of these GERBER, BOM and CPL are at your own risk

Support my work and considder **buying  me a coffee**

https://buymeacoffee.com/mark.birss


  


