\# IR-2026 — Ganancia Adaptativa (Control Motor / Hemiparesia)



\## Qué mide el test

Evalúa y adapta la sensibilidad del mouse (ganancia) para pacientes con ROM limitado por hemiparesia post-ACV.

\- Calibra el ROM real del paciente

\- Ajusta la ganancia del cursor en tiempo real

\- Registra tiempos de reacción, trayectorias, errores y eficiencia

\- Detecta mejora intrasesión comparando gain inicial vs final



\## Población objetivo

Pacientes adultos con hemiparesia secundaria a ACV, con rango de movimiento reducido en miembro superior.



\## Cómo instalarlo



1\. Clonar el repositorio: 
https://github.com/franciscoaringoli/IR-2026-AringoliFrancisco-ControlMotor.git

cd IR-2026-AringoliFrancisco-ControlMotor

2. Instalar dependencias:
pip install -r requirements.txt

3. Ejecutar:
py adaptive\_gain.py

## Salida de datos

Al finalizar se genera un JSON en `/results/` con: calibración, summary y datos por trial con trayectoria completa.

