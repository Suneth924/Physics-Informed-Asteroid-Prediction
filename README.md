# Physics-Informed-Asteroid-Prediction
This repository presents a cost-effective approach to predicting asteroid risk using Physics-informed Machine Learning.
Physics-Informed MOID + Machine Learning for Asteroid Hazard Prediction

This repository demonstrates a cost-efficient, physics-informed machine learning framework for predicting potentially hazardous asteroids.

We approximate the Minimum Orbit Intersection Distance (MOID) using a lightweight physics approach:

Convert asteroid orbital elements (a, e, i, Ω, ω, ν) into Cartesian coordinates.

Rotate from the perifocal frame to the heliocentric ecliptic frame.

Sample true anomaly across the full orbit.

Compute the minimum separation between the asteroid’s orbit and Earth’s orbital radius.

This produces a fast physics-based MOID estimate which is then combined with traditional ML features.
The final hybrid approach achieves strong predictive performance while keeping computational requirements low.
