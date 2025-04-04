# aws-lab-php-backend
Laboratorio AWS - Servidor PHP en EC2 con Amazon SES para envío de emails.

# 🚀 Laboratorio AWS: Servidor PHP en EC2 con Amazon SES

Este repositorio documenta la instalación y configuración de un servidor PHP en AWS EC2 con Apache y Amazon SES para el envío de correos.

---

## 🏗️ 1. Lanzar la instancia EC2

1. Ir a **AWS Console > EC2 > Instancias > Lanzar instancia**.
2. Configurar:
   - **Nombre:** `Servidor PHP BackEnd`
   - **Sistema Operativo:** Amazon Linux 2
   - **Tipo de instancia:** `t2.micro` (Free Tier)
   - **Par de claves SSH:** `vockey`
   - **Seguridad:** Habilitar **SSH (22) y HTTP (80)**
3. Conectar con SSH:
   ```sh
   ssh -i "vockey.pem" ec2-user@IP_PUBLICA

