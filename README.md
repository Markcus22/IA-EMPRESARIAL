# IA-EMPRESARIAL
Agente IA empresarial con autenticación, generación de documentos y trazabilidad.


# IA-Empresarial

Este proyecto tiene como objetivo desarrollar un sistema inteligente empresarial basado en agentes IA especializados, con autenticación segura, trazabilidad documental y automatización de procesos.

## 🚀 Funcionalidades principales

- Autenticación con **Microsoft Authenticator** y **JWT**.
- Agentes IA especializados en:
  - Contratos
  - Contabilidad
  - Obras
  - Mantenimiento
- Integración con **Power Automate** y **LM Studio**.
- Generación de documentos con trazabilidad mediante gemelos digitales.
- Transferencia de documentos entre departamentos en formatos como DOCX, PDF y Excel.

## 📁 Estructura del proyecto

```
IA-Empresarial/
│
├── README.md
├── .gitignore
├── requirements.txt
├── main.py  # Punto de entrada del agente
│
├── app/
│   ├── auth/               # Autenticación con Microsoft Authenticator y JWT
│   ├── agents/             # Agentes especializados
│   │   ├── contratos/
│   │   ├── contabilidad/
│   │   ├── obras/
│   │   ├── mantenimiento/
│   ├── database/           # Conexión y modelos de base de datos
│   ├── documents/          # Creación de documentos y gemelos digitales
│   ├── integrations/       # Integraciones con Power Automate, LM Studio, etc.
│   └── utils/              # Funciones auxiliares
│
└── tests/                  # Pruebas unitarias
```

## 🛠️ Tecnologías sugeridas

- Python 3
- FastAPI
- SQLAlchemy
- JWT
- Power Automate
- LM Studio

## 📌 Autor
Marc Vicent González
