# Partial-Differentiation

## 3.3 VARIABLE TREATED AS CONSTANT

Consider $\( z = x^2 - y^2 \)$. Introducing polar coordinates $\( x = r \cos \theta \)$, $\( y = r \sin \theta \)$, we have $\( r^2 = x^2 + y^2 \)$ and $\( \theta = \tan^{-1} \frac{y}{x} \)$. To find $\( \frac{\partial z}{\partial \theta} \)$ with different variables treated as constant, i.e., to find $\( \left(\frac{\partial z}{\partial \theta}\right)_r \)$, $\( \left(\frac{\partial z}{\partial \theta}\right)_x \)$, $\( \left(\frac{\partial z}{\partial \theta}\right)_y \)$.

**Variable treated as constant:** $\( \left(\frac{\partial z}{\partial \theta}\right)_r \)$, usually read as "partial derivative of $\( z \) w.r.t. \( \theta \)$, with $\( r \)$ held constant". However, the important point is that $\( z \)$ has been written as a function of the variables $\( \theta \)$ and $\( r \)$ only and then differentiated w.r.t. $\( \theta \)$, keeping $\( r \)$ constant. Thus

$\[
z = x^2 - y^2 = r^2 \cos^2 \theta - r^2 \sin^2 \theta
\]$

$\[
\left(\frac{\partial z}{\partial \theta}\right)_r = 2r^2 \left(\cos \theta (-\sin \theta) - \sin \theta \cos \theta \right)
\]$

$\[
= -4r^2 \sin \theta \cos \theta
\]$ (1)

To find $\( \left(\frac{\partial z}{\partial \theta}\right)_x \)$, express $\( z \)$ in terms of $\( \theta \)$ and $\( x \)$ as

$\[
z^2 = x^2 - y^2 = x^2 - x^2 \tan^2 \theta.
\]$

Now,

$\[
\left(\frac{\partial z}{\partial \theta}\right)_x = x^2 \left(0 - 2 \tan \theta \cdot \sec^2 \theta \right) \tag{2}
\]$ (2)

To find $\( \left(\frac{\partial z}{\partial \theta}\right)_y \)$, express $\( z \)$ in terms of $\( \theta \)$ and $\( y \)$ as

$\[
z = x^2 - y^2 = y^2 \cot^2 \theta - y^2
\]$

Now,

$\[
\left(\frac{\partial t}{\partial \theta}\right)_y = y^2 \left(2 \cdot \cot \theta \cdot (-\csc^2 \theta) \right) \tag{3}
\]$ (3)

These three expressions (1), (2), (3) for $\( \frac{\partial z}{\partial \theta} \)$ have different values and are derivatives of three different functions.

## WORKED OUT EXAMPLES

**Example 1:** If $\( z = x^2 + 2y^2 \)$, $\( x = r \cos \theta \)$, $\( y = r \sin \theta \)$, find the partial derivatives:

**a.** $\( \left( \frac{\partial z}{\partial x} \right)_y \)$

**b.** $\( \left( \frac{\partial z}{\partial x} \right)_\theta \)$ 

**c.** $\( \left( \frac{\partial z}{\partial \theta} \right)_r \)$ 

**d.** $\( \frac{\partial^2 z}{\partial r \partial y} \)$


**Solution:** Here $\( z = x^2 + 2y^2 \)$, $\( r^2 = x^2 + y^2 \)$, $\( \tan \theta = \frac{y}{x} \)$

**a.** To get $\( \left( \frac{\partial z}{\partial x} \right)_y \)$, $\( z \)$ should be expressed as a function of $\( x \)$ and $\( y \)$  
i.e.,

$\[
z = x^2 + 2y^2
\]$

Differentiating partially w.r.t. $\( x \)$, with $\( y \)$ held constant:

$\[
\left( \frac{\partial z}{\partial x} \right)_y = 2x
\]$

**b.** Express z as function of x and θ

z = x² + 2y² = x² + 2x² + tan² θ

Differentiating partially w.r.t. x, keeping θ con-
stant

$(∂z/∂x)_θ$ = 2x + 4x tan² θ = 2x(1 + 2 tan² θ)

**c.** Express z as function of r and θ

z = r² cos² θ + 2r² sin² θ

$(∂z/∂θ)_r$ = 2r² cos θ(- sin θ) + 2r²2 · sin θ · cos θ
           = r² · sin 2θ

**d.** z = (r² - y²) + 2y² = r² + y², ∂z/∂y = 2y,
   ∂²z/∂r∂y = 0.

**Example 2:** If x² = au + bv; y² = au - bv
prove that

