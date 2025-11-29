---

# 🧭 **Ruta práctica AWS Cloud Practitioner — “De cero a infraestructura productiva”**

---

## 🧩 **Etapa 1: Fundamentos + Proyecto 1 “Static Website Deployment”**

**Duración:** ~1 semana
**Objetivo:** Comprender los conceptos base del cloud, la consola, IAM y cómo desplegar contenido globalmente.

### 🔍 Servicios a dominar:

* **IAM** → usuarios, grupos, políticas, roles.
* **S3** → almacenamiento, permisos públicos, versionado, hosting estático.
* **CloudFront** → distribución CDN y HTTPS.
* **Route 53** → dominios y DNS.
* **ACM** → certificados SSL gratuitos.
* **AWS Budgets / Cost Explorer** → alertas de costos y presupuestos.

### 🧠 Laboratorios sugeridos:

1. Crear un **usuario IAM** con permisos limitados para prácticas.
2. Crear un **bucket S3** y subir tu landing page o un React build.
3. Configurar el **hosting estático** y habilitar acceso público.
4. Integrar **CloudFront + ACM** para HTTPS global.
5. Registrar un dominio en **Route 53** y apuntarlo a tu distribución.
6. Crear un **Budget mensual de $10 USD** y configurar alertas.

✅ **Resultado:**
Tu primera web pública y segura en AWS con dominio propio y control de costos.

---

## ⚙️ **Etapa 2: Serverless y APIs — Proyecto 2 “Serverless Task API”**

**Duración:** ~2 semanas
**Objetivo:** Comprender arquitectura serverless, seguridad, autenticación y bases de datos NoSQL.

### 🔍 Servicios a dominar:

* **Lambda** → ejecución sin servidores.
* **API Gateway** → endpoints REST y control de acceso.
* **DynamoDB** → base de datos NoSQL administrada.
* **CloudWatch** → logs, métricas y alarmas.
* **Cognito** → autenticación de usuarios.
* **Secrets Manager** → manejo de credenciales.
* **S3** (opcional) → almacenamiento de imágenes de usuario.

### 🧠 Laboratorios sugeridos:

1. Crear una función **Lambda** con Node.js o Python.
2. Exponerla mediante **API Gateway** con método `GET` y `POST`.
3. Crear una **tabla DynamoDB** para almacenar tareas o usuarios.
4. Conectar la Lambda a DynamoDB (usando SDK).
5. Configurar logs y alarmas básicas en **CloudWatch**.
6. Implementar **Cognito** para registro/login y asociar tokens JWT a tu API.
7. (Opcional) Integrar un **frontend React** que consuma tu API Gateway.

✅ **Resultado:**
Una API completamente serverless, autenticada y monitoreada, lista para escalar globalmente.

---

## 🧠 **Etapa 3: Infraestructura Completa — Proyecto 3 “Microinfraestructura empresarial”**

**Duración:** ~3–4 semanas
**Objetivo:** Crear una arquitectura empresarial moderna y comprender cómo interactúan los servicios core.

### 🔍 Servicios a dominar:

* **VPC** → redes privadas, subredes, NAT, Internet Gateway.
* **EC2** → instancias Linux/Windows, SSH, EBS.
* **RDS** → base de datos relacional administrada (MySQL/PostgreSQL).
* **Elastic Beanstalk** → despliegue automatizado (Laravel o Spring Boot).
* **EFS / S3** → almacenamiento persistente.
* **CloudWatch + SNS** → alertas de rendimiento o caídas.
* **Auto Scaling** → escalado horizontal.
* **CloudFormation** → infraestructura como código.
* **Pricing Calculator** → análisis de costos estimados.

### 🧠 Laboratorios sugeridos:

1. Crear una **VPC** con subredes públicas y privadas.
2. Desplegar una **instancia EC2** dentro de esa VPC.
3. Instalar **MySQL o PostgreSQL** en **RDS** y conectar desde EC2.
4. Subir tu backend (Laravel) a **Elastic Beanstalk**, conectado a RDS.
5. Agregar un bucket **S3** para guardar archivos de usuario.
6. Configurar **EFS** si necesitas almacenamiento compartido entre instancias.
7. Implementar **CloudWatch** para logs y crear una alerta en **SNS** si el CPU > 70%.
8. Automatizar toda la arquitectura con **CloudFormation** (plantilla YAML).
9. Calcular el costo total con **Pricing Calculator**.

✅ **Resultado:**
Infraestructura real de una aplicación web completa en AWS, con seguridad, monitoreo, automatización y control de costos.

---

## 💡 **Etapa 4 (Opcional): Optimización y prácticas de empresa**

**Duración:** ~1–2 semanas adicionales
**Objetivo:** Dominar herramientas de observabilidad, escalabilidad y buenas prácticas.

### 🔍 Servicios y temas:

* **AWS Organizations** → múltiples cuentas (dev, prod).
* **CloudTrail** → auditoría de acciones.
* **WAF** → firewall de aplicaciones web.
* **Auto Scaling + Load Balancer (ALB/NLB)**.
* **AWS Backup** → copias automáticas.
* **Well-Architected Framework** → buenas prácticas de diseño.

---

## 🎯 Resultado final del roadmap

| Competencia                                                   | Proyecto donde se aplica | Nivel |
| ------------------------------------------------------------- | ------------------------ | ----- |
| Infraestructura global, despliegue estático, dominio y costos | Proyecto 1               | 🟢    |
| Seguridad, IAM, serverless y APIs                             | Proyecto 2               | 🟡    |
| Redes privadas, bases de datos, despliegue de apps, monitoreo | Proyecto 3               | 🔴    |
| Buenas prácticas, auditoría y resiliencia                     | Etapa 4                  | 🟣    |
