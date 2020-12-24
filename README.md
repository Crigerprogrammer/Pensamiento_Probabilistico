# Programación Probabilística
--

- La programación probabilística utiliza probabilidades y modelos probabilísticos para ejecutar cómputos.
- Se utiliza en una gran cantidad de campos: investigación científica, inteligencia artificial, medicina, etc.
- Existen lenguajes y librerías especializadas para ejecutar este tipo de cómputo, como Pyro de Uber.

### Teorema de Bayes
P(A | B) = P(A AND B) / P(B)

### Aplicaciones del teorema de bayes
El Teorema de Bayes es uno de los mecanismos matemáticos más importantes en la actualidad. A grandes rasgos, nos permite medir nuestra certidumbre con respecto a un suceso tomando en cuenta nuestro conocimiento previo y la evidencia que tenemos a nuestra disposición. El Teorema de Bayes permea en tu vida diaria, desde descubrimientos científicos hasta coches autónomos, el Teorema de Bayes es el motor conceptual que alimenta mucho de nuestro mundo moderno.

En esta lectura me gustaría darte ejemplos de cómo se utiliza en la vida moderna para que puedas comenzar a implementarlo en tus proyectos, análisis y hasta en
tu vida personal.

### Inteligencia Artificial
El Teorema de Bayes es central en el desarrollo de sistemas modernos de inteligencia artificial. Cuando un coche autónomo se encuentra navegando en las calles, tiene que identificar todos los objetos que se encuentran en su “campo de visión” y determinar cuál es la probabilidad de tener una colisión. Esta probabilidad se actualiza con cada movimiento de cada objeto y con el propio movimiento del vehículo autónomo. Esta constante actualización de probabilidades es lo que permite que los vehículos autónomos tomen decisiones
acertadas que eviten accidentes.

### GIGO (Garbage in, Garbage out)
- La calidad de nuestros datos es igual de fundamental que la precisión de nuestros cómputos.
- Cuando los datos son errados, aunque tengamos un cómputo prístino nuestros resultados serán erróneos.
- En pocas palabras: con datos errados las conclusiones serán erradas.

En dos ocasiones me han preguntado (miembros del parlamento) 'Disculpe, Sr. Babbage, si introduce en la máquina números incorrectos, la respuesta correcta saldrá'. Me cuesta trabajo apreciar la confusión de ideas quepuede provocar dichas preguntas.

### Imágenes engañosas
- Las visualizaciones son muy importantes para entender un conjunto de datos.
- Sin embargo, cuando se juega con la escala se puede llegar a conclusiones incorrectas
- Nunca se debe confiar en una gráfica sin escalas o etiquetas

### Cum Hoc Ergo Propter Hoc
- Dos variables están positivamente correlacionadas cuando se mueven en la misma dirección y negativamente correlacionadas cuando se mueven en direcciones opuestas.
- Correlación no implica casualidad.
- Pueden existir variables escondidas que generen la correlación
- Después de esto, eso; entonces a consecuencia de esto, eso.

### Prejuicio en el muestreo
- Para que un muestreo pueda servir como base para la inferencia estadística tiene que ser aleatorio y representativo.
- El prejuicio en el muestreo elimina la representividad de las muestras.
- A veces conseguir muestras es difícil, por lo que se utiliza a la población de más fácil acceso (caso estudios universitarios)

### Falacia del francotirador de Texas
- Esta falacia se da cuando no se toma la aleatoriedad en consideración.
- También sucede cuando uno se enfoca en la similitudes e ignora las diferencias.
- Cuando fallamos al tener una hipótesis antes de recolectar datos estamos en alto riesgo de caer en esta falacia (muy común en Data Science)

### Porcentajes Confusos
- Cuando no sabemos la cuenta total del cual se obtiene un porcentaje tenemos el riesgo de concluir falsos resultados.
- Siempre es importante ver el contexto
- Los porcentajes, en vacio, no significan mucho.
**EJEMPLO**
- Escuela A incrementó su rendimiento en 25%
- Escuela B incrementó su rendimiento en 10%
- Escuela C incrementó su rendimiento en 5%s
**2DO EJEMPLO**
- En 1970, 12,5 millones de jóvenes vivían con sus padres.
- En 2015 esta cifra se incrementó a 18,6 millones.
- ¿Esto representa un incremento del 48%?