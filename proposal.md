# TP-DSW-ECOMMERCE
Trabajo practico para la materia Desarrollo de software en la comisión 3K02
# Propuesta TP DSW

## Grupo
### Integrantes
* 39749 - Egea Lucas Andres
* 49953 - Fracassi Santiago
* 49797 - Montrasi Juan Ignacio 
* 49416 - Achamas Agustina

### Repositorios
* [frontend app] no disponible en esta entrega
* [backend app] no disponible en esta entrega


## Tema
### Descripción
Se plantea para este proyecto un E-commerce de ropa con un carro de compras, busquedas con diferentes filtros, cada producto bien
discriminado en su tipo sea ropa de hombre, mujer, niño, unisex y sus diferentes talles.
Sera posible comprar como minorista o mayorista.
A considerarse nuevas cualidades.


### Modelo
Modelo de dominio inicial
https://drive.google.com/file/d/1pjqIB0xBDmt9TUcnxpfwAKTRw3L7BDt-/view?usp=sharing

## Alcance Funcional 

### Alcance Mínimo

Regularidad:
|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD Tipo Producto<br>2. CRUD Tipo CLiente<br>3. CRUD Pedido<br>4. CRUD Vendedor|
|CRUD dependiente|1. CRUD Producto {depende de} CRUD Tipo Producto<br>2. CRUD Cliente {depende de} CRUD Tipo de cliente y localidad 3. CRUD localidad {depende de} CRUD Provincia
|Listado<br>+<br>detalle| 1. Listado de prendas siguiendo algun criterio elegido <br> 2. Listado de productos elegidos para la compra, sub total y descuentos aplicados |
|CUU/Epic|1.Crear una cuenta como cliente minorista<br>2. Realizar una compra minorista|


Adicionales para Aprobación
|Req|Detalle|
|:-|:-|
|CRUD |1. CRUD Cliente<br>2. CRUD Servicio<br>3. CRUD Localidad<br>4. CRUD Provincia<br>5. CRUD Vendedor<br>|
|CUU/Epic|1. Consultar por stock <br>2. Realizar un pedido mayorista<br>3. Realizar registro como cliente mayorista|


### Alcance Adicional Voluntario


Todavia no definido
