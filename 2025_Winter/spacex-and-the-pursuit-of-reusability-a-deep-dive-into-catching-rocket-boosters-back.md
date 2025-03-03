---
title: "SpaceX and the pursuit of reusability: A deep dive into catching rocket
  boosters back"
category: Op-Ed
date: 2025-03-03T10:47:15.902Z
desc: "A deep dive into SpaceX’s booster recovery systems - chockful of
  equations, theories, and excitement! "
thumbnail: images/spacex_thumbnail.png
authors: Ritvik Ravi
starred: false
abio: ""
---
<h1>Introduction</h1>

<p>The increasing demand for improved space technology and advancements in space tourism and travel have necessitated developments in launch vehicle technology. Traditional one-time-use boosters and rockets are inefficient and both financially and environmentally costly, leading to the pursuit of reusable alternatives. SpaceX’s extensive work developing their flagship rockets, such as the Falcon 9 and, more recently, the Starship and its super heavy systems have redefined booster recovery through propulsive landing and mid-air catching techniques. 
This article focuses on the mechanics, challenges, and advancements in SpaceX’s booster recovery systems, which led to the historic Starship booster catch on Oct 13, 2024.</p>

<br>

<h1>Engineering Principles of booster recovery</h1>

<h2>Controlled descent and aerodynamics</h2>

<p>The descent of a body (in our case, a booster) to Earth is governed by the combination of a few forces - gravity, drag, and thrust. During re-entry, the booster undergoes rapid changes in temperature and velocity, reaching temperatures close to half the temperatures of the sun ( >5000 degrees F) and supersonic to subsonic transition phases, posing unique aerodynamic challenges:</p>

<ul type="none">

<li>a) <i>Reynolds and Mach number variations</i>:   The booster transitions through a high Reynolds number regime due to increased density and particle (the booster) velocity, and a compressible flow regime with Mach numbers exceeding 5. SpaceX uses grid fins made of titanium to address aerodynamic instability. They are designed for precision and have a withstanding nature in hypersonic and subsonic flow control.</li>
<br>

<li>b) <i>Re-entry plasma sheath formation</i>: While the booster re-enters the atmosphere, friction generates a plasma sheath, which can disrupt communications. SpaceX addresses this using fault-tolerant Inertial Guidance Systems (INS), which reduces dependency on GPS in critical stages. How INS works is similar to the motion tracking in a Wii remote- with the help of accurate accelerometers and gyroscopes that transmit and receive constant feedback from a computer processing the input data, the orientation, acceleration, position, and velocity of the body with respect to its initial position is realized.</li>
</ul>

<h2>Propulsive deceleration</h2>

<p>The Falcon 9 employs Merlin engines to decelerate from free fall into a controlled descent. The Thrust-to-Weight Ratio (TWR) is dynamically adjusted and precisely calculated in real-time to ensure a soft landing without structural overload. 
A basic equation pertaining to deceleration in this context is:</p>

<math display="block">
<msub><mi>F</mi><mi>t</mi></msub><mo>=</mo><mi>m</mi><mi>g</mi><mo>+</mo><mfrac><mn>1</mn><mn>2</mn></mfrac><mi>&rho;</mi><msup><mi>v</mi><mn>2</mn></msup><msub><mi>C</mi><mi>d</mi></msub><mi>A</mi>
</math>

<p>Where:</p>
<ul type="none">
<li><math><msub><mi>F</mi><mi>t</mi></msub></math>: Thrust required for deceleration (approximately equal to the weight of the rocket at the time of the docking, as acceleration will be negligible in the former).</li><br>

<li><math><mi>m</mi></math>: Mass of the booster</li><br>

<li><math><mi>g</mi></math>: Gravitational acceleration</li><br>

<li><math><mi>&rho;</mi></math>: Air density</li><br>

<li><math><mi>v</mi></math>: Velocity during descent</li><br>

<li><math><msub><mi>C</mi><mi>d</mi></msub></math>: Drag coefficient</li><br>

<li><math><mi>A</mi></math>: Area of the cross-section</li>