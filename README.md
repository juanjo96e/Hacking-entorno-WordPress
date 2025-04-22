# Laboratorio de Explotación en WordPress

Este laboratorio consiste en realizar un ataque en un entorno WordPress para obtener acceso a una máquina víctima mediante diversas técnicas de explotación. El objetivo es practicar el uso de herramientas como `nmap`, `wpscan`, y `msfvenom`, así como técnicas de inyección de código malicioso y de fuerza bruta.

---

## Objetivos

- **Identificar vulnerabilidades** en un entorno WordPress.
- Realizar un **ataque de fuerza bruta** para obtener credenciales.
- Usar **msfvenom** para generar un payload y conseguir acceso a la máquina víctima.
- Mejorar la conexión obtenida mediante **netcat** y estabilizarla.

---

## Herramientas utilizadas

- **nmap**: Para escanear puertos y detectar vulnerabilidades.
- **wpscan**: Para buscar usuarios y realizar ataques de fuerza bruta.
- **msfvenom**: Para generar un payload malicioso.
- **netcat**: Para establecer una conexión estable con la máquina víctima.

---

## Pasos realizados

1. **Conexión a la máquina víctima**  
   Se realizó la conexión inicial utilizando herramientas de escaneo.

2. **Exploración de directorios**  
   Se usó *fuzzing* para buscar directorios vulnerables, como `wp-login.php` y `/blog`.

3. **Uso de `wpscan`**  
   Se identificaron usuarios y se realizó un ataque de fuerza bruta.

4. **Generación de Payload**  
   Con `msfvenom`, se generó un payload para ser inyectado en el sitio WordPress.

5. **Establecimiento de conexión estable**  
   Se utilizó `netcat` para mejorar la conexión a la máquina víctima y asegurarse de que fuera estable.

6. **Inyección de código malicioso**  
   Se inyectó el payload en el archivo de footer de WordPress a través del editor de temas.

---

## Preparación para el examen eJPT

Este laboratorio ha sido realizado por **Juan Técnico Superior en ASIR**, con el fin de preparar el examen **eJPT (eLearnSecurity Junior Penetration Tester)**.

---

### Notas adicionales

> **Recuerda siempre realizar estos ataques en entornos controlados y con permisos.**  
Este laboratorio está diseñado para ser realizado en plataformas como **TryHackMe**, que proporcionan un entorno seguro y legal para practicar.
