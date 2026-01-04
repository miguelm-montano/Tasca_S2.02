# 📊 Análisis de Consultas SQL


## 📈 Resumen
✅ 38 correctas de 41 queries

## ✅ Query 1: Correcto

⏱ Tiempo: 0.34 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 2: Correcto

⏱ Tiempo: 0.30 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 3: Correcto

⏱ Tiempo: 0.30 ms
🔍 No se usó ningún índice en esta consulta.

🚨 **Problemas detectados:**
⚠️ Evitar `SELECT *`. Usar solo las columnas necesarias.

---

## ✅ Query 4: Correcto

⏱ Tiempo: 0.29 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 5: Correcto

⏱ Tiempo: 0.29 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 6: Correcto

⏱ Tiempo: 0.29 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 7: Correcto

⏱ Tiempo: 0.32 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 8: Correcto

⏱ Tiempo: 0.29 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 9: Incorrecto
```diff
--- 
+++ 
@@ -1,12 +1,12 @@
 nombre | precio
-Disco duro SATA3 1TB | 87.00
+Disco duro SATA3 1TB | 86.99
 Memoria RAM DDR4 8GB | 120.00
-Disco SSD 1 TB | 151.00
+Disco SSD 1 TB | 150.99
 GeForce GTX 1050Ti | 185.00
 GeForce GTX 1080 Xtreme | 755.00
 Monitor 24 LED Full HD | 202.00
-Monitor 27 LED Full HD | 246.00
+Monitor 27 LED Full HD | 245.99
 Portátil Yoga 520 | 559.00
 Portátil Ideapd 320 | 444.00
-Impresora HP Deskjet 3720 | 60.00
+Impresora HP Deskjet 3720 | 59.99
 Impresora HP Laserjet Pro M26nw | 180.00
```

⏱ Tiempo: 0.30 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 10: Correcto

⏱ Tiempo: 0.28 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 11: Correcto

⏱ Tiempo: 0.27 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 12: Correcto

⏱ Tiempo: 0.32 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante

---

## ✅ Query 13: Correcto

⏱ Tiempo: 0.28 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 14: Correcto

⏱ Tiempo: 0.28 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 15: Error
- **Descripción**: 1054 (42S22): Unknown column 'p.precio' in 'field list'


## ✅ Query 16: Correcto

⏱ Tiempo: 0.30 ms
🔍 No se usó ningún índice en esta consulta.

🚨 **Problemas detectados:**
⚠️ Evitar `SELECT *`. Usar solo las columnas necesarias.

---

## ✅ Query 17: Correcto

⏱ Tiempo: 0.27 ms
🔍 No se usó ningún índice en esta consulta.

🚨 **Problemas detectados:**
⚠️ Evitar `SELECT *`. Usar solo las columnas necesarias.

---

## ✅ Query 18: Correcto

⏱ Tiempo: 0.29 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 19: Correcto

⏱ Tiempo: 0.29 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 20: Correcto

⏱ Tiempo: 0.31 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante

---

## ✅ Query 21: Correcto

⏱ Tiempo: 0.31 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ❌ Query 22: Incorrecto
```diff
--- 
+++ 
@@ -1,12 +1,12 @@
 nombre | precio | nombre del fabricante
 Monitor 24 LED Full HD | 202.00 | Asus
 Monitor 27 LED Full HD | 245.99 | Asus
+GeForce GTX 1080 Xtreme | 755.00 | Crucial
 Memoria RAM DDR4 8GB | 120.00 | Crucial
-GeForce GTX 1080 Xtreme | 755.00 | Crucial
 GeForce GTX 1050Ti | 185.00 | Gigabyte
 Impresora HP Deskjet 3720 | 59.99 | Hewlett-Packard
 Impresora HP Laserjet Pro M26nw | 180.00 | Hewlett-Packard
+Portátil Ideapd 320 | 444.00 | Lenovo
 Portátil Yoga 520 | 559.00 | Lenovo
-Portátil Ideapd 320 | 444.00 | Lenovo
 Disco SSD 1 TB | 150.99 | Samsung
 Disco duro SATA3 1TB | 86.99 | Seagate
```

⏱ Tiempo: 0.33 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ✅ Query 23: Correcto

⏱ Tiempo: 0.33 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ✅ Query 24: Correcto

⏱ Tiempo: 0.31 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ✅ Query 25: Correcto

⏱ Tiempo: 0.31 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ✅ Query 26: Correcto

⏱ Tiempo: 0.34 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ✅ Query 27: Correcto

⏱ Tiempo: 0.33 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ✅ Query 28: Correcto

⏱ Tiempo: 0.32 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ✅ Query 29: Correcto

⏱ Tiempo: 0.36 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

🚨 **Problemas detectados:**
⚠️ Considerar `EXISTS` en lugar de `IN` para eficiencia.

---

## ✅ Query 30: Correcto

⏱ Tiempo: 0.35 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ✅ Query 31: Correcto

⏱ Tiempo: 0.31 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ✅ Query 32: Correcto

⏱ Tiempo: 0.33 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ✅ Query 33: Correcto

⏱ Tiempo: 0.32 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ✅ Query 34: Correcto

⏱ Tiempo: 0.34 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante

---

## ✅ Query 35: Correcto

⏱ Tiempo: 0.32 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante

---

## ✅ Query 36: Correcto

⏱ Tiempo: 0.35 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante

🚨 **Problemas detectados:**
⚠️ Evitar `SELECT *`. Usar solo las columnas necesarias.

---

## ✅ Query 37: Correcto

⏱ Tiempo: 0.38 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante

🚨 **Problemas detectados:**
⚠️ Evitar `SELECT *`. Usar solo las columnas necesarias.

---

## ✅ Query 38: Correcto

⏱ Tiempo: 0.37 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante

---

## ✅ Query 39: Correcto

⏱ Tiempo: 0.43 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante

---

## ✅ Query 40: Correcto

⏱ Tiempo: 0.36 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante

🚨 **Problemas detectados:**
⚠️ Evitar `SELECT *`. Usar solo las columnas necesarias.

---

## ✅ Query 41: Correcto

⏱ Tiempo: 0.40 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante

🚨 **Problemas detectados:**
⚠️ Evitar `SELECT *`. Usar solo las columnas necesarias.

---
