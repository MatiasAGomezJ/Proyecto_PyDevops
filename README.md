# Proyecto_PyDevops JuancMendoza
## **TRABAJAR CON RAMAS**

Primero de todo nos situamos en la carpeta que vamos a usar para trabajar. Luego clonamos el repositorio que vamos a usar.
```bash
git clone https://repositorioquetengamos
```
![](https://i.imgur.com/fB0ljbD.png)

Ahora que ya tenemos el repositorio clonado en nuestro ordenador, entramos dentro y escribimos lo siguiente.
```bash
git branch nombredelarama
```
Ahora para que ya tenemos creada la rama, deberemos de cambiar de rama, ya que en teoría queremos trabajar en ella.
Para cambiar de la rama principal a otra que exista usaremos el comando siguiente...
```bash
git checkout nombredelarama
```
![](https://i.imgur.com/9hYlNZ1.png)

Ahora creamos un archivo y lo agregamos a la cola para luego poder subirlo.

![](https://i.imgur.com/lgJtyNv.png)

Hacemos un **commit** para guardar los cambios, y finalmente hacemos el push.
```bash
git commit -m "loquequieras"
git push -u origin nombredelarama
```
![](https://i.imgur.com/QRJmUDC.png)

![](https://i.imgur.com/tVguaHK.png)

> ***Para este trabajo deberemos de hacer mínimo 5 commits, y además el video que muestra el proceso de creación de las ramas***
