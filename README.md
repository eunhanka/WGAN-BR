# PhantomFlow – WGAN-BR for Route-Guidance Attacks
*A reproducible research codebase accompanying our NDSS 2026 paper,  
“**Fake Rush Hour: Exploring Bounded-Rational Route Guidance Attacks on Urban Navigation Systems**.”*

---

PhantomFlow implements a **Wasserstein-GAN with a Bounded-Rationality critic (WGAN-BR)** that learns to inject *stealthy* traffic-time perturbations into real-time navigation services.  
The attack respects drivers’ bounded-rational tolerance (γ ≈ 0.2) while maximising city-wide congestion on four benchmark networks: **Sioux Falls, Anaheim, Barcelona, Chicago** :contentReference[oaicite:0]{index=0}&#8203;:contentReference[oaicite:1]{index=1}.
