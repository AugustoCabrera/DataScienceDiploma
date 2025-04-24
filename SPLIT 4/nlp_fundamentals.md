# 🧠 Marco Teórico

## 📚 Procesamiento de Lenguaje Natural (NLP)

El Procesamiento de Lenguaje Natural (NLP, por sus siglas en inglés) es una rama de la inteligencia artificial (IA) que se ocupa de dotar a las computadoras de la capacidad para comprender el lenguaje humano, tanto escrito como hablado, de manera similar a los seres humanos.

NLP combina la **lingüística computacional** con **modelos estadísticos**, **machine learning** y **deep learning**. Estas tecnologías permiten a las máquinas procesar el lenguaje en forma de texto o voz y "comprender" su significado completo, incluyendo la **intención** y el **sentimiento** del hablante o escritor.

---

## 💡 ¿Para qué se puede usar el NLP?

- Encontrar información relevante para las consultas de los usuarios.
- Sugerir correcciones ortográficas o gramaticales.
- Predecir la próxima palabra que probablemente escriba el usuario.
- Responder preguntas (cortas o largas).
- Resumir uno o varios documentos (pueden ser resúmenes generales o por consulta).
- Identificar opiniones y sentimientos expresados en un texto.
- Generar audio a partir de texto.

---

## 🔧 Principales Tareas de NLP

### 💬 Análisis de Sentimiento

Permite clasificar un fragmento de texto (como un comentario o reseña) como **positivo**, **negativo** o **neutral**. Tiene múltiples aplicaciones en salud, atención al cliente, banca, etc.

#### ✅ Análisis de Sentimiento Calificado

Si la polaridad es importante para el negocio, se pueden definir categorías más específicas como: **muy positivo**, **positivo**, **neutro**, **negativo** y **muy negativo**.  
Esto permite detectar comentarios negativos con mayor precisión y aplicar estrategias para mitigar impactos o prevenir la deserción de clientes.

#### 😠 Detección de Emociones

Va más allá de la simple polaridad y permite identificar emociones como **alegría**, **frustración**, **ira** o **tristeza**.  
Se puede lograr mediante léxicos emocionales (listas de palabras con emociones asociadas) o modelos complejos de aprendizaje automático.

#### 🧩 Aspect-Based Sentiment Analysis

Este análisis identifica **aspectos específicos** mencionados en un texto y determina la opinión sobre cada uno.  
Por ejemplo, una oración puede expresar una opinión negativa sobre la *duración de la batería*, mientras que el resto del texto sea positivo.

#### 🌍 Análisis de Sentimiento Multilingüe

Es desafiante por el alto nivel de **preprocesamiento** y recursos requeridos.  
Algunos recursos están disponibles online (léxicos multilingües), mientras que otros deben desarrollarse (corpus paralelos, técnicas de detección de ruido). Se requiere capacidad técnica para su implementación.

#### 📌 Importancia del Análisis de Sentimiento

El análisis de sentimiento es esencial para **comprender lo que los usuarios piensan y sienten** a gran escala.  
Permite detectar patrones en redes sociales, encuestas, reseñas, etc., ayudando a las marcas a:

1. Identificar necesidades del cliente  
2. Ordenar datos en grandes volúmenes  
3. Realizar análisis en tiempo real  
4. Aplicar criterios de evaluación consistentes  

#### 🏭 Ejemplos de Uso en la Industria

- Monitoreo de marcas  
- Mejora del soporte al cliente  
- Feedback de empleados  
- Optimización de productos analíticos  
- Monitoreo de mercado y competencia  
- Detección de influenciadores  
- Branding y publicidad en redes sociales  
- Manejo de crisis reputacional  
- Recomendaciones personalizadas

---

### 🧾 Reconocimiento de Entidades Nombradas (NER)

Técnica utilizada para identificar y clasificar entidades mencionadas en un texto, como **personas**, **organizaciones**, **ubicaciones**, **fechas**, **cantidades**, **valores monetarios**, entre otros.

---

### ✂️ Stemming y Lematización

- **Stemming**: Reduce las palabras a su raíz (ejemplo: "amigos", "amistad" → "amig").
- **Lematización**: Encuentra la forma base correcta de la palabra (requiere diccionario del idioma).

