# Net-Practice
RED-LAN
resumen

![Imagen de WhatsApp 2025-07-11 a las 06 41 59_3d994e88](https://github.com/user-attachments/assets/b09dca03-c3ea-4a2b-ac1a-5e778ad3e3a7)



IP: 192.168.1.73

Máscara: /26 (es decir, 255.255.255.192)

1. Calcula el bloque
Máscara en el octeto variable = 192 Bloque = 256 − 192 = 64

2. Divide 0–255 en tramos de 64
0–63 64–127 128–191 192–255

3. Localiza tu IP
La IP termina en .73 → cae dentro del tramo 64–127

Dirección de red = el inicio del tramo = 192.168.1.64

Broadcast = el final del tramo = 192.168.1.127

4. Obtén los hosts útiles
Todos los valores entre red+1 y broadcast−1:

192.168.1.65 … 192.168.1.126

Eso son 62 direcciones útiles (64 direcciones totales menos red y broadcast).

Resumen

Bloque = 64

Rango de red = 64–127

Red = 192.168.1.64

Broadcast = 192.168.1.127

Hosts útiles = 65…126
