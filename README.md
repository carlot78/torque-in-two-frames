# Torque in Two Frames

An interactive 3D page for studying rotations, skew-symmetric matrices, torque and wrenches in the space frame {s} and the body frame {b}. Notation follows *Modern Robotics* (Lynch & Park).

**Live page:** https://carlot78.github.io/torque-in-two-frames/

- Two synchronized views: one with the camera fixed in {s}, one with the camera moving with {b}.
- Move the body (p), rotate it (axis ω̂, angle θ, angular speed θ̇), and set the push point r_b and the force f, which can be fixed in {s} or in {b}.
- Live math: Rodrigues' formula, [r]f torques in both frames, angular velocity, and the wrench change of frame F_b = [Ad_Tsb]ᵀ F_s.

The whole app is the single file `index.html`. The only thing it downloads is three.js r128, from a CDN.
