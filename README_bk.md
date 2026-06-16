# 🏭 Buscador de Bienes de Capital | Decreto 379/01

Herramienta interna del Banco de la Nación Argentina para consultar si una posición arancelaria NCM califica como **Bien de Capital** según el Decreto 379/01.

## 📊 Datos
- **754 posiciones NCM** del Anexo IF-2022-26048694-APN-SIECYGCE#MDP
- 10 categorías de referencias/excepciones

## 📁 Archivos

```
buscador-bienes-capital/
├── buscador_bienes_capital.html  ← Página web
├── bienes_capital_ncm.json       ← Base de datos (754 NCM)
├── index.html                    ← Redirección
├── .nojekyll                     ← Bypass Jekyll (archivo vacío)
└── README.md
```

## 🚀 Deploy en GitHub Pages

1. Crear repo **público**: `buscador-bienes-capital`
2. Subir todos los archivos
3. Crear archivo vacío `.nojekyll` en la raíz
4. **Settings → Pages → Source: GitHub Actions**
5. Clic en **Configure** en "Static HTML" → **Commit changes**
6. URL: `https://TU-USUARIO.github.io/buscador-bienes-capital/`
