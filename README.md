🛰️ Satellite-SMC: Robust Attitude Control
A high-performance Sliding Mode Controller for satellites facing unpredictable atmospheric drag during de-orbiting.
🌟 Project Highlight:-This isn't just a simple tracker. This repository implements a Chattering-Free SMC that handles massive model uncertainty. We deliberately feed the controller "wrong" physics data to prove it can still land the satellite on its target orientation perfectly.
🛠️ Key Technical SpecsControl Law: u = u_{eq} + u_{robust}

🧠Surface Logic: First-order sliding manifold with λ convergence.
📉Actuator Safety: Integrated Boundary Layer (Saturation) logic to prevent reaction wheel burn-out. ⚙️Environment: Dynamic atmospheric "Chirp" torque simulation. 🌪️
