# Fehler-Log — Mathe Klausurvorbereitung

Wiederholungsliste meiner falsch beantworteten Aufgaben, automatisch gepflegt vom Mathe-Tutor (siehe CLAUDE.md). Status je Eintrag: offen, wiederholt, gemeistert.

<!-- Neue Eintraege unten anhaengen. Format siehe CLAUDE.md. -->

### F-1 · Differentiation: Quotientenregel · eigene Aufgabe
- Datum: 2026-06-22
- Status: offen

Aufgabe:

$$ f(x) = \frac{3x-1}{x^2+2}, \qquad f'(x) = ? $$

Mein Fehler: Im Zaehler $u'v - uv'$ das Minus nicht ueber das ganze Produkt $(3x-1)(2x)$ verteilt — der Term $-6x^2$ ging verloren und $+2x$ wurde zu $-4x$.
Richtig waere: Zaehler $= 3(x^2+2) - (3x-1)(2x) = -3x^2 + 2x + 6$, Nenner $(x^2+2)^2$.
Skript-Verweis: Korollar 35.5 (Quotientenregel)

### F-2 · Differentiation: Kettenregel · eigene Aufgabe
- Datum: 2026-06-22
- Status: offen

Aufgabe:

$$ f(x) = x^2 \cdot \sin(3x), \qquad f'(x) = ? $$

Mein Fehler: Innere Ableitung der Kettenregel vergessen (Faktor $3$) und $\cos(3)$ statt $\cos(3x)$ geschrieben.
Richtig waere: $f'(x) = 2x\sin(3x) + 3x^2\cos(3x)$ — "aeussere mal innere Ableitung".
Skript-Verweis: Satz 35.6 (Kettenregel), Satz 35.3 (Produktregel)

### F-3 · Integration: Stammfunktion · eigene Aufgabe
- Datum: 2026-06-22
- Status: offen

Aufgabe:

$$ \int_{-2}^{1} x \, dx = ? $$

Mein Fehler: Stammfunktion von $x$ mit der von $1/x$ verwechselt ($\ln$ benutzt) — $\ln(-2)$ ist zudem undefiniert.
Richtig waere: Stammfunktion von $x$ ist $x^2/2$, also $\left[x^2/2\right]_{-2}^{1} = \tfrac{1}{2} - 2 = -\tfrac{3}{2}$.
Skript-Verweis: Kapitel 36 (Stammfunktion), Lemma 36.4

### F-4 · Integration: Konstante integrieren · eigene Aufgabe
- Datum: 2026-06-22
- Status: offen

Aufgabe:

$$ \int (4x^3 - 6x^2 + 2x - 7)\, dx = ? $$

Mein Fehler: Die Konstante $-7$ falsch "integriert" (als $-7^2/2$ geschrieben) statt zu $-7x$; ausserdem $+C$ vergessen.
Richtig waere: Eine Konstante $a$ integriert zu $a\cdot x$, also $-7 \to -7x$; Ergebnis $x^4 - 2x^3 + x^2 - 7x + C$.
Skript-Verweis: Kapitel 36 (Stammfunktion)

### F-5 · Integration: bestimmtes Integral, Vorzeichen/Grenzen · eigene Aufgabe
- Datum: 2026-06-22
- Status: offen

Aufgabe:

$$ \int_{-1}^{2} (x-1)\, dx = ? $$

Mein Fehler: Vorzeichen falsch ($1{,}5$ statt $-1{,}5$) — vermutlich $F(-1)-F(2)$ statt $F(2)-F(-1)$ gerechnet.
Richtig waere: $F(x)=x^2/2 - x$; $F(2)-F(-1) = 0 - \tfrac{3}{2} = -\tfrac{3}{2}$.
Skript-Verweis: Kapitel 36 (Hauptsatz, bestimmtes Integral)
