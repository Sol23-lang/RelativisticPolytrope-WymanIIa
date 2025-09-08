# 🌟 RelativisticPolytrope-WymanIIa

**Análisis del intercambio de energía entre un politropo relativista y un fluido Wyman IIa isótropo en estrellas compactas**, usando **desacoplamiento gravitacional por deformación geométrica mínima extendida (GD por MGDe)**.  
Se muestran **transferencias energéticas en capas externas** y **estabilidad del núcleo**, cumpliendo la **Condición de Energía Fuerte (SEC)**.

---

## 🔹 Descripción del Proyecto

Una estrella es una esfera de gas, principalmente hidrógeno, en equilibrio entre:

- **Gravedad:** comprime la estrella.  
- **Presión del plasma caliente:** generado por reacciones nucleares, expande la estrella.

El equilibrio se logra hasta que se producen las condiciones de **fusión termonuclear**, aumentando energía, presión, temperatura y velocidad de partículas. Estas estrellas pueden evolucionar hacia **remanentes estelares** (enanas blancas, estrellas de neutrones o agujeros negros), donde la **Teoría de la Relatividad General (TRG)** regula su dinámica.

El estudio de **interacciones y transferencia energética entre fluidos relativistas** es fundamental para entender la evolución de estos objetos compactos. Aunque complejo, desde 2022 se han desarrollado **modelos analíticos simplificados** que permiten explorar estos fenómenos de manera controlada [1–5].  

Este proyecto utiliza la **semilla de fluido isótropo tipo Wyman IIa** y el algoritmo desarrollado por Ovalle para **analizar el intercambio energético** entre un politropo y un fluido Wyman IIa.

---

## 🎯 Objetivos

### General
- Analizar el **intercambio energético relativista** entre un politropo y un fluido tipo Wyman IIa.

### Específicos
- Revisar la bibliografía sobre **intercambio energético en fluidos relativistas**.  
- Estudiar el **desacople gravitacional por deformación mínima extendida**.  
- Emplear la semilla de fluido isótropo Wyman IIa en el algoritmo de Ovalle.  
- Analizar la **transferencia de energía entre las dos fuentes**.

---

## ❓ Formulación de la incógnita

**¿Cuál es la naturaleza del intercambio energético entre un politropo relativista y un fluido tipo Wyman IIa, y cómo afecta este intercambio a la estabilidad del sistema?**

---

## 📚 Revisión y Metodología

- Se desarrolló un **modelo físico-numerico en Matlab** para integrar la función g(x).  
- Se asignaron valores distintos a **A, B, c, K, R, n** para generar configuraciones realistas de estrellas de neutrones.  
- Se utilizó la **semilla Wyman IIa** para determinar g'(r) y cuantificar el **intercambio energético**.

---

## ⭐ Configuraciones y Estabilidad

- Se generaron **3 configuraciones**, todas consistentes con criterios físicos.  
- **2 cumplen la Condición de Energía Fuerte (SEC):**  
  - g₁ ≈ -1.638 (K = 0.44)  
  - g₂ ≈ -3.121 (K = 0.47)  
- **Conclusión:** valores de g en **[-1.638, -3.121]** garantizan estabilidad.  
- Se recomienda explorar más configuraciones para **analizar rangos precisos de estabilidad**.

---

## 🔹 Anisotropía

- La **anisotropía Π = p_t - p_r** crece con el radio r.  
- Presión tangencial > presión radial en zonas externas.  
- Cambios bruscos en Π cuando **SEC no se cumple**, afectando estabilidad.  
- Una alta anisotropía puede prevenir **colapsos gravitacionales** o alterar la dinámica del objeto.  

---

## ⚡ Intercambio Energético

- Configuraciones con **SEC cumplida**: patrones energéticos **ordenados**.  
- Configuraciones **sin SEC**: distribución energética **más dispersa**.  
- Centro del objeto: Π ≈ 0 → ΔE ≈ 0  
- Zonas externas: anisotropía y ΔE aumentan → mayor transferencia energética.

---

## 🔧 Factor de Compacticidad

- Objetos más compactos (u ~ 0.3-0.35): Π y ΔE **altos**, flujos energéticos activos.  
- Objetos menos compactos (u ~ 0.17): Π y ΔE **bajos**.  
- Variaciones en **K** afectan significativamente ΔE y Π → K es **determinante** en el comportamiento energético y anisotrópico.

---

## 📌 Conclusiones

- La **SEC** regula el intercambio energético y la anisotropía.  
- La **compacticidad y K** son factores clave para estabilidad y dinámica.  
- El modelo permite generar configuraciones físicamente realistas de **estrellas de neutrones**, contribuyendo al estudio de objetos compactos en condiciones extremas.

---
## 📖 Referencias

1. Energy-exchange-between-relativistic-fluids: the polytropic case key  
2. Carrasco-Hidalgo & Contreras  
3. Maurya et al., 2022  
4. Lohakare et al., 2023  
5. Ovalle, 2017
---  
👉 [Mira el póster de este proyecto](Póster_OAQ.pdf)


👉 [Mira el trabajo completa](INTERCAMBIO_ENERGETICO.pdf)