$(∂u/∂x)_y$ $(∂x/∂u)_v$ = 1/2 = $(∂v/∂y)_x$ $(∂y/∂v)_u$

**Solution:** Solving

x² = au + bv                      (1)
             
y² = au - bv                      (2)
             
we get u = (x² + y²)/2a                  (3)

 v = (x² - y²)/2b                  (4)

Differentiating (3) partially w.r.t. x, keeping y con-
stant, we get

$(∂u/∂x)_y$ = 2x/2a = x/a           (5)

Differentiating (1) partially w.r.t. u, keeping v con-
stant, we get

2x $(∂x/∂u)_v$ = a ∴ $(∂x/∂u)_v$ = a/2x (6)

From (5) and (6)

(∂u/∂x)_y (∂x/∂u)_v = x/a · a/2x = 1/2

Similarly differentiating (4) and (2) partially w.r.t. y
and v respectively, we get

$(∂v/∂y)_x$ = -2y/2b = -y/b          (7)

$2y(∂y/∂v)_u$ = -b ∴ $(∂y/∂v)_u$ = -b/2y (8)

From (7) and (8)

$(∂v/∂y)_x$ · $(∂y/∂v)_u$ = (-y/b)(-b/2y) = 1/2

## EXERCISE

1. Let z = x² - y² and x = r cos θ, y = r sin θ.

   Find **a.** $(∂z/∂r)_θ$
   
     **b.** $(∂z/∂r)_x$
   
   **c.** $(∂z/∂r)_y$
   
   a. **Hint:** z = r²  (cos² θ - sin² θ)
   
   b. **Hint:** z = 2x² - r²
   
   c. **Hint:** z = r² - 2y²
   

*Ans.* **a.** 2r(cos² θ - sin² θ)

  **b.**  -2r

  **c.** 2r

  2. Let z = x² + 2y² and x = r cos θ,
   y = r sin θ.

   Find   **a.** $(∂z/∂y)_r$
   
   **b.** $(∂z/∂θ)_x$ 
   
   **c.** $(∂z/∂r)_x$
   
   **d.** $∂²z/∂y∂θ$
   
   **e.** $∂²z/∂r∂θ$.

Ans. **a.** 2y 

**b.** 4r² tan θ  

**c.** 2x  

**d.** -4x cosec²θ

**e.** 2r sin 2θ

3. If u = lx + my, v = mx - ly show that

   $(∂u/∂x)_y$ $(∂x/∂u)_v$ = l²/(l² + m²),

   $(∂v/∂v)_x$ $(∂v/∂y)_u$ = (l² + m²)/l²

4. If f(p, v, t) = 0 show that
   
   $(∂p/∂T)_v$ = -$(∂v/∂T)_p$ $(∂p/∂v)_T$

   **Hint:** $(∂p/∂T)_v$ = -$f_T/f_p$, $(∂v/∂T)_p$ = -$f_T/f_v$,
         $(∂p/∂v)_T$ = -$f_v/f_p$.

5. If E = f(p, T) and T = g(p, v) show that

   $(∂E/∂p)_v$ = $f_p$ + $f_T g_p$

  = $(∂E/∂p)_T$ + $(∂E/∂T)_p$ $(∂T/∂p)_v$

6. If x = r cos θ, y = r sin θ find
    
   **a.** $(∂x/∂r)_θ$
   
   **b.** $(∂x/∂θ)_r$

   **c.** $(∂θ/∂x)_y$

   **d.** $(∂θ/∂r)_x$

   **e.** $(∂y/∂x)_r$

   **f.** $(∂x/∂y)_θ$

   **g.** $(∂r/∂θ)_x$

   **h.** $(∂θ/∂r)_y$

Ans. **a.** cos θ  

**b.** -r sin θ    

**c.** -r⁻¹ sin θ

**d.** r⁻¹ cos θ  

**e.** - cot θ     

**f.** cot θ

**g.** r tan θ    

**h.** -r⁻¹ tan θ.

## 3.4 TOTAL DERIVATIVE

Total differential of a function f of three variables
x, y, z is denoted by df and is defined as

df = (∂f/∂x)dx + (∂f/∂y)dy + (∂f/∂z)dz         (1)

whether or not x , y and z are independent of each other. Several types of dependence among x , y and z are considered now.

### Chain Rules for Partial Differentiation

**Total derivative** Let u = f(x,y) and x and y are themselves functions of a single independent variable *t*. Then the dependent variable *f* may be considered as truly a function of the one independent variables x,y. Now the derivative of *f* w.r.t.  '*t*' is known as the total derivative of *f* and is given by

