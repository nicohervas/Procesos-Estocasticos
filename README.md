# Simulaciones de Procesos Estocásticos

En este repositorio se recogen simulaciones y visualizaciones de tres procesos estocásticos fundamentales.
---
## Paseo Aleatorio Simple (PAS)

El paseo aleatorio simple es uno de los procesos estocásticos más básicos. En cada paso, el proceso se mueve a uno de sus estados vecinos con cierta probabilidad. Es la base de muchos modelos en física, biología y finanzas, y sirve como punto de partida para entender procesos más complejos.

En el archivo Simulacion_PAS se incluyen simulaciones de trayectorias del PAS y visualizaciones de su comportamiento.

## Procesos Gaussianos (GP)

Un proceso gaussiano es una colección de variables aleatorias tal que cualquier subconjunto finito de ellas sigue una distribución normal multivariante. Quedan completamente caracterizados por su función de media y su función de covarianza (o kernel). Son ampliamente usados en machine learning para regresión e inferencia bayesiana.

En Simulacion_GPs se incluyen simulaciones y visualizaciones de procesos gaussianos con diferentes kernels.

## Cadenas de Markov (MC)

Una cadena de Markov es un proceso estocástico en el que el estado futuro solo depende del estado presente, y no de los estados anteriores (propiedad de Markov). Quedan completamente caracterizadas por su matriz de transición. 

En Simulacion_MCs se simulan trayectorias, se estudia la distribución marginal y se ilustran empíricamente el teorema de convergencia de MCs y el teorema ergódico.
