---
layout: post
title: Infinitud de números primos
subtitle: Una prueba topológica
comments: true
mathjax: true
author: Jhixon Macías
---

En este, mi primer post, quiero hacer un esbozo de los pasos (generales) de la demostración topológica de la infinitud de los números primos presentada [aquí](https://math.colgate.edu/~integers/y47/y47.pdf).

###### Esbozo

- Considerar el espacio topológico $$X=(\mathbb{N},\tau)$$ donde $$\tau$$ es la topología generada por la base $$\beta:=\{\sigma_n: n\in\mathbb{N}\}$$ y $$\sigma_n:=\{m\in\mathbb{N}: \gcd(n,m)=1\}$$. Probar que en efecto $$X$$ es un espacio topológico.
- Sea $$\mathbb{P}$$ el conjunto de los números primos. Probar que la infinitud de los números primos es equivalente a que $$\mathbb{P}$$ sea denso en $$X$$.
- Demostrar que $$P$$ es denso en $$X$$ si y solo si $$P$$ es denso en  $$\mathbb{N}\setminus\{1\}$$ con la topología de subespacio heredada de $$\tau$$. A este último espacio lo denotamos por $$X_1$$.
- Demostrar que $$CL_{X_1}(\mathbb{P})=\mathbb{N}\setminus{1}$$ y concluir. Aquí $$CL_{X_1}(\mathbb{P})$$ es la calusura de $$\mathbb{P}$$ en $$X_1$$.

