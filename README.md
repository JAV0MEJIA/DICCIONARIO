# DICCIONARIO
#INFORMACION PERSONAL
#javier mejia

informacion_personal = {
    "nombre": "Juan Pérez",
    "edad": 30,
    "ciudad": "QUITO",
    "profesion": "Ingeniero de Software"
}

# Accedo al valor asociado con la clave "ciudad" y modificarlo
ciudad_actual = informacion_personal["ciudad"]
print(f" Ciudad actual: {ciudad_actual}")
informacion_personal["ciudad"] = "QUITO"
print(f" Ciudad nueva: {informacion_personal['ciudad']}")

# Agrego una nueva clave-valor al diccionario que represente la "especialidad" de la persona
informacion_personal["especialidad"] = "Desarrollo Web"

# Verifico si la clave "telefono" existe en el diccionario
if "telefono" not in informacion_personal:
    informacion_personal["telefono"] = "023020925"
    print("Teléfono agregado")

# Elimino la clave "edad" del diccionario
del informacion_personal["edad"]

# ImprimogG el diccionario resultante
print("\nDiccionario resultante:")
print(informacion_personal)
