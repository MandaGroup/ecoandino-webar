# Etapa 1 · Reconocimiento de dos empaques Ecoandino

Objetivos, en este orden:
0. Blanco — nibs de cacao endulzados con yacón orgánico. Referencia de usuario: IMG_6989.jpg.
1. Marrón — cacao criollo en polvo orgánico. Referencia de usuario: IMG_6990.jpg.

Ambos muestran el círculo verde «Acerca tu celular / vive la experiencia», impreso temporalmente en papel bond. Los adhesivos finales pueden alterar los detalles y necesitar una recompilación.

## Integración pendiente

1. Recortar las fotografías a las áreas frontales impresas, evitando pared, mesa y bordes que puedan no repetirse. Si se usa la bolsa completa, las arrugas pueden afectar al tracking.
2. En https://hiukim.github.io/mind-ar-js-doc/tools/compile/ cargar ambos recortes en orden [blanco, marrón], verificar puntos característicos distribuidos, descargar un único `targets.mind`.
3. Subirlo como `ecoandino-dual.mind` en esta rama de desarrollo.
4. Probar la vista previa con `?dual=1` (sin parámetro sigue funcionando `ecoandino.mind`).
5. Validar ambos productos en Safari y Chrome, cambios de ángulo, pérdidas/recuperación de tracking y duración de carga.

El código ya dispone de dos objetivos (índices 0 y 1) y reutiliza una sola escena. **El archivo compilado no está generado todavía** y no debe activarse `?dual=1` hasta subirlo.

Las fotos originales fueron proporcionadas por el usuario en la conversación y no deben sustituirse por renders.
