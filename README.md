nombre = str(input("INGRESA TU NOMBRE:\n"))
n = nombre.upper()

# Definimos el ancho total para el nombre
ancho_total = 24  # Ajusta este valor según sea necesario
nombre_centrado = n.center(ancho_total)

print(
"                1   8\n"
"                |   |\n"
"            ____|___|____\n"
"         0  |~ ~ ~ ~ ~ ~|   0\n"
"         |  |           |   |\n"
"      ___|__|___________|___|__\n"
"      |/\/\/\/\/\/\/\/\/\/\/\/|\n"
"  0   |       H a p p y       |   0\n"
"  |   |/\/\/\/\/\/\/\/\/\/\/\/|   |\n"
" _|___|_______________________|___|__\n"
"|/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/|\n"
"|                                   |\n"
"|         B i r t h d a y! ! !      |\n"
"|              " + nombre_centrado + " <3              |\n"
"| ~ ~ ~ ~ ~ ~ ~ ~ ~ ~ ~ ~ ~ ~ ~ ~ ~ |\n"
"|___________________________________|\n"
)
