# 📦 SENORTHMX – Laboratorios Automatizados con CloudFormation

Repositorio público de plantillas e infraestructura como código (IaC) para laboratorios de pruebas con tecnologías Fortinet.  
Todos los labs están diseñados para ser desplegados automáticamente en AWS usando **AWS CloudFormation**.

---

## 📁 Estructura del Repositorio

Cada carpeta representa un laboratorio independiente y contiene:

- Archivos `.yaml` de CloudFormation
- Un `README.md` con instrucciones de uso por lab
- Requisitos previos (como AMIs o configuraciones específicas)

---

## 🧪 Laboratorios disponibles

| Carpeta        | Descripción rápida                                                   |
|----------------|----------------------------------------------------------------------|
| `fortiedr/`    | Laboratorio con una AMI preconfigurada de FortiEDR sobre Windows     |
| `...`          | *(Aquí podrás agregar más laboratorios conforme se publiquen)*       |

---

## 🚀 ¿Cómo usar los labs?

1. Entra a la carpeta del lab deseado
2. Lee el `README.md` con las instrucciones específicas
3. Sube el archivo `.yaml` a **AWS CloudFormation**
4. Sigue los pasos indicados para lanzar tu entorno de pruebas

---

## 🙋‍♂️ ¿Necesitas acceso a las AMIs?

Algunos laboratorios requieren una AMI preconfigurada.  
Solicita acceso o IDs directamente a: `@itsmillanessa`

---

## ☁️ Requisitos generales

- Cuenta de AWS con permisos para usar CloudFormation, EC2, VPC
- Par de llaves EC2 (`.pem`) para conexión
- Conocimiento básico de redes y acceso remoto (RDP/SSH)

---

## 📫 Contribuciones

Este repositorio es de uso compartido para el equipo.  
Puedes contribuir con nuevos labs, mejoras o documentación.
