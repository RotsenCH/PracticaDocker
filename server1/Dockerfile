
# Utiliza una imagen de python
FROM python:3.9

#Establecer el directorio de trabajo dentro del contenedor
WORKDIR /servidor

#Copiar todos los archivos desde el host al directorio 
COPY . .

#Instalalr las dependencias requeridas
RUN pip install flask

#Exponer puerto del contenedor
EXPOSE 5000

#Comando para ejecutar aplicación 
CMD ["python", "app.py"]