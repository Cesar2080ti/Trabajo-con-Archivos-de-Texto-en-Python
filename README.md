# Crear un nuevo archivo llamado my_notes.txt
with open('my_notes.txt', 'w') as file:
    # Escribir al menos tres líneas de notas personales en el archivo
    file.write("Esta es una nota personal sobre mis objetivos.\n")
    file.write("Hoy aprendí a trabajar con archivos en Python.\n")
    file.write("Es importante organizar mis pensamientos.\n")

# Abrir el archivo my_notes.txt para lectura
with open('my_notes.txt', 'r') as file:
    # Leer el contenido del archivo línea por línea
    for line in file:
        # Mostrar en la consola cada línea leída
        print(line.strip())  # Usamos strip() para eliminar los saltos de línea

# Nota: No es necesario cerrar el archivo explícitamente cuando se usa 'with'
