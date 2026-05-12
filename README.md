
# Numerical Methods for Physics and Astrophysics

Solutions to computational [exercises](https://home.icts.res.in/~ajith/Teaching_files/Lab.pdf) from the ICTS *Numerical Methods for Physics and Astrophysics* lab course by Prof. Ajith, completed by Kruthi during Summer 2020.

## Topics Covered

### Exercise 1A — Finite Differencing, Convergence, Error Estimates
- Forward, backward, and central finite differencing
- Convergence and truncation error analysis
- Numerical differentiation of functions
- Error scaling and round-off behavior

### Exercise 1B — Richardson Extrapolation
- Richardson extrapolation methods
- Higher-order derivative approximations
- Numerical differentiation of gravitational-wave phase evolution
- Frequency and frequency-derivative estimation

### Exercise 2 — ODEs: Calculation of Gravitational Waves from Inspiralling Compact Binaries
- Inspiralling compact binary dynamics
- Gravitational-wave waveform generation
- Numerical integration using `odeint`
- Adaptive Runge–Kutta (`dopri5`) methods

### Exercise 3 — ODEs: Structure of a Relativistic, Spherically Symmetric Star
- Solving the Tolman–Oppenheimer–Volkoff (TOV) equations
- Neutron star mass-radius relations
- Interior and exterior lapse functions
- Polytropic equations of state

### Exercise 4A — Non-linear ODE with Chaotic Behavior: Lorenz Equations
- Lorenz chaotic system
- Sensitivity to initial conditions
- 3D Lorenz attractor visualization
- Lorenz attractor animation

### Exercise 4B — Stochastic ODE: Langevin Equation
- Brownian motion simulations
- Euler–Maruyama method
- Stochastic trajectories
- Probability distributions and diffusion behavior

### Exercise 5 — Two-point Boundary Value Problems: The Shooting Method
- Shooting method implementation
- Newton–Raphson root finding
- Boundary value solutions of TOV equations

### Exercise 6 — Partial Differential Equations
- FTCS scheme for the advection equation
- Upwind differencing methods
- Stability analysis
- Convergence analysis

### Exercise 7A — Fast Fourier Transform (FFT)
- FFT analysis of pulsar light curves
- Frequency-domain signal analysis
- Pulsar spin-period estimation
- Harmonic identification

### Exercise 7B — Power Spectrum Estimation Using FFT
- Power spectral density estimation
- Welch periodogram method
- LIGO strain data analysis

### Exercise 7C — Time-frequency Signal Detection Methods
- Spectrogram generation
- Time-frequency analysis
- Quasi-periodic oscillation (QPO) detection
- RXTE X-ray timing data analysis

### Exercise 7D — Computing Correlations Using FFT: Matched Filtering
- Matched filtering techniques
- Correlation-based signal detection
- Gravitational-wave template matching
- Parameter estimation from noisy detector data

## Files

### `nm_gwastro.ipynb`
Main notebook containing implementations, plots, simulations, and analyses for all exercises.

### `full problem set.pdf`
Original lab problem sheet describing all exercises and datasets.

### `data/`
Contains datasets used throughout the exercises:
- Numerical relativity waveform data
- RXTE X-ray pulsar light curves
- LIGO strain data
- Simulated gravitational-wave detector output

## Requirements

Recommended Python packages:

```bash
numpy
scipy
matplotlib
pandas
jupyter
```

Optional:

```bash
ffmpeg
```

for saving animations.
