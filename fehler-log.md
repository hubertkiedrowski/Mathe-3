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
