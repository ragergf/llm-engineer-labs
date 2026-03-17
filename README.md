# LLM Engineer Labs

Repositorio oficial de **LLM Engineer Labs**, donde iré subiendo todos los labs prácticos de mi serie sobre **LLM Engineer**.

La idea de este proyecto es aprender construyendo, con ejemplos reales, código reproducible y experimentos guiados sobre modelos, prompting, contexto, tokens, control del modelo, agentes, RAG y más.

---

## Objetivo del repositorio

Este repositorio centraliza todos los labs de la serie para que puedas:

- descargar el código fácilmente
- abrirlo en Cursor
- instalar dependencias de forma consistente
- sincronizar tu entorno con `uv`
- seguir la serie paso a paso mientras practicas

---

## Repositorio oficial

Clona este repositorio desde GitHub:

```bash
git clone https://github.com/ragergf/llm-engineer-labs.git
```

---

## 1) Descargar el proyecto desde GitHub

### Opción A — Con Git desde terminal

```bash
cd ~/Documents
git clone https://github.com/ragergf/llm-engineer-labs.git
cd llm-engineer-labs
```

### Opción B — Descargar ZIP desde GitHub

1. Entra al repo en GitHub
2. Haz clic en **Code**
3. Descarga el ZIP
4. Descomprímelo
5. Abre la carpeta

---

## 2) Abrir el proyecto en Cursor

1. Abre **Cursor**
2. Ve a **File > Open Folder**
3. Selecciona `llm-engineer-labs`
4. Espera indexación

---

## 3) Instalar uv

```bash
curl -LsSf https://astral.sh/uv/install.sh | sh
```

Verifica:

```bash
uv --version
```

---

## 4) Sincronizar dependencias

```bash
cd llm-engineer-labs
uv sync
```

---

## 5) Problemas comunes

**uv no encontrado**
→ Reinicia terminal

**.venv no existe**
→ Ejecuta `uv sync`

**Errores dependencias**
→ `git pull && uv sync`

---

## 6) Filosofía

No es solo usar IA.

Es pensar como un **LLM Engineer**:

- Controlar modelos
- Optimizar tokens
- Diseñar prompts
- Construir sistemas reales

---

## Autor

**Rager / System Handler**

GitHub:
https://github.com/ragergf/llm-engineer-labs.git
