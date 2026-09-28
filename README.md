# Torque in Two Frames

An interactive 3D page covering chapter 3 of *Modern Robotics* (Lynch & Park), Rigid-Body Motions: rotations, angular velocities, exponential coordinates, homogeneous transformations, twists, screw axes and wrenches, in the space frame {s} and the body frame {b}.

**Live page:** https://carlot78.github.io/torque-in-two-frames/

- Two synchronized views: one with the camera fixed in {s}, one with the camera moving with {b}.
- Pose tab: position p, orientation e^[ω̂]θ, and premultiply/postmultiply buttons (fixed-frame vs body-frame rotations and translations).
- Twist tab: a screw axis (direction ŝ, point q, pitch h) or a pure translation, with a speed. Move along it continuously or step by e^[S]Δθ.
- Force tab: push point r_b and force f, fixed in {s} or in {b}.
- Live math by section: 3.1 planar forms; 3.2 SO(3), angular velocity, Rodrigues and log R; 3.3 SE(3), T⁻¹, pre/postmultiplication, twists, adjoint, screw axes, e^[S]θ and log T; 3.4 moments, F_b = [Ad_Tsb]ᵀ F_s, and power 𝒱ᵀℱ.

The whole app is the single file `index.html`. The only thing it downloads is three.js r128, from a CDN.
