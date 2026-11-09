# Proyecto Final | Análisis de Datos
**Autor:** Agustina Britos  
**Curso:** Herramientas Básicas para el Análisis de Datos
**Año:** 2026

# Análisis característico de los Usuarios de Netflix
Este proyecto busca analizar de manera integral las características y preferencias de los usuarios de la plataforma de streaming en función de factores determinantes como la edad, el comportamiento de visualización y la ubicación geográfica. 

## Interrogante principal
¿Cuáles son las características de los usuarios actuales de Netflix en relación con su tipo de suscripción, género favorito y método de pago en las diferentes regiones del mundo?

## Objetivos específicos
- Conocer qué tipo de suscripción es la más frecuente entre los usuarios activos de la plataforma.
- Investigar cuál es el género de contenido más visto en cada región desglosado por rango etario.
- Detectar cuál es el método de pago más elegido por los usuarios según su zona geográfica.

## Dataset utilizado
El archivo inicial fue obtenido a través de la plataforma de Kaggle[cite: 3]. El dataset contiene 5.000 filas y 14 columnas. Cada registro corresponde a un usuario único e incluye información detallada sobre edad, género, tipo de suscripción, horas de visualización, días desde la última conexión, región, dispositivo, monto mensual, estado de la cuenta, método de pago, cantidad de perfiles y género favorito.

## Tecnologías y librerías
El flujo de trabajo analítico se desarrolló utilizando las siguientes herramientas:
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Power BI

## Resultados y hallazgos principales

### 1. Suscripción más elegida
La suscripción **Basic** es la más frecuente entre los usuarios activos, concentrando 1.027 usuarios, mientras que las modalidades Standard y Premium presentan cifras similares, con 748 y 740 usuarios respectivamente.

<img width="704" height="471" alt="image" src="https://github.com/user-attachments/assets/3b8f3e32-4133-42c6-8638-6afd5473f57f" />

### 2. Género favorito por región y rango etario
El género Drama predomina fuertemente entre los usuarios más jóvenes en África, Europa y Oceanía. En contraste, en Norteamérica y Sudamérica el género Romance lidera en este grupo etario. En los usuarios de mayor edad, las preferencias varían notablemente por región sin un patrón dominante único.

<img width="771" height="471" alt="image" src="https://github.com/user-attachments/assets/d5b962a8-1371-4ec7-bfb9-ae400856ffb9" />

### 3. Métodos de pago más utilizados por región
El análisis global demuestra que los métodos de pago más elegidos de manera general en todas las regiones evaluadas son las criptomonedas (Crypto) y las tarjetas de regalo (Gift Card).

<img width="850" height="597" alt="image" src="https://github.com/user-attachments/assets/e8d2fd73-e99e-400d-88a6-8bbdd1184f78" />

---

## 🔗 Enlaces del proyecto
* 📂 [Dataset inicial](https://github.com/agubritos99-dot/herramientasbasicas-britos-agustina/tree/main/dataset)[cite: 3]
* 📓 [Notebook de Análisis](https://github.com/agubritos99-dot/herramientasbasicas-britos-agustina/blob/main/notebook/DS_USUARIOS_NETFLIX.ipynb)[cite: 3]
* 📊 [Dashboard interactivo](https://github.com/agubritos99-dot/herramientasbasicas-britos-agustina/blob/main/power_bi/DS.USUARIOS_NETFLIX.pbix)[cite: 3]

## 📚 Referencias y Fuentes
* **Plataforma de datos:** Kaggle Datasets[cite: 3]. Disponible en: [https://www.kaggle.com](https://www.kaggle.com)[cite: 3].
* **Metodología e imágenes:** Elaboración propia basada en el EDA realizado en Python y la visualización en Power BI[cite: 1, 3].

## Autor
Nombre: Agustina Britos  
[LinkedIn](https://www.linkedin.com/in/agustina-britos-b96a2b18b?utm_source=share_via&utm_content=profile&utm_medium=member_ios)
