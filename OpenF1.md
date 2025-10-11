<table>
  <tr>
    <td style="width: 100px;">
      <img src="https://datasphere.tech/wp-content/uploads/2024/10/1-300x256.png" alt="Datasphere Logo" width="80">
    </td>
    <td>
    </td>
  </tr>
</table>

# OpenF1 – API de datos históricos y en tiempo real de Fórmula 1

**Autor:** Nelson Zepeda  
**Correo:** nelson.zepeda@datasphere.tech  

**Empresa:** [datasphere.tech](https://datasphere.tech)  
**LinkedIn:** [Datasphere Consulting](https://www.linkedin.com/company/datasphere-consulting/)  
**Fecha:** Octubre 2025



OpenF1 es una API **open-source** que proporciona acceso a datos de Fórmula 1, tanto **históricos** como **en vivo**, con un amplio abanico de endpoints disponibles. ([openf1.org](https://openf1.org/?utm_source=chatgpt.com))

---
<img src="https://openf1.org/images/logo-5882a735.png" alt="OpenF1 Logo" width="150">

## Qué ofrece OpenF1 (endpoint / tipos de datos)

Aquí los principales recursos que puedes consumir:

| Endpoint / Recurso | Qué devuelve / descripción |
|---------------------|-----------------------------|
| **meetings** | Información de eventos / Grandes Premios |
| **sessions** | Detalles de sesiones (práctica, clasificación, carrera, sprint) para cada meeting |
| **drivers** | Información de pilotos (número, equipo, país, etc.) |
| **laps** | Datos de vueltas: tiempo total de la vuelta, tiempos por sector, comparación entre vueltas |
| **car_data** | Telemetría del auto: velocidad, acelerador, freno, RPM, engranaje, DRS, etc. |
| **location** | Ubicación del auto en pista (coordenadas) en tiempo real / semi-real |
| **position** | Posiciones de los pilotos durante una sesión o cómo evolucionan |
| **pits** | Información de paradas en boxes: vuelta de parada, duración, etc. |
| **stints** | Segmentos de carrera de cada piloto sin parar (qué neumáticos usaron, entre paradas) |
| **race_control** | Mensajes de control de carrera: incidentes, penalizaciones, banderas |
| **team_radio** | Comunicaciones piloto-equipo (cuando están disponibles) |
| **weather** | Condiciones climáticas en pista (temperatura, viento, etc.) |

---

## Acceso: autenticación y uso

- Los datos **históricos están disponibles sin autenticación**.  
- Para acceder a datos **en tiempo real**, necesitas autenticación.  

---

## Consideraciones y notas

- OpenF1 es un proyecto **no oficial**, no afiliado a la Fórmula 1 ni a la FIA  
- La API es muy útil para análisis, visualizaciones, dashboards y simulaciones.  
- Dispone de documentación, ejemplos y SDKs en su repositorio oficial.  

---
