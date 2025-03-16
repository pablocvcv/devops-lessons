# devops-lessons


## Lesson 3

* Generar accesskeys.
* Configurar el cliente aws cli.
* ver el fichero `lesson_3_iac/cloudformation-simple-instance.yaml`
* Crear los recursos con el siguiente comando
```
aws cloudformation create-stack --stack-name MyFirstStack \
  --template-body file://lesson_3_iac/cloudformation-simple-instance.yaml \
  --region eu-west-1

```
* Ver los recursos en AWS cloudformaton y los recursos individuales.
* Borrar todos los recursos desde consola con el aws-cli

```
aws cloudformation delete-stack --stack-name MyFirstStack --region eu-west-1
```
