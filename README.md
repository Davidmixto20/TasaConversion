<h1>Proyecto: Calculadora de Divisas para Viajeros Frecuentes</h1>
Este proyecto ayuda a Diego y a Camila a calcular sus divisas en diferentes paises cuyas monedas tambien son diferentes

<h1>Requisitos</h1>
Python 3.12.9


<h1>Instalación</h1>
Clonar el Repositorio
Para obtener el código, clona este repositorio con:

 git clone https://github.com/usuario/proyecto.git
 cd proyecto


<h1>Uso</h1>
Ejecuta el siguiente Codigo en Python:

def exchange_money(budget, exchange_rate):
    resultado = budget * exchange_rate
    return resultado

#Corea: 300 USD a Wones
print(exchange_money(300, 1428.46))

#México: 500 USD a pesos MX
print(exchange_money(500, 19.61))

#Francia: 400 USD a euros
print(exchange_money(400, 0.88))

#Colombia: 250 USD -> pesos colombianos
print(exchange_money(250, 4295.25))

<h1>Explicación del Código</h1>

Se define exchange_money para despues definir la variable resultado que es el dinero que quieres convertir por la tasa de cambio del pais o moneda, despues lo probamos con 4 paises para ver si funciona.



Licencia

Este proyecto es de uso libre.

Contacto

Para dudas o mejoras, contacta con el desarrollador o abre un issue en GitHub.

