# Prueba Práctica — ISR-401 Unidad IV
**Estudiante:** Edhu Xavier Gamarra Araujo  
**Asignatura:** Ingeniería de Requisitos (ISR-401)  
**Docente:** Ing. Gleiston Guerrero, Mg.

---

## Instrucciones de compilación

### Requisitos
- **Compilador:** `pdflatex` (TeX Live 2022 o superior recomendado)
- **Paquetes LaTeX necesarios:**
  - `tcolorbox` (con librerías `skins`, `breakable`)
  - `xcolor`, `colortbl`, `booktabs`, `tabularx`, `longtable`, `multirow`
  - `geometry`, `fancyhdr`, `titlesec`, `hyperref`
  - `enumitem`, `float`, `caption`, `setspace`
  - `graphicx` (para incluir las imágenes PNG de los diagramas)
  - `babel` (opción `spanish`)

### Compilación

Desde la raíz del repositorio, ejecutar **dos veces** (para que el índice y las referencias internas se resuelvan correctamente):

```bash
pdflatex Gamarra_EV_U4.tex
pdflatex Gamarra_EV_U4.tex
```

### Archivo principal
```
Gamarra_EV_U4.tex
```

### Salida esperada
```
Gamarra_EV_U4.pdf
```

---

## Estructura del repositorio
```
/
├── Gamarra_EV_U4.tex          ← archivo principal LaTeX
├── Gamarra_EV_U4.pdf          ← PDF compilado
├── figuras/
│   ├── logo.png               ← logo de la universidad
│   ├── CapturaFormativa.jpeg  ← captura del cuestionario SGA
│   ├── Diagrama_Clases.png    ← P1: Diagrama de clases UML
│   ├── Diagrama_Actividad.png ← P2: Diagrama de actividades UML
│   └── Diagrama_Estados.png   ← P3: Máquina de estados UML
└── README.md                  ← este archivo
```

---

## Contenido del documento

| Sección | Actividad |
|---------|-----------|
| P1 | Diagrama de clases UML (imagen PNG) |
| P2 | Diagrama de actividades UML (imagen PNG) |
| P3 | Máquina de estados UML (imagen PNG) |
| P4 | Tabla de consistencia entre perspectivas |
| P5 | Especificación de requisitos con esquema de atributos |
| P6 | Priorización MoSCoW |
| P7 | Validación por inspección (lista 29148) |
| P8 | Pruebas de aceptación trazadas |
