![cff](https://user-images.githubusercontent.com/42939877/175185321-ab355396-c944-4a81-83e9-5d349f02e115.png)

# ¿Que es CloudFormation y para que sirve?

AWS CloudFormation es un servicio que ayuda a simplificar la gestion de Infra y configuracion de recursos de AWS. Esto permite desarrollar proyectos con buenas practicas de ingenieria de software, ya que ganamos en puntos como Automatizacion, replicabilidad, agilidad, versionado, eliminacion del error humano etc.

- **Automatizacion**: Se disponibiliza un conjunto de recursos de una manera especifica y automatica a traves de un template.

- **Error Humano**: Elimina el error humano al disponibilizar y configurar el conjunto de recursos, ya que ejecutar un codigo no es igual que un desarrollador tenga que replicar manualmente cada uno de los pasos que lleva configurar todos los recursos.

- **Agilidad**: Permite menor tiempo de despliegue del conjunto de recursos y configuraciones, ya que es un codigo que se ejecuta en minutos.

- **Replicabilidad**: Permite ejecutar un mismo conjunto de recursos en distintos ambientes o distintas cuentas sin errores.

- **Versionado**: Permite hacer cambios en algun recurso especifico (ejemplo tamaño de una instancia) para hacer pruebas, y en caso que no resulte satifactoria esa prueba, facilmente se puede volver atras con el versionado de ese codigo (Plantilla IAC).

A traves del servicio de CloudFormation se crea un template JSON o YAML que describe todos los recursos de AWS que necesitamos (por ej. Lambda,  API Gateway, instancias o un bucket s3), y CloudFormation se encarga de aprovisionar y configurar esos recursos. Con esto evitamos crear y configurar individualmente los recursos de AWS.


![cff1](https://user-images.githubusercontent.com/42939877/175190680-c28ab50a-c141-4772-8072-d9163c7e5a8d.png)
