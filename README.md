# practicaserver
# Crear carpeta
mkdir -p /home/angel/tarea_webmin

# Entrar a la carpeta
cd /home/angel/tarea_webmin

# Crear archivos con contenido de ejemplo
echo "Este es un archivo de texto." > informe.txt
echo -e "#!/bin/bash\necho 'Hola desde el script'" > script.sh
chmod +x script.sh
echo -e "nombre,edad\nJuan,25\nAna,30" > datos.csv
echo -e "<!DOCTYPE html>\n<html>\n<head><title>Ejemplo</title></head>\n<body>\n<h1>Hola Mundo</h1>\n</body>\n</html>" > pagina.html
echo -e '{\n  "nombre": "Angel",\n  "edad": 25\n}' > config.json

