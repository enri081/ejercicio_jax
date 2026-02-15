# Actividad JAX

Este repo contiene mi actividad en **JAX** en un cuaderno Jupyter.

## Archivos
- `Actividad_JAX.ipynb`: cuaderno con la práctica.
- `requirements.txt`: librerías necesarias.
- `entorno/`: entorno virtual.

## Qué se hace en el cuaderno
- Operaciones básicas con `jax.numpy`
- `grad` para derivadas automáticas
- `jit` para compilar y comparar tiempos
- `vmap` para vectorizar funciones
- Ejemplo simple de entrenamiento (regresión lineal) con descenso de gradiente

## Instalación
Con el entorno activado:

```bash
pip install -r requirements.txt
```

## Bibliografía / Recursos

### Documentación oficial (la principal)
- JAX (home / overview): https://jax.dev/
- Quickstart (cómo pensar en JAX): https://docs.jax.dev/en/latest/quickstart.html
- Key concepts (grad/jit/vmap y conceptos clave): https://docs.jax.dev/en/latest/key-concepts.html
- Referencia de `vmap`: https://docs.jax.dev/en/latest/_autosummary/jax.vmap.html
- Repositorio oficial (README + ejemplos): https://github.com/jax-ml/jax
