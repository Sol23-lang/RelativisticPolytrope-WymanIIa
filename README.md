# RelativisticPolytrope-WymanIIa
Análisis del intercambio de energía entre un politropo relativista y un fluido Wyman IIa isótropo en estrellas compactas, usando desacoplamiento gravitacional por deformación geométrica mínima extendida. Se muestran transferencias energéticas en capas externas y estabilidad del núcleo, cumpliendo la condición de energía fuerte.
# Descripción del Proyecto
# Intercambio Energético entre un Politropo Relativista y un Fluido Wyman IIa

Una estrella es una esfera de gas, principalmente hidrógeno, en equilibrio entre la **gravedad**, que tiende a comprimirla, y la **presión del gas de plasma caliente** generado por reacciones nucleares, que tiende a expandirla. Las colisiones moleculares calientan la nube hasta que se alcanzan las condiciones para la **fusión termonuclear**, liberando gran cantidad de energía y aumentando la presión, temperatura y velocidad de las partículas, lo que retroalimenta las reacciones nucleares.  

Estas estrellas pueden evolucionar hasta fases finales como **remanentes estelares**, donde los efectos gravitacionales son fundamentales y son estudiados dentro del marco de la **Teoría de la Relatividad General (TRG)**. Modelar estos cuerpos es un tema central en astrofísica teórica, utilizando soluciones analíticas de las **ecuaciones de campo de Einstein** para describir su estructura interna. Generalmente, estos modelos consideran a los cuerpos como **fluidos relativistas perfectos**, cuyas características internas están determinadas por las ecuaciones de Einstein.  

Entre los fenómenos menos estudiados en detalle se encuentra la **interacción e intercambio energético de los fluidos relativistas** que componen estos cuerpos. Aunque este intercambio puede parecer complejo debido a la naturaleza interna de los objetos compactos, desde 2022 se han desarrollado enfoques analíticos simplificados para ciertas configuraciones [1–5]. Estos estudios emplean el **desacoplamiento gravitacional mediante deformación geométrica mínima extendida**, permitiendo analizar el intercambio energético entre distintos fluidos de manera controlada.  

## Objetivo del proyecto

Analizar el intercambio energético relativista entre un politropo y un fluido tipo Wyman IIa.
## Objetivo Específico
- Realizar un estudio bibliográfico del intercambio energético entre fluidos relativistas.
- Estudiar el desacople gravitacional por deformación mínima extendida.
- Emplear la semilla de fluido isótropo de tipo Wyman IIa en el algoritmo desarrollado por Ovalle para resolver nuestro problema.
- Analizar el intercambio energético de ambas fuentes gravitacionales.
## Formulación de la incógnita
**¿Cuál es la naturaleza del intercambio energético entre un politropo relativista y un fluido tipo Wyman IIa, y cómo afecta este intercambio a la estabilidad del sistema?**
# Resultados del Intercambio Energético en Estrellas Compactas

## 📚 Revisión y metodología
- Se revisaron conceptos fundamentales del **intercambio energético en fluidos relativistas** usando **desacoplamiento gravitacional (GD por MGDe)**.  
- Se utilizó un **fluido isótropo tipo Wyman IIa** como semilla en el algoritmo analítico, permitiendo determinar g'(r).  
- Se desarrolló un **modelo físico-numerico en Matlab**, asignando valores a constantes **A, B, c, K, R, n** para integrar g(x) y generar configuraciones realistas de estrellas de neutrones.

---

## ⭐ Configuraciones y estabilidad
- Se generaron **3 configuraciones**, consistentes con criterios físicos.  
- **2 cumplen la Condición de Energía Fuerte (SEC):**  
  - g₁ ≈ -1.638 (K = 0.44)  
  - g₂ ≈ -3.121 (K = 0.47)  
- Conclusión: Valores de g en **[-1.638, -3.121]** garantizan estabilidad.  
- Se recomienda explorar más configuraciones para analizar rangos precisos de estabilidad.

---

## 🔹 Anisotropía
- La **anisotropía Π = p_t - p_r** aumenta con el radio r.  
- Presión tangencial > presión radial en regiones externas.  
- Cambios bruscos en Π cuando la **SEC no se cumple**, afectando estabilidad y evolución.  
- Alta anisotropía puede prevenir colapsos o alterar la dinámica del sistema.

---

## ⚡ Intercambio energético
- Configuraciones con SEC cumplida: patrones energéticos **ordenados**.  
- Configuraciones sin SEC: distribución energética **más dispersa**.  
- Centro del objeto: Π ≈ 0 → ΔE ≈ 0  
- Zonas externas: anisotropía y ΔE aumentan → mayor intercambio energético.

---

## 🔧 Factor de compacticidad
- Objetos más compactos (u ~ 0.3-0.35): Π y ΔE **altos**, flujos energéticos activos.  
- Objetos menos compactos (u ~ 0.17): Π y ΔE bajos.  
- Variaciones en **K** afectan significativamente ΔE y Π → K es determinante en comportamiento energético y anisotrópico.

---

## 📌 Conclusión
- La **SEC** regula el intercambio energético y la anisotropía.  
- La **compacticidad y K** son factores clave para estabilidad y dinámica de objetos estelares compactos.  
- El modelo permite generar configuraciones físicamente realistas de **estrellas de neutrones**, contribuyendo al estudio de objetos compactos en condiciones extremas.

## Referencias

1. Energy-exchange-between-relativistic-fluids: the polytropic case key  
2. Carrasco-Hidalgo & Contreras  
3. Maurya et al., 2022  
4. Lohakare et al., 2023  
5. Ovalle, 2017
