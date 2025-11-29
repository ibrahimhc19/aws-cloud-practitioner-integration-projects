## 🧩 **Proyecto 1: “Static Website Deployment” (Conceptos básicos y pricing)**

**Objetivo:** Entender la infraestructura global de AWS, los servicios básicos y cómo se cobra.

### Aprenderás:

* Conceptos de **Regiones, Zonas de disponibilidad, Edge locations**.
* Uso de **S3** para hosting estático.
* **CloudFront** para CDN y HTTPS.
* **Route 53** para dominios personalizados.
* **IAM**: usuarios, políticas y roles.
* **Cost Explorer** y **Budgets** para seguimiento de costos.

### Stack:

Frontend (HTML, React, o tu landing de Acuafit) desplegado en **S3 + CloudFront + Route 53**.
Incluye SSL gratis con **ACM**.

💡 *Resultado:* tu primera web profesional totalmente servida desde AWS, segura y con tu dominio.

---

## ⚙️ **Proyecto 2: “Serverless API + Base de datos” (Tecnología y seguridad)**

**Objetivo:** Crear un backend productivo y escalable sin usar servidores directos.

### Aprenderás:

* **Lambda** (código serverless en Node o Python).
* **API Gateway** (gestión y versionado de APIs).
* **DynamoDB** (NoSQL escalable).
* **CloudWatch** (logs y métricas).
* **IAM Roles** para funciones Lambda.
* **AWS Secrets Manager** (manejo de credenciales seguras).
* **AWS Cognito** (autenticación y autorización).

### Ejemplo:

Una API de tareas o de productos que use Lambda + API Gateway + DynamoDB.
Puedes conectar el frontend del Proyecto 1 a esta API.

💡 *Resultado:* backend sin servidores, seguro, con autenticación, y monitoreado.

---

## 🧠 **Proyecto 3: “Microinfraestructura empresarial” (Integración total + billing avanzado)**

**Objetivo:** Integrar todo lo aprendido en una infraestructura tipo SaaS mínima.

### Aprenderás:

* **EC2** (máquinas virtuales).
* **RDS** (base de datos relacional, como MySQL o PostgreSQL).
* **EFS o S3** (almacenamiento).
* **Elastic Beanstalk** o **ECS (Fargate)** para desplegar tu backend (Laravel, por ejemplo).
* **VPC** (redes privadas y subredes).
* **CloudFormation** o **Terraform** (infraestructura como código).
* **CloudWatch**, **SNS**, **SQS**, **Auto Scaling** (automatización y monitoreo).
* Análisis de costos con **AWS Cost Explorer** y **Pricing Calculator**.

### Ejemplo:

Un pequeño **sistema de gestión (tipo ERP o dashboard de logística)** con:

* Backend Laravel desplegado en **Elastic Beanstalk** con RDS.
* Archivos en **S3**.
* Monitoreo y alertas con **CloudWatch + SNS**.
* Logs y backups automatizados.

💡 *Resultado:* una infraestructura *realista de empresa pequeña*, con seguridad, resiliencia y control de costos.

---

## 🌍 **Orden recomendado**

| Etapa | Proyecto                           | Dificultad | Duración sugerida |
| ----- | ---------------------------------- | ---------- | ----------------- |
| 1     | Static Website (S3 + CloudFront)   | 🟢 Fácil   | 1 semana          |
| 2     | Serverless API (Lambda + DynamoDB) | 🟡 Media   | 2 semanas         |
| 3     | Full Infra (EC2/RDS/Beanstalk/VPC) | 🔴 Alta    | 3–4 semanas       |
