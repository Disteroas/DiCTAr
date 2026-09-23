# Examples and Labs

This folder collects the code I wrote while following the course: lecture examples and laboratories, as MATLAB scripts, live scripts and Simulink models.

## What's inside

- **`LECTURE_EXAMPLES/`** — worked examples, grouped by lecture:
  - `L01-02-03/` — discrete-time systems, Z-transform, responses and stability
  - `L04-05-06/` — 1-DoF digital controller design (pole placement, Diophantine equation, requirements analysis)
  - `L07/` — LQR: static state feedback, weights tuning, tracking with integral action
  - `L08/` — finite-horizon constrained control and receding horizon
  - `L09-10_MPC/` — MPC design and simulation
  - `SimulinkSimulations/` — basic Simulink models (unit step, disturbances) used across the examples
- **`LAB/`** — my solutions to the labs, one folder per lab (`LAB1` … `LAB7`; `LAB5.mlx` sits directly in `LAB/`), each with its live script and the Simulink models it uses. `SimulinkSimulations/` holds the same basic models as above.
- **`HomemadeFunctions/`** — small helper functions I wrote and reuse everywhere:
  - `diop_solver.m` — solves the Diophantine equation for 1-DoF design
  - `cal_m_builder.m` — builds the stacked prediction matrices for finite-horizon LQ / MPC as a function of $H_p$

The MPC scripts need **MPCtools**, which is not in this repo (see the main README).

## How to navigate these folders

The folders structure is set up for my personal convenience ;)

If you try to run the code, it might not find everything
immediately because some files are likely in different
locations. I won't update the paths until I re-run
the code (prob never), so you might need to
tweak things manually. It's not a maze though, I'm sure you
guys can figure it out.

Moreover, you'll maybe find errors / different data / results. Just don't try to fix your codes in function of mine; mistakes can occur
or simply I could edit just for the meme some ex.

Hope you'd read it before starting navigate and running scripts.

Bisous
