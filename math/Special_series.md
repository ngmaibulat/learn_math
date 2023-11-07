---

marp: true
theme: gaia
_class: lead
paginate: true
backgroundColor: #000
backgroundImage: url('https://marp.app/assets/hero-background.svg')

---
# Ряд Фурье (Тригомаметрическая форма)

$$ f(x) \in [-T,T] $$
### Определение

Ряд Фурье — тригонометрический ряд, коэффициенты которого вычислены по формулам Эйлера-Фурье. Колмогоров построил пример суммируемой - периодической функции, ряд Фурье которой расходится в каждой точке.

---

$$ a_0 = \frac{1}{T}\int_{-T}^{T} f(x) \; dx $$
$$ a_n = \frac{1}{T}\int_{-T}^{T} f(x) \cdot \cos \frac{\pi nx}{T} \; dx $$

$$ b_n = \frac{1}{T}\int_{-T}^{T} f(x) \cdot \sin \frac{\pi nx}{T} \; dx $$

$$ f(x) = \frac{a_0}{2} + \sum_{n=1}^{\infty} a_n \cdot \cos \frac{\pi nx}{T} + b_n \cdot \sin \frac{\pi nx}{T}  $$

---

# Ряд Фурье (Компллексная форма)

$$ f(x) \in [-T,T] $$

$$ f_n = \frac{1}{2T}\int_{-T}^{T} f(x) \cdot e^{-\frac{in\pi x}{T}} \; dx $$

$$ f(x) = \sum_{n=-\infty}^{\infty} f_n \cdot e^{-\frac{in\pi x}{T}} $$

---

# Ряд Тейлора

### Определение

Ряд Тейлора — разложение функции в бесконечную сумму степенных функций. Частный случай разложения в ряд Тейлора в нулевой точке называется рядом Маклорена.

$$ f(x) = \sum_{n=0}^{\infty} \frac{d^nf}{dx^n}(0) \frac{x^n}{n!} $$

$$ f(x) = \sum_{n=0}^{\infty} \frac{d^nf}{dx^n}(a) \frac{(x-a)^n}{n!} $$

---

# Пример
Пусть

$$ f(x) = \cos x $$

| $\frac{d^nf}{dx^n}(0)$ | n |
|---|---|
|$\cos 0$ | 1 |
|$-\sin 0$ | 0 |
|$-\cos 0$ | -1 |
|$\sin 0$ | 0 |

---

$\frac{d^nf}{dx^n}(0)$ - не равен нулю только при чётных n

$$ f(x) = \sum_{n=0}^{\infty} (-1)^n \frac{x^{2n}}{(2n)!} $$

$$ e^x = \sum_{n=0}^{\infty} \frac{x^n}{n!} $$