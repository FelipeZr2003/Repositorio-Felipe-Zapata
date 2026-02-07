## 📄 Generador de Nómina y Envío por Correo

## 🔍 Descripción

Aplicación web que permite generar colillas de pago en formato PDF a partir de datos almacenados en base de datos y enviarlas automáticamente por correo electrónico al empleado seleccionado.

Este proyecto nace de la necesidad de automatizar el proceso de entrega de nómina, evitando cálculos manuales, errores de digitación y el uso de documentos físicos.

---

## ⚙️ Funcionalidades

- Selección de empleado desde base de datos  
- Visualización de datos del empleado  
- Cálculo automático de valores de nómina  
- Generación de colilla de pago en PDF  
- Inclusión de logo e información de la empresa  
- Envío de colilla al correo del empleado  
- Historial de nóminas generadas  

---

## 🧠 Flujo del sistema

1. El usuario selecciona un empleado  
2. El sistema consulta los datos en la base de datos  
3. Se ingresan los valores variables de la nomina
4. Se genera el PDF con formato profesional  
5. Se guarda el registro en la base de datos  
6. Se envía el correo con el PDF adjunto  

---

## 🛠️ Tecnologías utilizadas

- Next.js  
- React  
- MySQL  
- Prisma ORM  
- Tailwind CSS  
- jsPDF  
- NodeMailer  

---

## 🧾 Estructura general

/app
/api
/nomina
route.ts
/prisma
/schema.prisma
/components


---

## 🧩 Generación del PDF

El sistema utiliza la librería **jsPDF** para construir la colilla de pago dinámicamente:

- Encabezado con logo de la empresa  
- Datos del trabajador  
- Tabla de ingresos y deducciones  
- Totales calculados  
- Pie de página con fecha de emisión  

El diseño se genera por coordenadas, asegurando una distribución clara de la información.

---

## 📧 Envío de correo

Para el envío de correos se utiliza **NodeMailer**:

- Configuración mediante variables de entorno  
- Adjunta el PDF generado  
- Envío automático al correo registrado del empleado  

Esto evita procesos manuales y asegura trazabilidad.

---

## 🔐 Seguridad

- Validación de datos antes de generar PDF  
- Uso de variables de entorno para credenciales  
- Control de errores en generación y envío  

---

## 📈 Posibles mejoras

- Firma digital  
- Envío masivo de nómina  
- Plantillas personalizables   

---

## 📚 Aprendizajes

- Generación de documentos dinámicos  
- Integración backend-frontend  
- Manejo de archivos en memoria  
- Automatización de procesos administrativos  

---

## 📸 Capturas

*(Agregar imágenes de la interfaz y del PDF generado)*

---

### ✅ Resultado

Proyecto enfocado en resolver un problema real de gestión administrativa mediante automatización.