---

### 🧺 Bag of Words (BoW)

Representa el texto como un vector basado en la **frecuencia de palabras**, sin considerar el orden.  
Es útil para convertir texto en números para modelos de aprendizaje automático.

---

### ☁️ Nube de Palabras (Wordcloud)

Visualiza las palabras más frecuentes de un texto, donde las palabras más usadas aparecen en tamaño mayor.  
Es ideal para identificar rápidamente los términos clave.

---

### 📈 TF-IDF (Frecuencia de Término - Frecuencia Inversa de Documento)

Asigna pesos a las palabras basándose en su frecuencia en un documento y su rareza en el conjunto total.  
Cuanto más específica sea una palabra para un documento, mayor será su peso.

---

## 🤖 Introducción al Deep Learning

El **Deep Learning** es un subconjunto del aprendizaje automático que usa **redes neuronales** para aprender patrones a partir de grandes cantidades de datos.  
Estas redes mejoran su rendimiento mediante el entrenamiento en **capas profundas** (*deep layers*), permitiendo aprendizaje progresivo y modelos de NLP más potentes.

---
# 🧠 NLP - Fundamentos y Herramientas

## 📌 Características de NLP

Algunas de las características más importantes del Procesamiento de Lenguaje Natural:

- ✅ Identificación de sentimientos  
- ✅ Conversión text-to-speech y viceversa  
- ✅ Traducción de lenguaje  
- ✅ Categorización e indexación  
- ✅ Organización de documentos  
- ✅ Aprendizaje supervisado en su mayoría  

---

## 🧭 Fases Típicas del NLP

1. Análisis léxico y morfológico  
2. Análisis sintáctico  
3. Análisis semántico  
4. Integración de discurso  
5. Análisis pragmático  

---

## ⚙️ ¿Cómo se ejecuta el análisis de NLP?

El análisis de NLP implica la lectura y comprensión del lenguaje escrito o hablado por una computadora. Ejemplos:

- Traducción automática entre idiomas  
- Reconocimiento de voz  
- Respuesta automática a preguntas  

---

## ✅ Ventajas

- Respuestas exactas y sin ruido  
- Mejoran con más información  
- Temas ilimitados  
- Fáciles de implementar  
- Menor costo que el personal humano  
- Permite comparaciones  
- Mejora los tiempos de respuesta  

---

## ❌ Desventajas

- Entrenamiento lento sin modelos pre-entrenados  
- Modelos enfocados en tareas específicas  
- Problemas con preguntas mal redactadas  
- Posibilidad de error en predicción  
- Implementación técnica compleja  

---

## 🧰 Herramientas: NLTK

**NLTK** es un toolkit para trabajar con NLP en Python, ofreciendo:

- Tokenización  
- Conversión a lower/upper case  
- Remoción de stopwords  
- Stemming y Lematización  
- Parse Tree (gramática)  
- POS Tagging (etiquetado gramatical)  

---

## 🔤 Conceptos Clave

### Tokenización
Divide el texto en unidades más pequeñas llamadas *tokens*. Se usa para construir vocabularios.

### Conversión a Minúsculas/Mayúsculas
Estandariza palabras como “Casa” y “casa” para evitar confusiones.

### Remoción de Stopwords
Elimina palabras vacías como “yo”, “la”, “y” que no aportan significado útil.

### POS Tagging
Clasifica palabras según su rol gramatical. Ejemplo: sustantivo, verbo, adjetivo.  
Usa: `word_tokenize` + `pos_tag`.

### Parse Tree
Representa visualmente la estructura gramatical de una oración usando árboles de análisis sintáctico.

### Stemming
Recorta palabras a su raíz. Ej: “jugando”, “jugaban” → “jug”.

### Lematización
Obtiene la forma base real de una palabra (lema), usando WordNet y `WordNetLemmatizer`.

---

## 📚 Corpus

Un **corpus** es una colección de texto o audio real usado para entrenar modelos de NLP.

- 🧠 Cuanto más grande, mejores resultados  
- 🧼 Datos limpios y de calidad  
- ⚖️ Balance en los datos para evitar sesgos  

---

## 📈 Document Term Matrix (DTM)

