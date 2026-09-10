# 1. Clona tu repositorio ya creado en GitHub
git clone https://github.com/KevinMichueHuaman/Mis-evidencias.git
cd Mis-evidencias

# 2. Descomprime el zip que descargaste (ajusta la ruta si está en otra carpeta)
unzip ~/Downloads/Kevin-Michue-Huaman.zip -d temp

# 3. Copia el contenido real del repo (incluye el .gitignore oculto)
cp -r temp/repo/. .

# 4. Borra el zip que habías subido antes y la carpeta temporal
rm -f Kevin-Michue-Huaman.zip
rm -rf temp

# 5. Sube los cambios
git add -A
git commit -m "Agregar estructura del curso: 4 unidades x 4 semanas + panel dinámico"
git push
