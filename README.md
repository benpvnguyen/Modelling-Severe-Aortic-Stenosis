# Modelling-Severe-Aortic-Stenosis

# Abstract

Aortic stenosis (AS) is a valvular disease that involves the narrowing of the aortic
valve, which increases the pressure of the left ventricle, reduces cardiac output, and
imposes significant strain on the heart. This study utilizes a lumped parameter (0D) model
of the cardiovascular system to examine the hemodynamic effects of severe AS using the
model as per Gerach et al. (2023). The model incorporates resistances, compliances,
inertances, a time-varying elastance representation of the left ventricle, and a pressure
dependent ordinary differential equation (ODE) that captures restricted leaflet motion
under AS. The resulting system of ODEs is solved using both Heun’s method and the
fourth-order Runge–Kutta method (RK4). Simulations reproduce key features of severe
AS, including elevated ventricular systolic pressures, reduced stroke volume, and increased
transvalvular pressure gradients. Pressure–volume loops exhibit a narrowed width and
significantly increased height, reflecting greater ventricular strain. Comparisons of
numerical methods show that RK4 provides smoother and more accurate waveforms than
Heun’s method for this nonlinear system. Overall, the model successfully isolates the
hemodynamic consequences of severe aortic stenosis and demonstrates the usefulness of
simplified computational frameworks for studying valvular disease.
