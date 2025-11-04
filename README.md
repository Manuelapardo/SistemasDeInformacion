**Análisis de Lambdas en AWS**

El uso de Lambdas por medio de AWS trata de un servicio mediante el cual las personas pueden definir un evento mediante la ejecución de un código, 
sin embargo, no requiere que el usuario provea un servidor, instale librerías, proxys ni configure firewalls, por lo tanto, es conocido como un servicio "serverless". El papel de AWS es entonces
brindar "containers" que cuenten con todo lo requerido para realizar la ejecución que permita la realización del evento, incluyendo el aprovisionamiento de recursos y la escalabilidad (la cantidad 
de containers depende de la cantidad de requerimientos).

*Facturación*

La facturación de estos servicios depende únicamente de la cantidad de memoria usada durante el tiempo de ejecución más un valor extra que se adiciona cada vez que se realiza la ejecución.

*Casos de uso:*
- Integración con servicios o APIs a terceros.
- Procesamiento de archivos
- Streaming de datos

*Ejemplo de código*
<img width="882" height="548" alt="image" src="https://github.com/user-attachments/assets/bb60fed5-657b-4684-a63c-298405b2fda5" />
