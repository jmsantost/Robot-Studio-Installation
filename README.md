# Guía de Instalación de RobotStudio

## 1. Descarga de RobotStudio

1. Ir al sitio oficial de ABB:  
   👉 [Descargar RobotStudio](https://new.abb.com/products/robotics/es/software-y-digital/descargas-de-software)

2. Seleccionar el software **RobotStudio**.

   ![Descarga RobotStudio](https://github.com/user-attachments/assets/c7d2ca2f-5017-419b-8f9d-e9fcf442cf3b)

3. Llenar el formulario con tus datos para iniciar la descarga.

   ![Formulario](https://github.com/user-attachments/assets/75bf66be-f7e4-4a08-a41c-f19085d245d0)

## 2. Instalación del VPN

Mientras se descarga RobotStudio, puedes instalar el VPN para conectarte al servidor de licencias.

1. Ir a 👉 [vpn.espol.edu.ec](https://vpn.espol.edu.ec)  
   Inicia sesión con tus credenciales ESPOL.

   ![Login VPN](https://github.com/user-attachments/assets/a38f6591-eafe-4ad4-b638-9ff7675b2ea4)

2. Haz clic en **Download**.

   ![Descargar VPN](https://github.com/user-attachments/assets/0d8ba164-4bf9-43d8-a3ae-fdd13d40501a)

## 3. Instalación de RobotStudio

1. Ejecuta el archivo `Setup` en la carpeta descargada.

   ![Setup](https://github.com/user-attachments/assets/4e521021-618b-4584-ba03-f61a7b822e20)

2. Elige el idioma e inicia la instalación:

   ![Idioma](https://github.com/user-attachments/assets/7931ee6d-0e09-4f3e-9832-a8b66b3b697c)
   ![Paso](https://github.com/user-attachments/assets/e597e0e0-93e3-4293-86d1-0fc4aa2489eb)
   ![Paso](https://github.com/user-attachments/assets/a4062ca9-0be7-4048-a5bb-7c800514e664)
   ![Paso](https://github.com/user-attachments/assets/a10130ef-d616-4d7d-b63d-2ed043bd582c)
   ![Carpeta instalación](https://github.com/user-attachments/assets/5277a317-783c-4a85-a30f-d499b4b96ca7)

3. Dar clic en **Siguiente** y luego en **Instalar**.

   ![Siguiente](https://github.com/user-attachments/assets/8cd2138f-c50b-4f46-a697-be54c7f7607f)
   ![Instalar](https://github.com/user-attachments/assets/cc374f72-84d6-4a56-a22a-6522a0c9cfcf)

## 4. Instalación del cliente VPN (Cisco)

1. Ejecuta el instalador descargado.

   ![VPN Setup](https://github.com/user-attachments/assets/660edad4-d6f1-48e5-a580-017b066e37c9)
   ![VPN Setup](https://github.com/user-attachments/assets/84ab538e-51b0-4d33-9b89-b28c17c3efd7)

2. Clic en **Instalar**.

   ![Instalación VPN](https://github.com/user-attachments/assets/4939d31f-e592-4741-a54d-a37facab43b5)

3. Busca “Cisco” en el menú de inicio y abre el cliente VPN.

   ![Buscar Cisco](https://github.com/user-attachments/assets/575b99b4-adfa-49d6-911b-d0fca942eed4)

4. Escribe la dirección: `vpn.espol.edu.ec`.

   ![Configurar VPN](https://github.com/user-attachments/assets/aa4024a0-9cc3-466a-94c2-d133231a14fb)

5. Ingresa tus credenciales ESPOL.

   ![Login VPN Cisco](https://github.com/user-attachments/assets/be70961b-0794-4930-b1a1-0d30300d749a)

6. Verifica conexión con el servidor de licencias:  
   Abre una terminal (cmd) y ejecuta:

   ```
   ping 200.126.19.236
   ```

   No debe haber pérdida de paquetes.

   ![Ping](https://github.com/user-attachments/assets/ed52bf41-4314-4a41-9241-777259b89e52)

## 5. Activación de licencia en RobotStudio

1. Abre **RobotStudio**.

2. Selecciona el tipo de licencia: **Servidor de red**.

   ![Tipo de licencia](https://github.com/user-attachments/assets/12796cb2-a906-4e79-a8cc-1f705e680e2a)

3. Ingresa la IP del servidor de licencias: `200.126.19.236`.

   ![Ingresar IP](https://github.com/user-attachments/assets/0196e356-ca0a-4333-9cb3-58e427bda51f)

4. Verifica la licencia:  
   Ve a **Archivo > Opciones > Licencias**.

   ![Verificar licencia](https://github.com/user-attachments/assets/3114a1cb-0dd5-43de-a7de-3ddd7d04e084)

## 6. Instalación de RobotWare y el robot IRB 2600

1. Ve a **Complementos > RobotWare para IRC5**.

2. En el panel izquierdo, selecciona la versión `6.11.01` y haz clic en **Añadir**.

   ![RobotWare](https://github.com/user-attachments/assets/6b58c872-e845-471c-9484-570bd1ed33e8)

3. Luego, ve a **Modelo de RobotStudio** y selecciona:  
   `IRB 2600 12 kg 1.65 m (versión estándar, no tipo C)`.

   ![Modelo IRB 2600](https://github.com/user-attachments/assets/ad855e64-d9ad-4f0f-8bed-6ca96bba5ce1)

4. Reinicia el programa si es solicitado.

## 7. Crear un nuevo proyecto

1. Ve a **Archivo > Nuevo**.

2. Asegúrate de configurar:

   - **RobotWare:** 6.11.01  
   - **Modelo del robot:** IRB 2600 12 kg 1.65 m (versión estándar)

   ![Nuevo proyecto](https://github.com/user-attachments/assets/f4dcdcb1-db13-41dd-bffe-f3beb6e03c04)

---

¡Listo! Ahora puedes comenzar a trabajar con **RobotStudio**. Si tienes dudas, consulta al equipo técnico o tutor del curso.
