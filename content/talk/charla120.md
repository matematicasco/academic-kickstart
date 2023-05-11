+++
date  = "2023-05-11"
draft = false
tags  = ["Nuestro Encuentro"]
title = "Charla 120: Operadores seudo-diferenciales adélicos asociados a formas cuadráticas"
math  = true
+++


**Conferencista:**  [Óscar F. Casas](https://matematicas.netlify.app/authors/casas-o/). Profesor Escuela de Matemáticas y Estadística, Uptc.

**Fecha:** Viernes 12 de mayo de 2023, 3:00 p.m.

**Lugar:** C-119

**Resumen**

En esta charla se mostrarán los principales resultados obtenidos durante la Comisión de Investigación en la que se desarrolló el proyecto titulado: Operadores seudo-diferenciales adélicos asociados a formas cuadráticas.

Sea $\zeta(s)=\prod_{p\leq \infty}\zeta_p(s)$ la clásica función  zeta de Riemann. Dada una función suave con soporte compacto $f:\mathbb{R}^+\rightarrow\mathbb{R}$, denotamos por  $\hat{f}(s)$ su transformada de Mellin. Weil [2], [3], utilizando la ecuación funcional $\zeta(s)=\zeta(1-s)$, obtiene la fórmula explícita:


$$\hat{f}(0)+\hat{f}(1)-\sum_{\zeta(s)=0} \hat{f}(s)=-\frac{1}{2 \pi i} \oint \hat{f}(s) d \log \zeta(s)$$
$$\qquad\qquad\qquad=\sum_{p \leq \infty} \frac{1}{2 \pi i} \int_{\frac{1}{2}-i \infty}^{\frac{1}{2}+i \infty} \hat{f}(s) d \log \frac{\zeta_p(1-s)}{\zeta_p(s)} \stackrel{\text { def }}{=} \sum_{p \leq \infty} W_p(f)$$

conocida como la fórmula explícita de Weil.

En 1990 Haran [1], utilizando el grupo de adeles de los números racionales y potenciales de Riesz, encuentra una nueva interpretación de $W_p(f)$. Él muestra que todas las contribuciones locales a la fórmula explícita pueden ser expresadas en términos del generador infinitesimal de los núcleos de Riesz asociados al correspondiente cuerpo local.

En esta charla mostraré que es posible extender los resultados de  Haran a el caso de una extensión cuadrática imaginaria de $\mathbb{Q}$. Para esto, definiré la función zeta de Dedekind asociada a la extensión, el núcleo de Riesz para el cuerpo de los números complejos $\mathbb{C}$  y para las correspondientes extensiones cuadráticas de los cuerpos locales  $\mathbb{Q}_p$, las cuales incluyen las extensiones cuadráticas no ramificadas y las totalmente ramificadas. 

**Referencias**

[1] S. Haran. Riesz potentials and explicit sums in arithmetic. *Invent. Math.*, 101(3):697--703, 1990.

[2] A. Weil. Sur les \formules explicites" de la th eorie des nombres premiers. *Comm. S em. Math. Univ. Lund [Medd. Lunds Univ. Mat. Sem.]*, 1952(Tome Suppl ementaire):252--265, 1952.

[3] A. Weil. Sur les formules explicites de la th eorie des nombres. *Izv. Akad. Nauk SSSR, Ser. Mat.*, 36:3--18, 1972.
