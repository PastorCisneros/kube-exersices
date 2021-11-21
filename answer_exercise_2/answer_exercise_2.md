Debe tener 3 replicas

![alt text](images2/Imagen1.png)

![alt text](images2/Imagen2-2.png)

¿Cúal sería el comando que utilizarías para escalar el número de replicas a 10?

```csharp kubectl scale --replicas=10 -f replicas.yml```
![alt text](images2/Imagen3.png)

Si necesito tener una replica en cada uno de los nodos de Kubernetes, 
¿qué objeto se adaptaría mejor?

DaemonSet