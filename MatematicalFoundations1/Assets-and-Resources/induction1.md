## Complex Numbers & Induction: Step-by-Step Roadmap

### Step 1: Proof by Induction $P(n+1)$

* **Goal:** Find what the formula looks like for the next term $n+1$.
* **Action:**
1. Take the $n$-th term on the left side and replace every $n$ with $(n+1)$. Simplify the result to find the new ending term.
2. Take the right-hand side formula and replace every $n$ with $(n+1)$. Simplify the fraction.
3. Combine them to form the full $P(n+1)$ equation.



---

### Step 2: Fractions & Standard Form ($a + bi$)

* **Goal:** Simplify complex division into a single real part $a$ and imaginary part $b$.
* **Action:**
1. **Order of Operations:** Multiply out any terms in the numerator or denominator first (remember that $i^2 = -1$).
2. **Combine Like Terms:** Group all real numbers together and all $i$ terms together.
3. **Rationalize Denominator:** Multiply both the top and bottom by the **conjugate** of the denominator (change the sign of $i$: $c - di \to c + di$).
4. **Split:** Write as two separate fractions: $\frac{\text{Real}}{\text{Denom}} + \frac{\text{Imag}}{\text{Denom}}i$.



---

### Step 3: Converting to Polar Form ($r_\theta$)

* **Goal:** Find the distance (modulus $r$) and angle (argument $\theta$).
* **Action:**
1. **Modulus $r$:** Use the distance formula $r = \sqrt{a^2 + b^2}$.
2. **Reference Angle:** Calculate $\tan(\alpha) = \left\vert{}\frac{b}{a}\right\vert{}$.
3. **Check Quadrant:**
* Quadrant I ($a>0, b>0$): $\theta = \alpha$
* Quadrant II ($a<0, b>0$): $\theta = \pi - \alpha$ (or $180^\circ - \alpha$)
* Quadrant III ($a<0, b<0$): $\theta = \pi + \alpha$ (or $180^\circ + \alpha$)
* Quadrant IV ($a>0, b<0$): $\theta = 2\pi - \alpha$ (or $360^\circ - \alpha$)





---

### Step 4: Powers of Complex Numbers ($z^n$)

* **Goal:** Calculate $z^n$ without expanding long algebraic terms.
* **Action:**
1. Convert the base complex number into polar/exponential form $r_\theta$.
2. **New Modulus:** Raise $r$ to the power: $r_{\text{new}} = r^n$.
3. **New Angle:** Multiply $\theta$ by the power: $\theta_{\text{new}} = n \cdot \theta$.
4. **Simplify Angle:** Subtract full turns ($2\pi$ or $360^\circ$) if the angle exceeds a full circle.



---

### Step 5: Finding $n$-th Roots ($\sqrt[n]{z}$)

* **Goal:** Find all root angles for an equation like $\sqrt[n]{w}$.
* **Action:**
1. Convert the inner number $w$ to polar form to get its starting angle $\theta_w$.
2. Use the root angle formula for each index $k = 0, 1, 2, \dots, n-1$:

$$\theta_k = \frac{\theta_w + k \cdot 360^\circ}{n} \quad \text{(in degrees)}$$


3. Plug in $k = 0$ for the 1st root, $k = 1$ for the 2nd root, and so on.
