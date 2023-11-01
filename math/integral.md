---

marp: true
theme: gaia
_class: lead
paginate: true
backgroundColor: #000
backgroundImage: url('https://marp.app/assets/hero-background.svg')

---

# Feynman technique

$$ \int_{0}^{\infty} e^{-x^2} \cdot \cos(x^2)dx = \; ? $$

---

$$ I(a) = \int_{0}^{\infty} e^{-x^2} cos(ax^2) dx \rightarrow $$

RP is Real part

RP(a+ib) = a

$$ \rightarrow RP ( \int_{0}^{\infty} e^{-x^2} \cdot e^{ax^2i} dx ) = RP ( \int_{0}^{\infty} e^{-x^2(1-ai)} dx) \rightarrow $$

$$ \rightarrow RP( \frac{\sqrt{\pi}}{2\cdot \sqrt{1-ai}} ) $$

---

# We know

$$ \int_{0}^{\infty} e^{-ax^2} dx = \frac{1}{2} \sqrt{\frac{\pi}{a}} $$

$$ 1-ai = \sqrt{1^2 + a^2} \cdot e^{i\arctan{-a}} $$
$$ \sqrt{1-ai} = \sqrt[4]{1^2+a^2} \cdot e^{\frac{1}{2}\arctan{-a}} $$

---

$$ \cos \frac{x}{2} = \sqrt{\frac{1+\cos x}{2}} $$

$$ \cos \arctan -a  = \cos \arctan a = \frac{1}{\sqrt{1+a^2}} $$

$$ \cos \frac{1}{2} \cdot \arctan a = \sqrt{\frac{1+\frac{1}{\sqrt{1+a^2}}}{2}} = \frac{1}{\sqrt{2}} \cdot \frac{\sqrt{\sqrt{a^2+1}+1}}{\sqrt[4]{1+a^2}} $$ 

---

# Solving

$$ \frac{1}{\sqrt{1-ai}} = \frac{1}{\sqrt[4]{1^2+a^2} \cdot e^{\frac{1}{2}\arctan{-a}}} = \frac{1}{\sqrt[4]{1^2+a^2}} \cdot e^{\frac{-i}{2} \arctan (-a) } \rightarrow$$

$$ \rightarrow \frac{1}{\sqrt[4]{1^2+a^2}} \cdot (\cos(\frac{1}{2}\arctan(-a)) - i \sin(\frac{1}{2}\arctan(-a)) ) $$

---

# Simplification

$$ RP( \frac{\sqrt{\pi}}{2\cdot \sqrt{1-ai}} ) = \frac{\sqrt{\pi}}{2} \cdot RP( \frac{1}{\sqrt[4]{1^2+a^2}} \cdot (\cos(\frac{1}{2}\arctan(-a)) - i \sin(\frac{1}{2}\arctan(-a)) )) \rightarrow $$

$$ \rightarrow \frac{\sqrt{\pi}}{2} \cdot \frac{1}{\sqrt[4]{1^2+a^2}} \cdot \frac{1}{\sqrt{2}} \cdot \frac{\sqrt{\sqrt{a^2+1}+1}}{\sqrt[4]{1+a^2}} \rightarrow $$

$$ \int_{0}^{\infty} e^{-x^2} \cdot \cos(x^2)dx = \frac{\sqrt{\pi}}{2\sqrt{2}} \cdot \frac{\sqrt{\sqrt{a^2+1}+1}}{\sqrt{a^2+1}} $$
