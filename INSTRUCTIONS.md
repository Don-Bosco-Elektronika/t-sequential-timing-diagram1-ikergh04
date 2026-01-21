# 🛠️ Zirkuitu Sekuentzialen Kronograma

| **Alumnos** | **Curso** | **Módulo** |
|-------------|-----------|------------|
| 2ME         | 1º        | EEM (Equipos Microprogramables) |

---

## Tabla de la verdad

| Entrada A | Entrada B | Entrada C | Salida    | Salida |
|-----------|-----------|-----------|-----------|--------|
| 0         | 0         | 0         | ░0░       | ░0░    |
| 0         | 0         | 1         | ░1░       | ░1░    |
| 1         | 1         | 0         | ░1░       | ░1░    |
| 1         | 1         | 1         | ░0░       | ░0░    |

----

## 🔲 Kronogramaren Emaitza
<img width="649" height="152" alt="Captura de pantalla 2026-01-21 134630" src="https://github.com/user-attachments/assets/934e34c1-c0c6-435e-846c-d3a2b7203b24" />
<img width="631" height="136" alt="Captura de pantalla 2026-01-21 134707" src="https://github.com/user-attachments/assets/ff758713-c61d-4270-8066-043b449cb197" />

---


## 🔲 Kronogramaren Kodea
Ejercicio 2: T flanco ascendente

{signal: [

  {name: 'T',   wave: '010101....0...101'},
  
  {name: 'clk', wave: 'P................'},
  
  {},
  
  {name: 'Q',   wave: '0.1.0.1.......0.1'},
  
  {name: '-Q',  wave: '1.0.1.0.......1.0'}

]}

Ejercicio 2: T flanco descendente

{signal: [

  {name: 'T',   wave: '010101....0...101'},
  
  {name: 'clk', wave: 'N................'},
  
  {},
  
  {name: 'Q',   wave: '0.1.0.1.0.1.....0'},
  
  {name: '-Q',  wave: '1.0.1.0.1.0.....1'}

]}




---


## 📤 Igo

➡️ **Instrucciones:**  

- **EU:** Igo hurrengo fitxategiak. Igotako fitxategi guztiek zure izena eduki behar dute.  
  - Sinboloaren argazki bat.  
  - Proteus fitxategia eta zirkuitu bakoitzaren irudia (captura) Proteusen.  
  - Wavedrom bakoitzaren emaitzaren kaptura (grafikoa bakarrik).  
  - **KONTUZ:** Kronogramaren kodea kodea izan behar da, ez irudi bat.

