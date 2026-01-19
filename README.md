# 🏠 La crisis estructural de la vivienda en España (2007–2023)

**Análisis de oferta, precios, salarios y alquiler**

📊 *Proyecto de Data Analysis y análisis económico aplicado basado en datos oficiales para explicar la crisis de accesibilidad a la vivienda en España.*

---

## 📌 Resumen ejecutivo
Entre 2007 y 2023, el mercado de la vivienda en España ha experimentado una transformación estructural profunda:
- La **construcción de vivienda cayó un 83%** desde el pico del boom inmobiliario y **nunca se recuperó**.
- Los **precios de compra** han vuelto a niveles de burbuja **sin un boom de crédito asociado**.
- El **salario real permanece estancado** desde hace más de 15 años.
- El **alquiler se ha convertido en la verdadera barrera de acceso a la vivienda,** absorbiendo la demanda que no puede comprar.

**Conclusión clave:**
La crisis actual **no es una burbuja financiera**, sino una **crisis estructural de oferta**, provocada por una década de infra-construcción.

[**📄 Informe completo (PDF)**](informe/informe_vivienda_españa.pdf)

---

## 🎯 Objetivo del proyecto
Responder con datos a una pregunta clave:

**¿Por qué la vivienda en España es cada vez más inaccesible si no estamos ante una burbuja como la de 2007?**

Preguntas abordadas:
- ¿Qué ha ocurrido con la construcción de vivienda tras la crisis financiera?
- ¿Cómo han evolucionado los precios frente a los salarios reales?
- ¿Qué papel juega el alquiler como “válvula de presión” del sistema?
- ¿Estamos ante un fenómeno cíclico o estructural?

---

## 🧩 Estructura del proyecto
```bash
vivienda_espa-a_analysis/
├── README.md
├── data
│   ├── data_clean
│   │   └── mercado_vivienda_procesado.csv
│   └── data_raw
│       ├── ipc.csv
│       ├── ipv.csv
│       ├── ipva.csv
│       ├── nuevas_viviendas.csv
│       └── salarios.csv
├── informe
│   └── informe_vivienda_españa.pdf
├── notebooks
│   ├── 00_carga_y_limpieza.ipynb
│   ├── 01_analisis_vivienda.ipynb
│   └── 02_analisis_alquiler.ipynb
└── outputs
    └── figures
        ├── alquiler_vs_salario.png
        ├── comparativo_oferta_precio_vivienda.png
        ├── comparativo_precio_salario_real.png
        ├── compra_vs_alquiler.png
        ├── evolucion_construccion_vivienda.png
        ├── evolucion_precio_vivienda.png
        └── evolucion_salario_real.png
```

---

## 📉 Colapso de la oferta de vivenda

La construcción de vivienda en España sufrió un **colapso histórico tras 2008**:
- Pico del ciclo (2007): índice 208
- Mínimo (2014): índice 18
- Caída acumulada: –83%

Desde 2015, la construcción permanece estancada en niveles propios de una economía en recesión, generando una **escasez estructural acumulada año tras año**.

![Evolución de la Construcción de Vivienda en España](outputs/figures/evolucion_construccion_vivienda.png)

---

## 📈 Precio de la vivienda vs oferta

Tras la corrección post-burbuja (2008–2014), los precios se recuperan hasta niveles máximos mientras la construcción **no responde**.

Desde 2018:
- La oferta permanece congelada
- Los precios siguen aumentando

Esto indica una **ruptura del mecanismo de autorregulación del mercado**: los precios ya no incentivan nueva construcción.

![Precio vs Oferta](outputs/figures/comparativo_oferta_precio_vivienda.png)

---

## 💼 Precio de vivienda vs salario real

El salario real del trabajador medio en 2023 es prácticamente el mismo que en 2008.

Mientras tanto:
- El precio de la vivienda ha aumentado más de un **50% desde 2014**
- Comprar una vivienda requiere hoy **1,6 veces más salario** que hace nueve años

Esto genera una **crisis estructural de accesibilidad**.

![Precio vs Salario](outputs/figures/comparativo_precio_salario_real.png)

---

## 🏠 El alquiler como precio real de acceso

Ante la imposibilidad de comprar, la demanda se desplaza al alquiler.

Desde 2018:
- El alquiler sube con fuerza
- El salario real se estanca o cae
- La brecha se amplía de forma persistente

El alquiler deja de ser una opción temporal y se convierte en **la principal barrera de acceso a la vivienda**.

![Alquiler vs Salario](outputs/figures/alquiler_vs_salario.png)

---

## 🧠 Conclusiones

La crisis de vivienda en España:

❌ No es una burbuja financiera  
❌ No es un fenómeno cíclico  

✅ Es una **crisis estructural de oferta**

España:
- Construye como si estuviera en recesión
- Tiene precios como en una burbuja
- Y salarios congelados

**Resultado**: un sistema que genera escasez persistente y bloquea el acceso a la vivienda, especialmente para jóvenes y nuevos hogares.

---

## 🛠️ Tecnologías utilizadas

- Python
- Pandas
- Matplotlib
- Jupyter Notebook
- Análisis de series temporales
- Correlaciones y ratios económicos

---

## 📚 Fuentes de datos

Los datos utilizados provienen de fuentes oficiales y macroeconómicas:

- **INE (Instituto Nacional de Estadística)**  
  - IPC (Índice de Precios al Consumo)  
  - IPVA (Índice de Precios de Alquiler)
  - IPV (Índice de Precio de la Vivienda) 

- **Ministerio de Transportes, Movilidad Sostenible**  
  - Viviendas iniciadas

- **datosmacro.com (Expansión)**  
  - Salario medio

Todos los datos han sido **homogeneizados, limpiados y normalizados (base 2008 = 100)** para permitir comparaciones directas entre variables.

---

## 📄 Informe completo

[👉 Descargar informe completo en PDF](informe/informe_vivienda_españa.pdf)
