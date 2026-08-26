# TP01 - Operaciones 1

## Automatización con Bash
Script que automatiza 3 tareas de administraciÃ³n de sistemas Linux Ubuntu.

## Tareas automatizadas
1. **Backup con timestamp**: Copia archivos del directorio especificado.
2. **Limpieza de archivos viejos**: Elimina backups con mÃ¡s de N dÃ­as de antigÃ¼edad.
3. **Reporte de salud**: Genera un informe detallado de CPU, memoria, disco y procesos.

## Uso
Ejecutar en Bash:
```bash
bash scripts/sistema.sh [directorio_origen] [dias_retencion]

# Uso con valores por defecto
bash scripts/sistema.sh

# Especificando directorio y retenciÃ³n de 3 dÃ­as
bash scripts/sistema.sh /var/log 3

devops-TP01/
|--- scripts/
  |---sistema.sh
|---logs/
  |---sistema.log
â |---reporte_FECHA.txt
|---backups/
|---README.md
