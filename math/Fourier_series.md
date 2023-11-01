---

marp: true
theme: gaia
_class: lead
paginate: true
backgroundColor: #000
backgroundImage: url('https://marp.app/assets/hero-background.svg')

---
# Fourier series (Trigonometry form)

$$ f(x) \in [-T,T] $$

The Fourier series converges, if the function f(x) is continuous on the interval $[-T,T]$

---

Odds for series:

$$ a_0 = \frac{1}{T}\int_{-T}^{T} f(x) \; dx $$
$$ a_n = \frac{1}{T}\int_{-T}^{T} f(x) \cdot \cos \frac{\pi nx}{T} \; dx $$

$$ b_n = \frac{1}{T}\int_{-T}^{T} f(x) \cdot \sin \frac{\pi nx}{T} \; dx $$

---

$$ f(x) = \frac{a_0}{2} + \sum_{n=1}^{\infty} a_n \cdot \cos \frac{\pi nx}{T} + b_n \cdot \sin \frac{\pi nx}{T}  $$

---

# Fourier series (Complex form)

$$ f(x) \in [-T,T] $$

Odds for series:

$$ f_n = \frac{1}{2T}\int_{-T}^{T} f(x) \cdot e^{-\frac{in\pi x}{T}} \; dx $$

Series :

$$ f(x) = \sum_{n=-\infty}^{\infty} f_n \cdot e^{-\frac{in\pi x}{T}} $$ 
