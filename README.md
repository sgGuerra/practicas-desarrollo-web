# 📚 Fundamentos de la Web - Notas de Estudio

**Fecha:** 05/02/2026

---

## 🌐 Conceptos Básicos

### Host
Un **host** es cualquier dispositivo conectado a Internet que contiene una dirección IP. Esta dirección IP ayuda a identificar de manera única ese dispositivo en la red.

**Ejemplos de hosts:**
- Computadoras personales
- Servidores web
- Dispositivos móviles
- Routers y switches

---

### WWW (World Wide Web)
El **WWW** es un sistema de documentos interconectados que se acceden a través de Internet. Fue inventado por Tim Berners-Lee en 1989 y utiliza protocolos como HTTP/HTTPS para la transferencia de información.

**Características principales:**
- Sistema de hipertexto
- Accesible mediante navegadores web
- Documentos conectados mediante enlaces

---

### URL (Uniform Resource Locator)
Una **URL** es un identificador más legible que nos envía siempre a un recurso específico en la web. Es la dirección que escribimos en el navegador para acceder a una página web.

**Ejemplo de URL:**
´´´
https://www.ejemplo.com:443/ruta/pagina.html?param1=valor1&param2=valor2#seccion
´´´


---

### HTTPS (HyperText Transfer Protocol Secure)
**HTTPS** es una versión segura del protocolo HTTP que utiliza un certificado de seguridad SSL/TLS. Lo que hace es cifrar la información que viaja a través de este protocolo, protegiendo los datos del usuario contra interceptaciones y ataques.

**Ventajas de HTTPS:**
- ✅ Cifrado de datos
- ✅ Autenticación del servidor
- ✅ Integridad de la información
- ✅ Mejor posicionamiento en buscadores

---

## 🔗 Componentes de una URL

Una URL está compuesta por varios elementos:
´´´
protocolo://subdominio.dominio-nivel-secundario.dominio-de-nivel-superior:puerto/ruta?parametros#fragmento
´´´

### Estructura detallada:

1. **Protocolo**: Indica cómo se debe acceder al recurso (http, https, ftp, etc.)
2. **Subdominio**: Parte opcional antes del dominio principal (www, blog, api, etc.)
3. **Dominio de nivel secundario (Second Level Domain)**: Nombre principal del sitio
4. **Dominio de nivel superior (Top Level Domain)**: Extensión (.com, .org, .net, .es, etc.)
5. **Puerto**: Número de puerto (opcional, por defecto 80 para HTTP, 443 para HTTPS)
6. **Ruta**: Ubicación específica del recurso en el servidor
7. **Parámetros**: Información adicional denotada por el signo `?`
   - Los parámetros se separan con `&`
   - Formato: `clave=valor`
8. **Fragmento**: Sección específica de la página, denotada por `#`

### Ejemplo práctico:


- Protocolo: `https`
- Subdominio: `www`
- Dominio nivel secundario: `tienda`
- Dominio nivel superior: `com`
- Puerto: `443`
- Ruta: `/productos/camisetas`
- Parámetros: `color=rojo&talla=M`
- Fragmento: `ofertas`

---

## 🛠️ Práctica #1: Primera Página Web

### Objetivo
Crear tu primera página web básica utilizando HTML.

### Estructura básica recomendada:

```html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Primera Página Web</title>
</head>
<body>
    <h1>Título Principal de la Página</h1>
    <p>Este es mi primer párrafo de contenido.</p>
</body>
</html>