$\frac{df}{dt}$ = $\frac{\partial f}{\partial x} \frac{dx}{dt}$ + $\frac{\partial f}{\partial y} \frac{dy}{dt} \qquad$ (2)

Generalizing this, if u = f(x, y, z) and
x = x(t), y = y(t), z = z(t) then the total derivative
of f is

$\frac{df}{dt}$ = $\frac{\partial f}{\partial x} \frac{dx}{dt}$ + $\frac{\partial f}{\partial y} \frac{dy}{dt}$ + $\frac{\partial f}{\partial z} \frac{dz}{dt} \qquad$ (3)

This can easily be extended to function of several
variables.
If u = f(x, y, z) and suppose y and z are function
of x, then f is a function of the one independent
variable x. Here y and z are intermediate variables.
Identifying t with x in (3), we obtain

$\frac{df}{dx}$ = $\frac{\partial f}{\partial x} \frac{dx}{dx}$ + $\frac{\partial f}{\partial y} \frac{dy}{dx}$ + $\frac{\partial f}{\partial z} \frac{dz}{dx}$

$\frac{df}{dx}$ = $\frac{\partial f}{\partial x}$ + $\frac{\partial f}{\partial y} \frac{dy}{dx}$ + $\frac{\partial f}{\partial z} \frac{dz}{dx} \qquad$ (4)

### WORKED OUT EXAMPLES

**Example 1:** Find $\frac{du}{dt}$ as a total derivative and verify
the result by direct substitution if u = $x^2 + y^2 + z^2$
and x = $e^{2t}$, y = $e^{2t}$ cos 3t, z = $e^{2t}$ sin 3t.

**Solution:** Here u is a function of x, y, z and x, y, z
are in turn functions of t. Thus u is a function 't' via
the intermediate variables x, y, z. Then

$\frac{du}{dt}$ = $\frac{\partial u}{\partial x} \frac{dx}{dt}$ + $\frac{\partial u}{\partial y} \frac{dy}{dt}$ + $\frac{\partial u}{\partial z} \frac{dz}{dt}$

= 2x $\cdot 2e^{2t}$ + 2y $\cdot (2e^{2t} \cos 3t$ - $3e^{2t} \sin 3t)$ +

 2z $\cdot (2e^{2t} \sin 3t$ - $3e^{2t} \cos 3t)$

 Rewriting in terms of x, y, z
 
= 2x · 2 · x + 2 · y(2y - 3 · z) + 2z(2z + 3y)
= 4(x² + y² + z²)
or in terms of t

$\frac{du}{dt}$ = $4(e^{4t} + e^{4t}(\cos² 3t + \sin² 3t))$ = 8 $e^{4t}$

verification by direct substitution:

u = x² + y² + z² = $e^{4t}$ + $e^{4t} \cos² 3t$ + $e^{4t} \sin² 3t$ = 2 $e^{4t}$

$\frac{du}{dt}$ = 8 $e^{4t}$.

**Example 2:** Find the total differential coefficient
of x²y w.r.t. x when x, y are connected by
x² + xy + y² = 1.

**Solution:** Let u = x²y, then the total differential is

du = $\frac{\partial u}{\partial x}dx$ + $\frac{\partial u}{\partial y}dy$

Thus the total differential coefficient of u w.r.t. x is

$\frac{du}{dx}$ = $\frac{\partial u}{\partial x}$ + $\frac{\partial u}{\partial y}\frac{dy}{dx}$

$\frac{du}{dx}$ = 2xy + x² $\frac{dy}{dx}$

From the implicit relation f = x² + xy + y = 1, we
calculate

$\frac{dy}{dx}$ = - $\frac{f_x}{f_y}$ = - $\frac{2x + y}{x + 2y}$

so

$\frac{du}{dx}$ = 2xy + x² · $\frac{dy}{dx}$ = 2xy + x² · $\left(-\frac{(2x + y)}{(x + 2y)}\right)$

$\frac{du}{dx}$ = 2xy - $\frac{x²(2x + y)}{(x + 2y)}$

**Example 3:** The altitude of a right circular cone
is 15 cm and is increasing at 0.2 cm/sec. The radius
of the base is 10 cm and is decreasing at 0.3 cm/sec.
How fast is the volume changing?

**Solution:** Let x be the radius and y be the altitude
of the cone. So volume V of the right circular cone is

V = $\frac{1}{3}\pi x²y$.

Since x and y are changing w.r.t. time t, differentiate
V w.r.t. t.

$\frac{dV}{dt}$ = $\frac{\partial V}{\partial x}\frac{dx}{dt}$ + $\frac{\partial V}{\partial y}\frac{dy}{dt}$



















