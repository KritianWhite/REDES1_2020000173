#
REDES DE COMPUTADORAS 1 \
ING. PEDRO HERNANDEZ \
AUX. MELANI LOPEZ 

CHRISTIAN ALESSANDER BLANCO GONZALEZ \
202000173

#
<center> <h1>PRACTICA 1</h1> </center>
<br><br>

## CONFIGURACIÓN DE VPCs
1. VPC del computador para el administrador.

    ![alt text](./src/vpc-administrador.png)

2. VPC del área gerencial.

    ![alt text](./src/vpc-gerencia.png)

3. VPC del área de atención al cliente.

    ![alt text](./src/vpc-atencion-cliente.png)

4. VPC del área de recursos humanos.

    ![alt text](./src/vpc-recursos-humanos.png)

5. VPC de la oficina A.

    ![alt text](./src/vpc-oficina-a.png)

6. VPC de la oficina B.

    ![alt text](./src/vpc-oficina-b.png)

7. VPC de la oficina C.

    ![alt text](./src/vpc-oficina-c.png)

## PING ENTRE HOSTS

1. Realizaremos la comunicación de la máquina del administrador (192.168.73.101) hacia la segunda máquina de la oficina A (192.168.73.202).

    ![alt text](./src/ping-administrador-oficina-a.png)

2. Realizaremos la comunicación de la tercera máquina de recursos humanos (192.168.73.108) hacia la máquina del gerente (192.168.73.102).

    ![alt text](./src/ping-recursos-humanos-gerencia.png)

3. Realizaremos la comunicación de la cuarta máquina de la oficina B (192.168.73.207) hacia la segunda máquina de atención al cliente (192.168.73.105).

    ![alt text](./src/ping-oficina-c-atencion-cliente.png)

## PAQUETE ARP/ICMP

A continuación se estará mostrando lo que es el paquete ICMP de la máquina administrador hacia la segunda máquina de la oficina A:

1. Enviando paquete:

    ![alt text](./src/icmp-enviando.png)

2. Recibiendo paquete:

    ![alt text](./src/icmp-recibido.png)

3. Regresando paquete:

    ![alt text](./src/icmp-regreso.png)

4. Ping exitoso:

    ![alt text](./src/icmp-exito.png)

    ![alt text](./src/icmp-tabla.png)

## ANEXOS

En esta prácita se realizó un boceto en formato svg para poder entender el diagrama de dicha tipología de la red, tanto del primer y segundo nivel, conectandolos también a su respectivo switch e identificando cada máquina en su área respectiva:

![alt text](./src/Diagrama-boceto-topología-red.svg)
