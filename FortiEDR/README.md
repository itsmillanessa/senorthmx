LABORATORIO AUTOMATIZADO DE FORTIEDR

Prerequisitos: Acceso a AMI preconfigurada, solicitarla con @itsmillanessa

fortiedr-lab.yaml
Este template de CloudFormation lanza un entorno completo para pruebas de FortiEDR sobre Windows con:

VPC y subred pública

EC2 con tu AMI personalizada

Security Group con acceso RDP (puerto 3389)

🚀 Uso
Ve a AWS CloudFormation

Clic en “Crear pila” > “Con recursos nuevos (estándar)”

Carga el archivo desde el bucket de S3: https://se-northmx.s3.us-west-1.amazonaws.com/Laboratorios/cloudformation/EDR/fortiedr-lab.yaml

Da clic en “Siguiente” → “Siguiente” → Acepta permisos IAM → Crear pila
