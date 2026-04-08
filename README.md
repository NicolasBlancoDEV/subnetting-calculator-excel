# Calculadora de Subnetting IPv4 - Excel

Herramienta desarrollada durante el curso **Introducción al Hacking** de **Savitar Academy (Hack4u)**.

Este archivo de Excel permite calcular de forma automática y rápida todo lo relacionado con **subnetting** en redes IPv4.

### Funcionalidades
- Calcula la cantidad de hosts totales y utilizables
- Muestra dirección de red y broadcast
- Indica el rango de IPs utilizables
- Convierte entre notación CIDR y máscara decimal
- Muestra Wildcard mask

**Ejemplo:**  
Al ingresar `192.168.1.0/26` calcula automáticamente:
- Hosts: 64 (62 utilizables)
- Rango usable: 192.168.1.1 - 192.168.1.62
- Broadcast: 192.168.1.63
- Máscara: 255.255.255.192 (/26)

### Objetivo
Practicar y automatizar los cálculos de subnetting vistos en el curso, para tener una herramienta rápida de consulta y reforzar el entendimiento de CIDR y división de redes.

---

Hecho mientras aprendo Ethical Hacking 🛡️

<img width="924" height="765" alt="Captura de pantalla 2026-04-08 071843" src="https://github.com/user-attachments/assets/c5f63dcf-85f9-46f5-8400-c5bca3612bf9" />

## Vista previa del Calculador de Subnetting

![Calculadora de Subnetting en Excel](Subnetting_Calculator.png)

*Ejemplo mostrando el cálculo para la red 192.168.1.0/26*

