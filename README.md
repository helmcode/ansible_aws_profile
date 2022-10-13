# AWS PROFILE
Este role de Ansible se utiliza para:

- Instalar AWS CLI y configurar sus binarios.
- Configura las credenciales de AWS en el usuario root y en un usuario alternativo que le indiquemos.
- Exporta como variables de entorno las credenciales de AWS.


### Input variables
*Credenciales de AWS:*
AWS_ACCESS_KEY_ID:
AWS_SECRET_ACCESS_KEY:
AWS_REGION:

> Se recomienda encarecidamente utilizar Ansible Vault para cifrar estas variables.

*Usuario alternativo: (variable opcional, si no se indica solo se configura el aws profile en el usuario root)*
alternative_user:
