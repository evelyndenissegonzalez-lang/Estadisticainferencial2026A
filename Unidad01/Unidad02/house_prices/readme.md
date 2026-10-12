

# Descripción del Conjunto de Datos: Inmuebles en Toluca

## 📊 Acerca del Conjunto de Datos

Este conjunto de datos fue recopilado de forma independiente mediante técnicas de **web scraping** (utilizando la librería *BeautifulSoup*) enfocándose en la oferta de casas en venta en la ciudad de **Toluca, México**. Está pensado como un proyecto de práctica para el desarrollo y perfeccionamiento de habilidades en ciencia de datos, análisis exploratorio y limpieza de datos.

* **Total de registros**: 2,004 propiedades
* **Número de variables (columnas)**: 8

---

## 🗂️ Estructura de las Variables

| Columna | Tipo de Dato | Valores No Nulos | Descripción |
| --- | --- | --- | --- |
| `Unnamed: 0.2`, `Unnamed: 0`, `Unnamed: 0.1` | Entero | 2,004 | Índices residuales o contadores generados automáticamente durante la exportación previa en Pandas. |
| `Ubicación` | Texto (String) | 2,004 | Descripción textual o dirección de la propiedad dentro de Toluca y sus alrededores. |
| `Area` | Numérico (Float) | 1,721 | Superficie o área total de la propiedad (generalmente expresada en metros cuadrados). |
| `Baños` | Numérico (Float) | 1,950 | Cantidad de baños con los que cuenta la residencia. |
| `Habitaciones` | Numérico (Float) | 1,931 | Número de recámaras o habitaciones de la propiedad. |
| `Precio` | Numérico (Float) | 1,999 | Precio de venta listado para el inmueble. |

---

## 📈 Resumen Estadístico Preliminar

* **Área (`Area`)**:
* Media: ~229.53 m² | Rango: 10 m² a 11,111 m²
* *Nota*: Cuenta con 283 valores faltantes.


* **Baños (`Baños`)**:
* Media: ~2.5 baños | Rango: 1 a 124
* *Nota*: Cuenta con 54 valores faltantes.


* **Habitaciones (`Habitaciones`)**:
* Media: ~3.3 habitaciones | Rango: 1 a 40
* *Nota*: Cuenta con 73 valores faltantes.


* **Precio (`Precio`)**:
* Media: ~$169,047 | Mediana: ~$90,750 | Rango: ~$10,653 a ~$10,000,000
* *Nota*: Cuenta con 5 valores faltantes.