Matriz donde:
- Las filas son documentos  
- Las columnas son términos (palabras)  
- Las celdas representan la frecuencia del término en el documento  

Se suele representar como matriz dispersa (`sparse matrix`).  
La **Term Document Matrix (TDM)** es simplemente la transpuesta de la DTM.

---

## 🧠 POS y NER

### POS (Part of Speech)
Clasifica palabras por su función gramatical según el contexto.  
`spaCy` ofrece modelos y visualizaciones para esto.

### NER (Named Entity Recognition)
Identifica entidades como:

- Personas  
- Organizaciones  
- Ubicaciones  
- Fechas  
- Cantidades  
- Dinero  
- Porcentajes  

---

## 🔄 Preprocesamiento de Texto

### Ejemplo:
- “Quiero ir a COMER Hamburguesas a #Palermo”  
- “Quisiera ir a comer una hamburguesa en palermo”

Para una persona son similares. Para una computadora, no.

### Técnicas de Normalización:
- Convertir todo a minúsculas  
- Limpiar caracteres especiales  
- Lematizar / Stemming  
- Eliminar *stop words*  

---

## 🧮 Vectorización

Convertir texto en vectores de características.

### Bag of Words
1. Identificar el **corpus** (vocabulario único)
2. Contar apariciones por documento  
3. Generar una DTM  
4. Entrenar modelos con esos vectores

⚠️ El problema: genera muchos features → es clave **normalizar y limpiar** bien el texto antes.

---

# 🔍 Procesamiento de Lenguaje Natural con spaCy

## 📦 ¿Qué es spaCy?

**spaCy** es una librería gratuita y de código abierto para procesamiento de lenguaje natural (NLP) en Python. Es altamente eficiente, está escrita en Cython, y está diseñada para construir sistemas robustos de extracción de información y comprensión del lenguaje natural en producción.

Ofrece una API sencilla, rápida y escalable para trabajar con datos textuales no estructurados, siendo ideal para tareas a gran escala.

---

## 🛠️ Creación de Modelos con spaCy

spaCy ofrece modelos preentrenados en varios idiomas como español, inglés, francés, italiano, entre otros.

El modelo de español (`es_core_news_md`) incluye:
- ~500,000 keys
- ~20,000 vectores únicos (300 dimensiones)
- Componentes: `parser`, `tok2vec`, `morphologizer`, `senter`, `lemmatizer`, entre otros.

### 📥 Instalación y carga del modelo en español:

```python
!python -m spacy download es_core_news_md

import spacy
import es_core_news_md

nlp = es_core_news_md.load()
```

---

## ✂️ Detección de Oraciones

Permite dividir un texto en oraciones:

```python
text = ("Gus es un desarrollador en Python actualmente trabajando para una compañía Fintech en Londres Inglaterra. "
        "Se encuentra interesado en aprender NLP.")
t = nlp(text)

oraciones = list(t.sents)
print(len(oraciones))
for x in oraciones:
    print(x)
```

---

## 🧱 Tokenización

Divide el texto en **tokens**, es decir, unidades básicas significativas:

```python
for token in t:
    print(token, token.idx)
```

### Atributos útiles de los tokens:

```python
for token in t:
    print(token, token.idx, token.text_with_ws, token.is_alpha, token.is_punct, token.is_space, token.shape_, token.is_stop)
```

---

## 🛑 Uso de Stopwords

```python
import spacy
from spacy.lang.es.stop_words import STOP_WORDS

print(len(STOP_WORDS))
for stop_word in list(STOP_WORDS)[:10]:
    print(stop_word)

for token in t:
    if not token.is_stop:
        print(token)
```

---

## 🌱 Lematización

Obtiene la forma base (lema) de cada palabra:

```python
for token in t:
    print(token, '-', token.lemma_)
```

---

## 🏷️ POS Tagging (Etiquetado Gramatical)

Asigna una etiqueta gramatical a cada palabra:

```python
for token in t:
    print(token, '-', token.tag_, '-', token.pos_, '-', spacy.explain(token.tag_))

nouns = []
adjectives = []

for token in t:
    if token.pos_ == 'NOUN':
        nouns.append(token)
    if token.pos_ == 'ADJ':
        adjectives.append(token)

print("Sustantivos:", nouns)
print("Adjetivos:", adjectives)
```

