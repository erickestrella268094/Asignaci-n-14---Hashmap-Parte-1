# Compilacion y ejecucion

# Opcion 1: Desde NetBeans
1. Abrir NetBeans 22  
2. Importar el proyecto  
3. Abrir la clase TestTablaHash.java  
4. Clic derecho → Run File  
5. Ver la salida en la consola de NetBeans  

# Opcion 2: Desde consola
1. Ir a la carpeta src  
2. Compilar todas las clases  
   javac com/mycompany/hashmap/*.java  
3. Ejecutar la clase de prueba  
   java com.mycompany.hashmap.TestTablaHash  



Clases principales

- **Diccionario.java**  
  Interfaz generica clave valor que define los metodos basicos put get remove containsKey size  

- **TablaHash.java**  
  Implementacion de la tabla hash con encadenamiento separado y redimensionamiento dinamico  
  Incluye  
  - Insercion put  
  - Busqueda get  
  - Eliminacion remove  
  - Verificacion containsKey

- Tamano size  
  - Rehashing automatico resize  

- **TestTablaHash.java**  
  Clase de prueba con metodo main que demuestra el funcionamiento de la tabla hash  



#Ejemplo de salida

Valor de manzana: 10  
Contiene 'pera'? true  
Size: 2  
Contiene 'pera'? false  
Size: 1  


# Documentacion Javadoc

La documentacion se genera directamente en NetBeans  
- Menu Run → Generate Javadoc  
- Se crea la carpeta dist/javadoc con archivos HTML navegables  
 
