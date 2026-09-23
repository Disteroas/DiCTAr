# Exam preparation

This folder collects what I used to get ready for the exam: quick theory reviews, practice exercises and fast re-runs of the labs.

## What's inside

- **`TheoryReview/`** — short live-script summaries of the main topics, each with a solved exercise: `1DoF/`, `LQR/`, `MPC/` and `Constraints&RH.mlx` (finite-horizon constrained control and receding horizon). See the `readme.md` inside for what it is and what it is not.
- **`exam_simulation/`** — my code for a full exam-style design problem: a 1-DoF digital controller (`exam_design.m`) and an MPC controller (`exam_mpc.m`), each with its Simulink model.
- **`quizEx.mlx`** — my solutions to exam-style quizzes (stability, 1-DoF, LQ, MPC).
- **`quiz_sim_again.m`** — the same kind of quizzes, redone as a plain script.
- **`exBalordi.mlx`** — a few odd exercises worth a second look (responses, stability, inverse Z-transform).
- **`oneDof/`** — extra 1-DoF design practice, scripts plus Simulink model.
- **`MPC_lectureEx/`** — MPC design and tuning practice.
- **`spreedrun/`** — "speedrun" of the labs: the key steps of each lab redone as fast as possible, to check I could do them under time pressure.

The MPC scripts need **MPCtools**, which is not in this repo (see the main README).

Same warning as for `ExamplesAndLabs`: paths and folder structure are set up for my convenience, so you may need to fix them before running anything.
