# Ejercicio 1: Configuración de AWS CLI

## Instrucciones

1. Instala AWS CLI en tu máquina local siguiendo las [instrucciones oficiales](https://docs.aws.amazon.com/cli/latest/userguide/install-cliv2.html).
2. Configura AWS CLI con tus credenciales de AWS.
3. Crea un bucket en S3 utilizando AWS CLI.
4. Sube un archivo a tu bucket S3.
5. Lista los objetos en tu bucket S3 utilizando AWS CLI.

## Solución Esperada

```sh
aws s3 mb s3://mi-bucket-de-ejemplo
aws s3 cp mi_archivo.txt s3://mi-bucket-de-ejemplo/
aws s3 ls s3://mi-bucket-de-ejemplo/
