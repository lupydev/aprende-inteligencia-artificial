# 🚀 Aprende Inteligencia Artificial desde Cero

Este repositorio es una **guía completa** para aprender Inteligencia Artificial, Prompt Engineering, RAG (Retrieval-Augmented Generation) y Embeddings desde los fundamentos más básicos hasta aplicaciones prácticas avanzadas.

### 🎯 Objetivos de aprendizaje

- **Fundamentos de IA**: Comprender los conceptos básicos de inteligencia artificial y machine learning
- **Prompt Engineering**: Dominar el arte de escribir prompts efectivos para modelos de lenguaje
- **RAG (Retrieval-Augmented Generation)**: Aprender a construir sistemas que combinan búsqueda de información con generación de texto
- **Embeddings**: Entender cómo convertir texto en vectores numéricos para análisis semántico
- **Aplicaciones prácticas**: Desarrollar proyectos reales que puedas usar en tu trabajo o emprendimiento

## 🔧 Herramientas de desarrollo

- **Python**: El lenguaje principal para IA
- **LangChain**: Framework para aplicaciones con LLMs
- **Vector databases**: Pinecone, Chroma, Weaviate
- **APIs**: Integración con servicios de IA

### Instalación paso a paso

#### 1. Clona el repositorio

```bash
git clone <repository-url>
cd aprende-inteligencia-artificial
```

#### 2. Crea las variables de entorno

Crea el archivo `.env` en la raíz del repositorio copiando el siguiente comando:

```bash
cp .env.example .env
```

Edita el archivo `.env` y agrega tus secretos:

```env
# Estas no las cambies
OPENAI_BASE_URL="https://models.inference.ai.azure.com"
OPENAI_EMBEDDINGS_URL="https://models.github.ai/inference"

# Estas las cambias
GITHUB_TOKEN="tu_github_token"
LANGSMITH_TRACING="tu_langsmith_tracing"
LANGSMITH_API_KEY="tu_langsmith_api_key"
LANGSMITH_PROJECT="nombre_del_proyecto"
```

**Important:** Reemplaza el valor del placeholder con tus secretos.

#### 3. Sincroniza las dependencias

```bash
# Using uv (recommended)
uv sync

# Or using pip
pip install -r requirements.txt
```

## 🤝 Contribuciones

- **Issues de GitHub**: Para reportar problemas y bugs
- **Discussions**: Para preguntas y debates

---

## 📄 Licencia

Este proyecto está bajo la licencia [MIT](LICENSE). Puedes usar, modificar y distribuir el código libremente.