---

## 🧩 Noun Chunks

Extrae **frases nominales** del texto, agrupando sustantivos con palabras que los modifican:

```python
for chunk in t.noun_chunks:
    print(chunk)
```

**Ejemplo:**

Texto: `"The big red apple fell on the scared cat"`  
Noun Chunks:
- `the big red apple`
- `the scared cat`

---

## ✅ ¿Por qué usar spaCy?

- Optimizado para producción
- Rápido y preciso
- Soporte para múltiples idiomas
- Excelente para tareas de análisis de texto a gran escala

---



## 🧵 Expresiones Regulares (Regex)

Las expresiones regulares son patrones de texto utilizados para encontrar coincidencias específicas dentro de cadenas. Se originaron en los años 40 y fueron aplicadas en programación en los 70, inicialmente en el editor QED de Ken Thompson.

### ✋ Validación
Se usan comúnmente para validar campos en formularios:
- Correos electrónicos
- Contraseñas
- Números de teléfono

### 🏦 Detalles bancarios
Permiten validar:
- Códigos IFSC
- Números de tarjetas (Visa, MasterCard, etc.)

### 📊 Minería de datos
Se aplican para encontrar patrones en datos no estructurados, facilitando su análisis y conversión en valores numéricos.

### 💬 NLP
Sirven para eliminar palabras irrelevantes y analizar texto, ayudando en la limpieza y estructuración para modelos NLP.

### 🌐 Redes Sociales
Se usan en el backend de motores de búsqueda personalizados en plataformas como Google, Facebook o Twitter.

### ⚖️ Ventajas y Desventajas de Regex

| Ventajas                              | Desventajas                                       |
|---------------------------------------|----------------------------------------------------|
| Muy flexibles                         | Difíciles de leer y mantener                      |
| Procesamiento rápido                  | Difíciles de depurar si no hay coincidencia       |
| Independientes del lenguaje           | Muy dependientes de la calidad de los datos       |
| Poderosas en pocas líneas de código   | Typos pueden romper el análisis                   |

---

## 🧺 Bag of Words (BoW)

BoW es una técnica sencilla y popular para convertir texto en datos numéricos útiles para modelos de ML.

### 🧠 ¿Qué es?
- Representa un documento como una **bolsa de palabras** sin tener en cuenta el orden.
- Se basa en:
  1. Un vocabulario de palabras conocidas.
  2. La presencia o frecuencia de esas palabras.

### 📦 Aplicaciones
- Procesamiento del lenguaje natural
- Recuperación de información
- Clasificación de documentos

### 👁️ Computer Vision
También se usa para identificar patrones visuales o anomalías en imágenes.

### ⚙️ Feature Generation
Después de aplicar BoW se pueden calcular medidas como:
- Frecuencia bruta
- TF-IDF

### ⚖️ Ventajas y Desventajas de BoW

| Ventajas                                        | Desventajas                                         |
|-------------------------------------------------|------------------------------------------------------|
| Flexibilidad en múltiples casos de uso         | Diseño del vocabulario requiere cuidado             |
| Fácil de entender y programar                  | Resulta en vectores dispersos difíciles de modelar  |
| Aplicable en muchos contextos                  | Ignora el orden de las palabras (pierde significado)|
| Permite construir modelos elementales          | Difícil generar insights con poca información       |

---

## 📈 TF-IDF (Term Frequency - Inverse Document Frequency)

TF-IDF es una técnica que asigna peso a las palabras basado en:
- Su frecuencia en un documento (TF)
- Su rareza en el corpus completo (IDF)

### 💡 ¿Por qué TF-IDF?
- Algunas palabras aparecen muy seguido pero no aportan valor.
- TF-IDF penaliza palabras comunes y resalta las importantes.

### 🔣 Fórmula

```text
TF(term, doc) = (Frecuencia del término en el documento) / (Número total de términos del documento)
IDF(term) = log(Número total de documentos / Número de documentos que contienen el término)
TF-IDF(term, doc) = TF(term, doc) * IDF(term)
```

### 🛠️ Uso
- Representar documentos en un espacio vectorial
- Construcción de buscadores
- Priorización de keywords

---