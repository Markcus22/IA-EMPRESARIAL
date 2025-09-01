# IA-EMPRESARIAL
Agente IA empresarial con autenticación, generación de documentos y trazabilidad.

**ARQUITECTURA DE DATOS**

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
