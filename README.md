JWT
---

Partiendo de una API para abstraernos de toda la complejidad de crear un token, agregá una
base de datos H2 para validar el usuario desde una base de datos. Para esto, tenés que
crear la entidad **User**:

* password: String

* username: String

Recordá crear un repository (capa de acceso a datos) para manejar la consulta a la base de datos. Debemos llamar a esta clase desde la clase **MyUserDetailsService**.**loadUserByUsername** para validar que el usuario y contraseña son correctos.


Desde Postman se pueden enviar la información para guardar de la siguiente manera:
![](https://raw.githubusercontent.com/sgcm14/java-JWT/main/src/docs/Captura1.PNG)
> Pantalla de postman

Desde Postman se puede obtener la información enviando el token obtenido en el paso anterior:
![](https://raw.githubusercontent.com/sgcm14/java-JWT/main/src/docs/Captura2.PNG)
> Pantalla de postman


**Realizado por :** Sammy Gigi Cantoral Montejo (sgcm14)

<img src ="https://raw.githubusercontent.com/sgcm14/sgcm14/main/sammy.jpg" width="200">
