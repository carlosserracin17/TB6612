# Proyecto:  TB6612FNG DC MOTOR DRIVER Repo.

En este proyecto presentaremos el diseño de un driver, especificamente el Dual Motor Driver TB6612FNG, el cual es mucho más eficiente que los antiguos controladores basados en puente H bjt,como el L298N, pero ya veremos por qué.
Comenzaremos exponiendo su funcionalidad.

## Funcionalidad y caracteristicas
- Este driver o controlador es una completa etapa de potencia MOSFET capaz de controlar dos motores DC de hasta 1A, pudiendo entregar hasta 3A de pico. 
- Voltaje de funcionamiento de VCC: 2.7V ~ 5.5V
- Potencia de entrada de VM: 2.5V ~ 12V
- Canales conductores: 2 canales
- Corriente de salida: 1.2A (corriente de accionamiento continuo de un solo canal)
- Está compuesto por dos etapas MOSFET en H y permite controlar de forma indivisual tanto la dirección de giro como la velocidad mediante PWM. 
- Acepta frecuencia de hasta 100 KHz.
- También dispone de un pin STANDBY para poder desactivar el driver si se necesita.
- Circuito de apagado térmico incorporado
- Condensadores de filtrado en ambas líneas de suministro
- Protección de potencia inversa en el suministro del motor
- Dimensión: 1.57x1.57 (in) / 40 × 40 (mm)

![](https://raw.githubusercontent.com/DFRobot/DFRobotMediaWikiImage/master/Image/_DRI0044-A_Dual_Motor_Driver_TB6612.png)

## Resultados
![image](https://user-images.githubusercontent.com/66341655/84214866-418a1a80-aa8a-11ea-9388-bc87a698e554.png)
