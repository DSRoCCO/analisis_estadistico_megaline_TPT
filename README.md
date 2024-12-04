# Análisis de Tarifas de Megaline

Este proyecto analiza el desempeño de las tarifas **Surf** y **Ultimate** de Megaline, con el objetivo de identificar tendencias, patrones de uso y diferencias estadísticas entre ambas tarifas, así como evaluar los ingresos generados por cada plan.

## Metodología

1. **Descripción de las Tarifas:**
   - **Surf:**
     - Pago mensual: 20$.
     - Incluye 500 minutos, 50 SMS y 15 GB de datos.
     - Costos por excedente: 3 centavos por minuto/SMS y 10$ por GB adicional.
   - **Ultimate:**
     - Pago mensual: 70$.
     - Incluye 3000 minutos, 1000 SMS y 30 GB de datos.
     - Costos por excedente: 1 centavo por minuto/SMS y 7$ por GB adicional.

2. **Datos Analizados:**
   - **Llamadas, SMS e Internet:** Registros mensuales de duración, cantidad y uso de datos de cada usuario.
   - **Usuarios:** Información demográfica y suscripción a tarifas.
   - **Ingresos:** Cálculo del total generado por los usuarios según los límites de cada tarifa y su uso adicional.

3. **Análisis Exploratorio y Estadístico:**
   - Tendencias mensuales de llamadas, SMS y datos consumidos.
   - Ingresos promedio y totales por tarifa y mes.
   - Pruebas estadísticas para evaluar diferencias significativas entre tarifas y regiones geográficas.

## Hallazgos Clave

### Llamadas
- **Tendencias Mensuales:**
  - El uso de minutos aumenta de enero a diciembre en ambos planes.
  - Los usuarios del plan **Ultimate** consumen más minutos que los de **Surf** en la mayoría de los meses, excepto en enero y febrero, probablemente debido a vacaciones.

### Mensajes
- **Diferencias por Plan:**
  - El promedio de mensajes enviados por los usuarios de **Surf** incrementa hacia diciembre.
  - En **Ultimate**, los mensajes disminuyen gradualmente durante el año, salvo un pico en enero y febrero, que podría atribuirse a vacaciones.

### Internet
- **Consumo de Datos:**
  - Ambos planes muestran un incremento en el uso de datos de enero a diciembre.
  - Los usuarios de **Ultimate** consumen más datos en promedio, especialmente entre enero y marzo.
  - En los meses de julio y agosto, el consumo promedio de **Surf** casi iguala al de **Ultimate**, posiblemente debido a estacionalidades.

### Ingresos
- **Comparación de Tarifas:**
  - El plan **Ultimate** genera ingresos consistentemente altos (entre 70 y 75$ por usuario).
  - **Surf** muestra un incremento de ingresos promedio, comenzando con 20$ en enero y alcanzando hasta 70$ en diciembre.
  - Los meses de julio, agosto y octubre destacan con ingresos promedio altos para **Surf** (60$).

### Pruebas Estadísticas
- Los ingresos entre las tarifas **Surf** y **Ultimate** son significativamente diferentes a nivel estadístico, confirmando la superioridad de **Ultimate** en ingresos totales y consumo.
- Los ingresos en el área de **NY-NJ** también son significativamente diferentes en comparación con otras regiones.

## Conclusiones

- El plan **Ultimate** supera consistentemente a **Surf** en ingresos, consumo y cobertura de servicios, especialmente en los primeros meses del año.
- Aunque el plan **Surf** tiene ingresos más bajos, muestra un crecimiento constante a lo largo del año, lo que lo hace competitivo en términos de volumen de usuarios.
- Las diferencias entre las tarifas y las regiones demuestran la importancia de adaptar estrategias según el perfil del cliente y las áreas geográficas.
- Los resultados respaldan la posibilidad de optimizar los precios de **Surf** en los meses pico para maximizar los ingresos sin comprometer la competitividad.
