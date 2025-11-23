#  Documentación del Dataset de Accidentes en EE. UU. (2016–2023)

Este documento describe cada una de las variables presentes en el dataset de accidentes de tránsito registrados en Estados Unidos entre 2016 y 2023.

---

## Identification
**Identificador único del registro de accidente.**

---

## Source
**Fuente original del dato** (sensores, reportes policiales, APIs de tráfico, etc.).

---

## Severity
**Nivel de gravedad del accidente:**

| Valor | Descripción |
|-------|-------------|
| **1** | Menor impacto (demora leve) |
| **2** | Impacto moderado |
| **3** | Accidente grave |
| **4** | Impacto severo (gran congestión o daños significativos) |

---

## Tiempos del Accidente

| Variable | Descripción |
|---------|-------------|
| **Start_Time** | Fecha y hora de inicio del accidente (zona local). |
| **End_Time** | Fecha y hora de finalización o normalización del tráfico. |

---

## Coordenadas Geográficas

| Variable | Descripción |
|---------|-------------|
| **Start_Lat / Start_Lng** | Coordenadas GPS del punto inicial del accidente. |
| **End_Lat / End_Lng** | Coordenadas del punto final (si aplica). |
| **Distance(mi)** | Longitud de la carretera afectada, en millas. |

---

## Descripción del Accidente

| Variable | Descripción |
|---------|-------------|
| **Description** | Texto descriptivo del evento. |

---

##  Ubicación

| Variable | Descripción |
|---------|-------------|
| **Street** | Calle donde ocurrió el accidente. |
| **City** | Ciudad. |
| **County** | Condado. |
| **State** | Estado de EE. UU. |
| **Zipcode** | Código postal. |
| **Country** | País (generalmente “US”). |
| **Timezone** | Zona horaria (Eastern, Central, Pacific, etc.). |
| **Airport_Code** | Aeropuerto cercano (útil para datos meteorológicos). |

---

## Variables Meteorológicas

| Variable | Descripción |
|---------|-------------|
| **Weather_Timestamp** | Momento del registro meteorológico más cercano. |
| **Temperature(F)** | Temperatura en Fahrenheit. |
| **Wind_Chill(F)** | Sensación térmica en Fahrenheit. |
| **Humidity(%)** | Humedad relativa. |
| **Pressure(in)** | Presión atmosférica (pulgadas de mercurio). |
| **Visibility(mi)** | Visibilidad horizontal en millas. |
| **Wind_Direction** | Dirección del viento (N, NE, SE, etc.). |
| **Wind_Speed(mph)** | Velocidad del viento. |
| **Precipitation(in)** | Precipitación acumulada. |
| **Weather_Condition** | Descripción general del clima (Clear, Rain, Snow…). |

---

## Infraestructura y Entorno

Valor booleano (True/False) indicando presencia cercana:

| Variable | Significado |
|---------|-------------|
| **Amenity** | Servicios cercanos (tiendas, gasolineras, etc.). |
| **Bump** | Tope o montículo. |
| **Crossing** | Cruce peatonal o vehicular. |
| **Give_Way** | Señal de “Ceda el paso”. |
| **Junction** | Intersección o entronque. |
| **No_Exit** | Calle sin salida. |
| **Railway** | Vías ferroviarias cercanas. |
| **Roundabout** | Rotonda o glorieta. |
| **Station** | Estación (bus, tren, metro). |
| **Stop** | Señal de “Pare”. |
| **Traffic_Calming** | Medidas de control de tráfico. |
| **Traffic_Signal** | Semáforo cercano. |
| **Turning_Loop** | Área de retorno o giro. |

---

## Condiciones de Luz

| Variable | Descripción |
|---------|-------------|
| **Sunrise_Sunset** | Día o noche según el estado del sol. |
| **Civil_Twilight** | Crepúsculo civil. |
| **Nautical_Twilight** | Crepúsculo náutico. |
| **Astronomical_Twilight** | Crepúsculo astronómico. |

---

