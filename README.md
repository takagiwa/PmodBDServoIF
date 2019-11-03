# PmodBDServoIF

Pmod BiDirectional Servo motor Interface

----

This is a Servo motor interface Pmod project.

----

# Variation

## single ended and half duplex

target: ICS, G15 Cube Servo

### For HV/MV

standard type.

One 2pin power connector.

One regulator for level converter (5V).

### No power supply

monitor and control. don't supply power to servo.

One USB Micro B connector supply power to level converter.

if possible, make same PCB with HV/MV.

### For MV

One 2pin power connector.

Two regulator for level converter (5V) and servo (7.2V)

This may use with HV/MV and same power supply.

## single ended and full duplex (future plan)

target: V-SERVO

## differential and half duplex (future plan)

target: Command Type Servo, Smart Actuator Module

# References

## Digilent

- [Pmod Standard](https://reference.digilentinc.com/reference/pmod/specification)

## Kondo Kagaku

- [ICS変換基板](https://kondo-robot.com/product/03121)
- [テクニカルガイド](https://kondo-robot.com/archives/faq_category/tecguide)
- [ICS3.6と3.5の違いと新機能についての紹介](https://kondo-robot.com/faq/ics3_6function)
- [シリアルサーボ制御方法（１）　回路編](https://kondo-robot.com/faq/serial-servo-method-tech)




