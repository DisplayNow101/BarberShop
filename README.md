# BarberShop
Proyecto Encargo N°2
#Test del cliente , ya como extendimos el usuario user para agregar mas atributos y
#Asi sea mas facil el logeo de multiusuario (administrador,cliente) 
#Nuestro modelo Cliente recibe la foreignkey del user.

Testeamos el cliente con TestCase

Creamos 2 funciones una que crea el objecto de user y el otro que recibe la instancia comparando el usuario User del sistema con el usuario recien creado.

Creamos otra funcion para el update , el mismo procedimiento solo cambie que recibe como parametro de entrada la id para identificar que usuario quiere modificar.

Probamos el test con los formularios si reciben la validacion correspondientes creados en el forms.py 

Mas abajo creamos unos testeo utilizando unittest para los strings del sistema

*Comparando si son iguales
*Si escriben en mayusculas o minusculas
*Por separado