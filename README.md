# Prueba Práctica — ISR-401 Unidad IV
**Estudiante:** Edhu Xavier Gamarra Araujo  
**Asignatura:** Ingeniería de Requisitos (ISR-401)  
**Docente:** Ing. Gleiston Guerrero, Mg.

---

## Instrucciones de compilación

### Requisitos
- **Compilador:** `pdflatex` (TeX Live 2022 o superior recomendado)
- **Paquetes LaTeX necesarios:**
  - `tikz`, `tikz-uml`
  - `tcolorbox` (con librerías `skins`, `breakable`)
  - `xcolor`, `colortbl`, `booktabs`, `tabularx`, `longtable`, `multirow`
  - `geometry`, `fancyhdr`, `titlesec`, `hyperref`
  - `enumitem`, `float`, `caption`, `setspace`
  - `babel` (opción `spanish`)

### Compilación

Desde la raíz del repositorio, ejecutar **dos veces** (para que el índice y las referencias internas se resuelvan correctamente):

```bash
pdflatex main.tex
pdflatex main.tex
```

### Archivo principal
```
main.tex
```

### Salida esperada
```
main.pdf
```

---

## Estructura del repositorio
```
/
├── main.tex        ← archivo principal LaTeX
├── main.pdf        ← PDF compilado
└── README.md       ← este archivo
```

---

## Contenido del documento

| Sección | Actividad |
|---------|-----------|
| P1 | Diagrama de clases UML (TikZ) |
| P2 | Diagrama de actividades UML (TikZ) |
| P3 | Máquina de estados UML (TikZ) |
| P4 | Tabla de consistencia entre perspectivas |
| P5 | Especificación de requisitos con esquema de atributos |
| P6 | Priorización MoSCoW |
| P7 | Validación por inspección (lista 29148) |
| P8 | Pruebas de aceptación trazadas |
