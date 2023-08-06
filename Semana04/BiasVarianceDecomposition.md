# Descomposición en sesgo y varianza del error

La descomposición en __sesgo__ y __varianza__ se puede escribir de la siguiente forma:

$$
error(\mathbf{x}) = bias(\mathbf{x})^2 + Var\left[\hat{f}_{\mathcal{D}}(\mathbf{x})\right]
$$

Este error se puede atribuir a una combinación de tres tipos de errores:

- Error sistemático de predicción inherente al modelo (sesgo)
- Fluctuación del modelo debido a los datos de entrenamiento (varianza)
- Ruido

El ruido no se puede reducir, mientras que el sesgo y la varianza se pueden controlar a través de técnicas de selección de modelos (cross-validation).

Vamos a derivar la ecuación:

$$
\textcolor{blue}{error(\mathbf{x})} = \textcolor{purple}{bias(\mathbf{x})^2} + \textcolor{orange}{Var\left[\hat{f}_{\mathcal{D}}(\mathbf{x})\right]}
$$

$$
\mathbb{E}_{\mathcal{D},y} = \left{ \left(y - \hat{f}_(y - \hat{f}(\mathbf{x}) \right) ^2 \right}
$$
