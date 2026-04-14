# Taller de autenticación en Flutter

Proyecto frontend desarrollado en Flutter que implementa un flujo completo de autenticación con pantallas de inicio de sesión, registro y recuperación de contraseña.

El diseño es responsivo, minimalista y utiliza una interfaz en blanco y negro.

---

## Flujo de pantallas

### Desde iniciar sesión

**Iniciar sesión → Registrarse**  
Crear una nueva cuenta.

**Iniciar sesión → Olvidé mi contraseña**  
Recuperar contraseña.

### Desde registro

**Registrarse → Iniciar sesión**  
Redirección al inicio de sesión después de registrarse.

### Desde recuperación de contraseña

**Olvidé mi contraseña → Iniciar sesión**  
Retorno al inicio de sesión después de enviar el enlace.

---

## Capturas de pantalla

### Pantalla de login
Pantalla de inicio de sesión

![Login](assets/images/login.png)

---

### Pantalla de registro
Pantalla de registro

![Registro](assets/images/register.png)

---

### Pantalla de recuperación de contraseña
Has olvidado tu contraseña

![Recuperación](assets/images/forgot.png)

---

## Cómo ejecutar el proyecto

```bash
git clone https://github.com/LiyhetRodriguez/TALLER-V2.git
cd TALLER-V2
flutter pub get
flutter run
