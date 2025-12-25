🏠 Proyecto: Sistema de Domótica con ESP32 y Red Mesh

#Microcontrolador esp32
#Microservidor de logs - Microcontrolador ATmega 328p

El proyecto tiene como objetivo controlar y monitorear distintos componentes domóticos (iluminación, sensores y actuadores) sin depender de un nodo central fijo. Cada ESP32 actúa como un nodo inteligente, capaz de enviar, recibir y retransmitir mensajes dentro de la red mesh, garantizando la continuidad de la comunicación incluso si uno o más nodos dejan de funcionar.

A nivel técnico, el sistema fue desarrollado utilizando el ESP-IDF, haciendo uso de tareas de FreeRTOS, comunicación inalámbrica Wi-Fi en modo mesh, manejo de interrupciones, temporizadores y comunicación serial para depuración. El código está estructurado de forma modular para facilitar la escalabilidad, permitiendo agregar nuevos nodos o dispositivos sin afectar el funcionamiento general del sistema.

####
#####
###### Todo el diseño fue realizado en altium designer

#Esquematico del BSwitch

<img width="1384" height="913" alt="Esquematico" src="https://github.com/user-attachments/assets/6dfa7ec5-64be-4418-9648-42fe4d7a1bf4" />

#Diseño PCB Bswitch para TH

<img width="634" height="919" alt="image" src="https://github.com/user-attachments/assets/ac1808c1-74d0-4c16-a299-e97fb2009d49" />

#Diseño PCB Bswitch para SMD

<img width="632" height="916" alt="image" src="https://github.com/user-attachments/assets/808d1d1d-08bd-426a-8b07-606ebcdd302d" />

#Esquematico del Cerebro del sistema bautizado como DCPO

<img width="1371" height="907" alt="image" src="https://github.com/user-attachments/assets/fc1a105f-0a36-47ea-a97a-aee32bd4f42e" />

#Diseño PCB DCPO

<img width="1316" height="722" alt="image" src="https://github.com/user-attachments/assets/8db11464-d17d-4bda-bb00-cf975e85346e" />
