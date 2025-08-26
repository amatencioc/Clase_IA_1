Subir los cuadernos del ejercicio
Ejercicio Propuesto Integrador (Se considerara ejercicio para el examen final)

Se plante el siguiente ejercicio: Limpieza de Datos

Examina cuidadosamente el archivo ‘Absenteeism-data.csv’. Luego, utiliza la siguiente guía para preparar los datos para un análisis posterior:

    Elimina la columna ‘ID’.
    Divide las razones de ausencia en múltiples variables dummym(dummy variables) y luego agrúpalas de la siguiente manera:

    Grupo 1: Columnas 1 a 14
    Grupo 2: Columnas 15, 16 y 17
    Grupo 3: Columnas 18, 19, 20 y 21
    Grupo 4: Columnas 22 a 28

    Después de hacer eso, no olvides eliminar también la columna ‘Reason for Absence’.
    Extrae el valor del mes y del día de la semana a partir de la columna ‘Date’. Luego, elimina también la columna ‘Date’.
    Convierte los datos de la columna ‘Education’ en datos binarios, mapeando el valor 0 a 1, y el valor 1 y el resto de valores encontrados en esta columna a 0.
    No olvides crear puntos de control a medida que avances. Si trabajaste correctamente, la versión final de tu DataFrame debería contener los mismos datos que los almacenados en el archivo ‘df-cleaned.csv’.