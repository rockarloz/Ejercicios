Ejercicios
==========

Solo subiré ejercicios que voy aprendiendo 
class Saludo
def initialize(nombre)
@n=nombre
end
def hola
puts "hola #{@n}"
end
def n=(nuevo)
@n=nuevo
end

#bueno si , luego creo mi objeto

a=Saludo.new(carlos)
a.hola --> "hola carlos"

a.n=juan 
a.hola -->"hola juan rai "

#Pero ahora escribe
a.n
#y verás como todo explota
# si todo sale mal
# El error que te marca es "no hay metodo "n" para la clase Saludo"

a.n= "carlos"
#significa:
#1 =el objeto "a" "responde" al método "n=" con un parámetro "carlos"
#2 = "a" es el receptor de una llamada al método "n="
# NO significa:
#1= que "n" no es una instancia de a
#2= que "a" es una especie de estructura de datos con un tipo de dato "n"
