# Código de DocuZen

Se incluyen íntegros los archivos distribuidos en los ZIP de GitHub archivados en Drive el 07/11/2026. Directorios `Web_SaaS` y `Escritorio_Edge` conservan estructura de los repositorios.

**Web:** `cd Web_SaaS`, `npm ci`, `npx prisma generate`, `npm run dev`. Crear MySQL y .env.local con secretos suministrados por el administrador.

**Escritorio:** `cd Escritorio_Edge`; en PowerShell: `py -3.12 -m venv .venv`; `.\.venv\Scripts\Activate.ps1`; `python -m pip install -r requirements.txt`; `python main.py`. OCR requiere Poppler/Tesseract.

Para pasos y precauciones, leer `Manual_de_Instalacion_DocuZen_CSWII.docx`. No asuma que los archivos .db son la base de producción.
