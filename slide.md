# Introduccion a  ![python_logo](img/python_logo.png) Andres F. Cardenas #

---

# Me presento #

## Andres F. Cardenas ##

## Desarrollador web Python/Django ##

### akardenasjimenez@gmail.com ######

### @andresfcardenas ######

---

# Motivos para dar esta charla #

1. Mostrar una excelente alternativa para el desarrollo de software
2. Demostrar que es una herramienta robusta
3. Aclarar mitos que giran entorno a este lenguaje
4. Dos meetups en Bogotá:

    * Python Colombia - http://www.meetup.com/pythoncolombia-bogota/

    * Django Bogotá - http://www.meetup.com/Django-Bogota/

---

# ¿Que no es esta charla? #

---

# ¿Que es Python? #

---

# Guido van Rossum ![guido](img/guido.jpg) #

---

# Caracteristicas #

* Sintaxis clara y limpia -> Codigo legible
* Lenguaje interpretado (Practico para hace scripts)
* Flexible
* Veloz (En comparacion con otros lenguajes interpretados)
* Tipado dinamico
* Fuertemente tipado
* Multiplataforma de verdad
* Multiparadigma: estructurado, funcional, orientado a objetos y aspectos
* Se complementa con C/C++ facilmente si se quiere optimizar la app

---

# Por qué Python #

* Cuando se lee codigo Python, se lee como si se tratara de lenguaje natural
* Dinamico al no tener que declarar variables ni argumentos
* Tipos de datos de alto nivel
* Gestion de memoria automatica
* Viene con pilas incluidas
* Facil, En serio, Muy facil de aprender
* Desarrollo rapido de aplicaciones
* Codigo facil de mantener
* Se integra muy bien con metodologias agiles de desarrollo como SCRUM o XP

---

# Un pequeño dato interesante!!! #

---

# Un programador Python es 10 veces mas productivo que un programador Java y 100 veces mas productivo que un programador C  #

---

# Caracteristicas unicas de Python #

---

# Pequeño ejemplo de la sintaxis #
    !python
    class Player:
        """Esta clase representa un jugador
        """
        def __init__(self):
            self.score = REGULATORY_SCORES[0]

        def modify_score(self,p , other_item=None, printed=True):
            """Modifica el puntaje del jugador
            que se le pasa como parametro.
            """
            if other_item == None:
                self.score = REGULATORY_SCORES[
                    REGULATORY_SCORES.index(self.score) + 1
                ]
            elif other_item > 3 and other_item < 7:
                self.score = REGULATORY_SCORES[other_item]
            if printed:
                print "Player {0} {1}\n".format(p, self.get_score())

        def get_score(self):
            """Retorna el puntaje del jugador
            """
            return self.score

    def game(p1, p2):
        """Esta funcion representa un juego
        """
        while True:
            ...

---

# Estructuras de datos #

---

# Diccionarios #

Tipo de dato nativo en Python similar a la matriz asociativa, en el desarrollo web los diccionarios son muy utiles para crear cadenas json a partir de ellos.

## Crear un diccionario, imprimirlo e imprimir un valor asociado a el ##
    !python
    Python 3.2.3 (default, May  7 2012, 07:19:49) 
    [GCC 4.6.2] on linux2
    Type "help", "copyright", "credits" or "license" for more information.
    >>> d = {'llave 1': 'valor 1', 'llave 2': 2}
    >>> print(d)
    {'llave 1': 'valor 1', 'llave 2': 2}
    >>> print(d['llave 1'])
    valor 1

## Modificar un diccionario ##
    !python
    >>> d['llave 1'] = 'nuevo valor' # Cambiar el valor de una llave
    >>> print(d)
    {'llave 1': 'nuevo valor', 'llave 2': 2}
    >>> print(d['llave 1'])
    nuevo valor
    >>> del(d[llave 1]) # Eliminando el valor de un diccionario
    >>> print d
    {'llave 2': 2}

---

# Listas #

---

# Tuplas #

---

# Bucles #

---

# Muchas Gracias!!! ![aplaudir](img/aplaudir.gif) Preguntas? #
