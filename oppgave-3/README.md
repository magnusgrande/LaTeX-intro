# 3. Matematikkommandoer

## 3.1 Introduksjon av *align*, *equation* og *$*

Oppgave 3 handler om hvordan sette opp et matematikkmiljø (environment) i LaTeX. Dette kan vi gjøre med de tre introduserte kommandoene: align, equation og ved å pakke ting inn i $.

**Align** bruker vi for å vise utregning, utlede noe eller presentere flere linjer med ligninger.

```latex
\begin{align}
F &= ma \\
E &= mc^2 \\
V &= IR
\end{align}
```
🔎 Undersøk gjerne hvilken funksjoner `&` har i kodeblokken over.
<img width="1101" height="199" alt="image" src="https://github.com/user-attachments/assets/9cc4faf7-0442-4118-926a-62ee3a62a7d2" />


**Equation** er gjerne for å presentere en enkelt formel eller ligning som kan bli referert til senere.
```latex
\begin{equation}
E = mc^2
\end{equation}
```
<img width="877" height="183" alt="image" src="https://github.com/user-attachments/assets/eb747cfc-31d6-4a20-a5bc-8b68cb354aca" />


**$** bruker vi dersom vi skriver tekst og ønsker introdusere noen mindre matematiske variabler eller kommandoer inne i tekstform.

```latex
Teksteksempel som inneholder en matematisk variabel $\ell$ etterfølgt av mer tekst.
```

<img width="874" height="55" alt="image" src="https://github.com/user-attachments/assets/833c7cf6-3421-4717-8598-e64d78f2a364" />


### 🌱3.2: Inline ($)
Bruk inline til å skrive følgende i Overleaf:
#### Oppgave 1:
Newtons andre lov kan skrivast som $F=ma$

#### Oppgave 2:
Arealet til ein sirkel er $A=πr^2$, og omkrinsen er $C=2πr$


### 🌳3.3: Equation
Bruk equation til å skrive følgende i Overleaf:

#### Oppgave 1:
$E_k = \frac{1}{2}mv²$

#### Oppgave 2:
$S_n = \frac{n(a_1+a_n)}{2}$


### 🌲3.4: Align

Bruk align til å løse matematisk følgende i Overleaf.

#### Oppgave 1:  Løs for x
$y = 2x+3$


### 🔥3.5: Kombinasjon
Bruk alt du har lært om inline, equation og align for å gjenskape følgende:

Vi starter med Ohms lov, $V = IR$.
For en krets med konstant $R$ kan vi utlede:
$I = \frac{V}{R}$
Dersom $V(t) = V_0sin(ωt)$, får vi:
$I(t) = \frac{V_0sin(ωt)}{R}$
