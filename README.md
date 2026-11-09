# pi7c9x3g808gpa

# PCIe Switch PI7C9X3G808GP — Diseño de Esquemático y PCB

# PI7C9X3G808GPA EVB — Tarjeta de evaluación PCIe Gen 3

Tarjeta de evaluación (EVB) para el switch PCI Express Gen 3 **PI7C9X3G808GPA**.
Permite probar el switch en un sistema real: se conecta al host por un conector
de borde (gold fingers) y reparte el enlace hacia varios slots PCIe en la propia tarjeta.

![estado](https://img.shields.io/badge/ruteo-98.9%25-brightgreen)
![cortos](https://img.shields.io/badge/cortos-0-brightgreen)
![herramienta](https://img.shields.io/badge/OrCAD%20X-25.1-blue)

---

## 🛠️ Herramientas

| Herramienta | Uso |
|---|---|
| OrCAD X Capture | Esquemático |
| OrCAD X PCB / Allegro 25.1 | Layout y ruteo |
| Python (scripts propios) | Apoyo al ruteo y verificación con los Gerbers |

## 📈 Estado del proyecto

| Etapa | Estado |
|---|---|
| Esquemático | ✅ Completo (pendiente un ajuste en PCIe) |
| Colocación de componentes | ✅ 454 / 454 |
| Ruteo | 🟡 **1246 / 1260 conexiones (98.9 %)** |
| Cortos | ✅ 0 |
| Limpieza de DRC (espaciados) | ⏳ Pendiente |
| Gold fingers (bisel, máscara, keepouts) | ⏳ Pendiente |
| Serigrafía | ⏳ Pendiente |
| Gerbers de fabricación | ⏳ Pendiente |
