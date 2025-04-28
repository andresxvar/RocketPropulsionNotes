# Rocket Nozzle Thermochemistry

In the 40's-50's Engineers assumed that the composition of the exhaust gases were based on the condition at the combustion chamber. This is known as *frozen flow*, which assumes that chemical kinetics are infinitely slow. Calculations based on frozen flow would underpredict performance of the larger rockets. With the advent of computing in the 60s, engineers adapted an *equilibrium flow* model, with infinitely fast kinetics. In the equilibrium approach Isp would be generally overpredicted.

In reality, the specific impulse of the rocket is actually between these two limits:

Isp_frozen < Isp_actual < Isp_equilibrium

This is because in the nozzle there is recombination of species so it's neither frozen nor complete. Chemical kinetics in the nozzle occurs in microseconds, while the gas residence time is milliseconds.

## Why is Isp_frozen less than actual?

Recombination (bond forming) releases energy into surroundings.
h0 = h + v^2/2 = constant in the ideal nozzle, here v is velocity
 h = u + p*v, here v is specific volume, I will be addressing it as `pv` to avoid confusion

Expansion transfers energy from h to v
with recombination h can be higher because there is an injection to u, from forming bonds! 🚀
