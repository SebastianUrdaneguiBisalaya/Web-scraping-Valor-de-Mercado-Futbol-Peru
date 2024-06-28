# Análisis de los Valores de Mercado de los Jugadores de la Selección Peruana y Argentina en la Copa América 2024

>[!NOTE]
> Desarrollado por Sebastian Urdanegui Bisalaya

En este proyecto utilizo las técnicas de web scraping en la plataforma de ***Transfermarkt*** para extraer el valor de mercado de los jugadores titulares de la selección peruana y la selección argentina en la Fecha 2 de la Copa América 2024.

<img
src="https://larazon.pe/wp-content/uploads/2024/03/Peru.jpeg"
style="border-radius: 10px"/>

### **Introducción**
Este proyecto se centra en la comparación de los valores de mercado de los jugadores titulares de las selecciones de Perú y Argentina en la Fecha 2 de la Copa América 2024. El objetivo es extraer datos detallados sobre los jugadores, procesarlos, limpiarlos y analizarlos, para luego visualizar los resultados.


### **Características**
1. **Extracción de Datos:** Web scraping de Transfermarkt usando Python y Selenium.
2. **Procesamiento de Datos:** Limpieza y análisis de datos.
3. **Visualización:** Presentación de los datos utilizando Figma.

### **Visualización de los datos**

**¿Sabías que el XI inicial de la selección argentina en la Fecha 2 de la Copa América 2024 vale 29 veces más que el XI inicial de Perú?** ⚽💰



Con la emoción de los eventos deportivos en curso, decidí analizar y comparar el valor de mercado del XI inicial de ambas selecciones. Los datos corresponden a los equipos que estuvieron presentes en el pitazo inicial de la Fecha 2, cuando Perú enfrentó a Canadá y Argentina jugó contra Chile. 🇵🇪 vs 🇦🇷



**Te adelanto algunos datos interesantes: el XI inicial argentino tiene un valor de mercado de €504 millones 💸, mientras que el de Perú es de €17.5 millones.**



Para obtener esta información, utilicé técnicas de web scraping con Python y la librería Selenium, extrayendo datos de Transfermarkt. Esto incluye la fecha y lugar de nacimiento, altura, nacionalidad, posición, pie preferido, club actual, agente, y, por supuesto, el valor de mercado actual.



**¿Por qué web scraping?** La eficiencia es clave. Mientras que el scraping tomó alrededor de 5 minutos ⏱️, hacerlo manualmente habría tomado aproximadamente 2 minutos por jugador, lo que se traduce en 44 minutos de trabajo manual. ¡Ahorré casi ¾ de hora! ⚙️



En cuanto a los valores individuales, Julián Álvarez encabeza la lista argentina con un valor de €90 millones, seguido por Enzo Fernández y Alexis Mac Allister con €75 millones cada uno. En contraste, el jugador peruano con mayor valor de mercado es superado por Nicolás Tagliafico (3x), el jugador con menor valor en el XI argentino. 📊



**Otros datos comparativos:**



• La mediana de edad del XI inicial de Perú es 29 años, mientras que la de Argentina es 26 años. 🧑‍🎓🧑‍🦳



• El 90% del XI argentino juega en Europa 🌍, en clubes como Aston Villa, Atlético de Madrid, Tottenham Hotspur, Manchester United, Manchester City, Olympique de Lyon, Chelsea FC, Liverpool y Fiorentina. En Perú, cerca del 40% juega en Europa, en clubes como AEK Atenas FC, Feyenoord Rotterdam, Malmö FF y Cagliari. 🏟️



• La altura promedio de los jugadores peruanos es de 1.79 m, ligeramente superior a la de los argentinos, que es de 1.78 m. 📏



***En futuras publicaciones, sería interesante analizar el rendimiento de los jugadores, incluyendo partidos jugados, tarjetas amarillas y rojas, goles anotados y encajados, historial de fichajes y la evolución de sus valores de mercado.*** 📈

<img
src="./src/Visualization Market Value Peru Soccer Player.png"
/>


### **Tecnologías Utilizadas**

1. **Python:** Lenguaje de programación principal.
2. **Selenium:** Librería para web scraping.
3. **Figma:** Herramienta para la visualización de datos.