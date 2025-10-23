# modelacion-ede

Librería para orquestar `ModelacionEDE` sin modificar funciones matemáticas.
Uso básico:

```python
from modelacion_ede_lib import procesar_serie
resultado = procesar_serie(df=data_DUK, dt=1/252, nombre="DUK", frecuencia="días", k=1000)
print(resultado)
