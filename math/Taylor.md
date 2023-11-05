---

marp: true
theme: gaia
_class: lead
paginate: true
backgroundColor: #000
backgroundImage: url('https://marp.app/assets/hero-background.svg')


---
# Ряд Тейлора

### Определение

Ряд Тейлора — разложение функции в бесконечную сумму степенных функций. Частный случай разложения в ряд Тейлора в нулевой точке называется рядом Маклорена.


$$ f(x) = \sum_{n=0}^{\infty} \frac{d^nf}{dx^n}(0) \frac{x^n}{n!} $$

$$ f(x) = \sum_{n=0}^{\infty} \frac{d^nf}{dx^n}(a) \frac{(x-a)^n}{n!} $$

Примичание - $ \frac{d^nf}{dx}(a) $ - это n - ная в точке a

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