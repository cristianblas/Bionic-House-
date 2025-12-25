🏠 Proyecto: Sistema de Domótica con ESP32 y Red Mesh

#Microcontrolador esp32
#Microservidor de logs - Microcontrolador ATmega 328p

El proyecto tiene como objetivo controlar y monitorear distintos componentes domóticos (iluminación, sensores y actuadores) sin depender de un nodo central fijo. Cada ESP32 actúa como un nodo inteligente, capaz de enviar, recibir y retransmitir mensajes dentro de la red mesh, garantizando la continuidad de la comunicación incluso si uno o más nodos dejan de funcionar.

A nivel técnico, el sistema fue desarrollado utilizando el ESP-IDF, haciendo uso de tareas de FreeRTOS, comunicación inalámbrica Wi-Fi en modo mesh, manejo de interrupciones, temporizadores y comunicación serial para depuración. El código está estructurado de forma modular para facilitar la escalabilidad, permitiendo agregar nuevos nodos o dispositivos sin afectar el funcionamiento general del sistema.

#Diseño PCB Bswitch
<img width="634" height="919" alt="image" src="https://github.com/user-attachments/assets/ac1808c1-74d0-4c16-a299-e97fb2009d49" />

