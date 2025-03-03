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
<li><math><msub><mi>F</mi><mi>t</mi></msub></math>: Thrust required for deceleration (approximately equal to the weight of the rocket at the time of the docking, as acceleration will be negligible in the former)</li><br>

<li><math><mi>m</mi></math>: Mass of the booster</li><br>

<li><math><mi>g</mi></math>: Gravitational acceleration</li><br>

<li><math><mi>&rho;</mi></math>: Air density</li><br>

<li><math><mi>v</mi></math>: Velocity during descent</li><br>

<li><math><msub><mi>C</mi><mi>d</mi></msub></math>: Drag coefficient</li><br>

<li><math><mi>A</mi></math>: Area of the cross-section</li>

</ul>
<br>

<h1>The <i>Mechazilla</i> catch system</h1>

<h2>System Overview</h2>
<p>The Mechazilla system uses massive robotic ‘arms’ attached to the launch tower to catch the descending Super Heavy booster in mid-air. This eliminates the requirement of landing legs on the booster, reducing weight and improving payload performance.</p>

<h2>Kinematic and dynamic modelling</h2>
<p>Catching a booster mid-air requires precise control of the robotic arms’ velocity and position. An example of a kinematic equation with vector algebra governing this synchronization is as follows:</p>

<math display="block">
<msub><mover><mi>r</mi><mo>&rarr;</mo></mover><mi>catch</mi></msub><mo>=</mo><msub><mover><mi>r</mi><mo>&rarr;</mo></mover><mi>booster</mi></msub><mo>+</mo><mi>&Delta;</mi><mover><mi>r</mi><mo>&rarr;</mo></mover><mo>(</mo><mi>t</mi><mo>)</mo>
</math>

<p>Where:</p>
<ul type="none">
<li><math><msub><mover><mi>r</mi><mo>&rarr;</mo></mover><mi>catch</mi></msub></math>: Position vector of the robotic arm</li><br>

<li><math><msub><mover><mi>r</mi><mo>&rarr;</mo></mover><mi>booster</mi></msub></math>: Predicted trajectory of the booster</li><br>

<li><math><mi>&Delta;</mi><mover><mi>r</mi><mo>&rarr;</mo></mover><mo>(</mo><mi>t</mi><mo>)</mo></math>: Real-time adjustments based on atmospheric perturbations</li><br>

</ul>

<p>The dynamic stress analysis of the arms and attachment points considers load distribution during the catch can be modelled by:</p>

<math display="block">
<msub><mi>&sigma;</mi><mi>max</mi></msub><mo>=</mo><mfrac><mi>F</mi><mi>A</mi></mfrac><mo>+</mo><mfrac><mrow><mi>M</mi><mi>d</mi></mrow><mi>I</mi>
</math>

<p>Where:</p>
<ul type="none">
<li><math><msub><mi>&sigma;</mi><mi>max</mi></msub></math>: Maximum stress on the arms</li><br>

<li><math><mi>F</mi></math>: Contact force applied during the catch</li><br>

<li><math><mi>A</mi></math>: Cross-sectional area of the arms</li><br>

<li><math><mi>M</mi></math>: Moment due to angular acceleration</li><br>

<li><math><mi>d</mi></math>: Distance from the pivot</li><br>

<li><math><mi>I</mi></math>: Moment of Inertia</li><br>

</ul>
<br>

<h1>Materials and Structural Integrity</h1>

<h2>Thermal Protection Systems (TPS)</h2>
<p>The extremely high temperatures the boosters encounter ranges from 1,500K to 5,000K during re-entry. SpaceX uses ablative TPS (This type of TPS sacrifices itself, eroding away while absorbing and dissipating the heat, and is generally made of materials like PICA or C-Ph) and reinforced Carbon-Carbon composites in critical areas for structural integrity and to dissipate heat. These materials undergo extensive testing to withstand thermal cycling without extensive degradation.</p>

<h2>Fatigue and Longevity</h2>
<p>Reusable systems require materials that can endure multiple launch and recovery cycles without failure. Finite element analysis (FEA) predicts fatigue life, focusing on high-stress regions such as engine mounts and structural joints.</p>

<br>

<h1>Guidance and Navigation Systems</h1>
<p>SpaceX’s success in booster recovery hinges on accurate real-time positioning, for which GNS plays a major part, ensuring precise manoeuvring during descent and landing. GNS consists of real-time data processing, advanced algorithms, and robust data networks, with Deep Learning being looked into for inclusion in existing systems.</p>

<h2>Inertial Navigation Systems (INS)</h2>
<p>Without external references, INS relies on gyroscopes and accelerometers to determine position, velocity, and orientation. Some equations of motion governing the INS include:
</p>

<math display="block">
<mover><mover><mi>r</mi><mo>&rarr;</mo></mover><mo>.</mo></mover><mo>=</mo><mover><mi>v</mi><mo>&rarr;</mo></mover>
</math>
<br>

<math display="block">
<mover><mover><mi>v</mi><mo>&rarr;</mo></mover><mo>.</mo></mover><mo>=</mo><msub><mover><mi>a</mi><mo>&rarr;</mo></mover><mi>sensor</mi></msub><mo>-</mo><mn>2</mn><msub><mover><mi>&omega;</mi><mo>&rarr;</mo></mover><mi>E</mi></msub><mo>&times;</mo><mover><mi>v</mi><mo>&rarr;</mo></mover><mo>-</mo><msub><mover><mi>&omega;</mi><mo>&rarr;</mo></mover><mi>E</mi></msub><mo>&times;</mo><mo>(</mo><msub><mover><mi>&omega;</mi><mo>&rarr;</mo></mover><mi>E</mi></msub><mo>&times;</mo><mover><mi>r</mi><mo>&rarr;</mo></mover><mo>)</mo><mo>+</mo><mover><mi>g</mi><mo>&rarr;</mo></mover>
</math>

<p>Where:</p>
<ul type="none">
<li><math><mover><mi>r</mi><mo>&rarr;</mo></mover></math>: Position vector relative to the Earth</li><br>

<li><math><mover><mi>v</mi><mo>&rarr;</mo></mover></math>: Velocity vector</li><br>

<li><math><mover><mi>a</mi><mo>&rarr;</mo></mover></math>: Specific acceleration measured by the accelerometers</li><br>

<li><math><msub><mover><mi>&omega;</mi><mo>&rarr;</mo></mover><mi>E</mi></msub></math>: Earth's angular velocity vector</li><br>

<li><math><mover><mi>g</mi><mo>&rarr;</mo></mover></math>: Gravity vector</li><br>

</ul>

<h2>Kalman Filtering</h2>
<p>SpaceX employs Kalman filtering for sensor fusion to mitigate sensor noise and errors. The Kalman filter prediction and update equations are:</p>

<math display="block">
<msub><mover><mi>x</mi><mo>^</mo></mover><mrow><mi>k</mi><mo>&verbar;</mo><mi>k</mi><mo>-</mo><mn>1</mn></mrow></msub><mo>=</mo><msub><mi>F</mi><mi>k</mi></msub><msub><mover><mi>x</mi><mo>^</mo></mover><mrow><mi>k</mi><mo>-</mo><mn>1</mn><mo>&verbar;</mo><mi>k</mi><mo>-</mo><mn>1</mn></mrow></msub><mo>+</mo><msub><mi>B</mi><mi>k</mi></msub><msub><mi>u</mi><mi>k</mi></msub>
</math>
<br>

<math display="block">
<msub><mi>P</mi><mrow><mi>k</mi><mo>&verbar;</mo><mi>k</mi><mo>-</mo><mn>1</mn></mrow></msub><mo>=</mo><msub><mi>F</mi><mi>k</mi></msub><msub><mi>P</mi><mrow><mi>k</mi><mo>-</mo><mn>1</mn><mo>&verbar;</mo><mi>k</mi><mo>-</mo><mn>1</mn></mrow></msub><msubsup><mi>F</mi><mi>k</mi><mi>T</mi></msubsup><mo>+</mo><msub><mi>Q</mi><mi>k</mi>
</math>
<br>

<math display="block">
<msub><mi>K</mi><mi>k</mi></msub><mo>=</mo><msub><mi>P</mi><mrow><mi>k</mi><mo>&verbar;</mo><mi>k</mi><mo>-</mo><mn>1</mn></mrow></msub><msubsup><mi>H</mi><mi>k</mi><mi>T</mi></msubsup><msup><mrow><mo>(</mo><msub><mi>H</mi><mi>k</mi></msub><msub><mi>P</mi><mrow><mi>k</mi><mo>&verbar;</mo><mi>k</mi><mo>-</mo><mn>1</mn></mrow></msub><msubsup><mi>H</mi><mi>k</mi><mi>T</mi></msubsup><mo>+</mo><msub><mi>R</mi><mi>k</mi></msub><mo>)</mo></mrow><mn>-1</mn></msup>
</math>
<br>

<math display="block">
<msub><mover><mi>x</mi><mo>^</mo></mover><mrow><mi>k</mi><mo>&verbar;</mo><mi>k</mi></mrow></msub><mo>=</mo><msub><mover><mi>x</mi><mo>^</mo></mover><mrow><mi>k</mi><mo>&verbar;</mo><mi>k</mi><mo>-</mo><mn>1</mn></mrow></msub><mo>+</mo><msub><mi>K</mi><mi>k</mi></msub><mo>(</mo><msub><mi>z</mi><mi>k</mi></msub><mo>-</mo><msub><mi>H</mi><mi>k</mi></msub><msub><mover><mi>x</mi><mo>^</mo></mover><mrow><mi>k</mi><mo>&verbar;</mo><mi>k</mi><mo>-</mo><mn>1</mn></mrow></msub><mo>)</mo>
</math>

<p>Where:</p>
<ul type="none">
<li><math><msub><mover><mi>x</mi><mo>^</mo></mover><mrow><mi>k</mi><mo>&verbar;</mo><mi>k</mi></mrow></msub></math>: State estimate at step <i>k</i></li><br>

<li><math><msub><mi>P</mi><mrow><mi>k</mi><mo>&verbar;</mo><mi>k</mi></mrow></msub></math>: Covariance</li><br>

<li><math><msub><mi>F</mi><mi>k</mi></msub></math>: State transition</li><br>

<li><math><msub><mi>B</mi><mi>k</mi></msub></math>: Control input model</li><br>

<li><math><msub><mi>H</mi><mi>k</mi></msub></math>: Observation model</li><br>

<li><math><msub><mi>Q</mi><mi>k</mi></msub></math>: Process covariance matrix</li><br>

<li><math><msub><mi>R</mi><mi>k</mi></msub></math>: Noise covariance matrix</li><br>

<li><math><msub><mi>K</mi><mi>k</mi></msub></math>: Kalman gain</li><br>

</ul>

<p>The Kalman Filter equations are extensively used in control systems engineering and are a powerful algorithm to estimate the state of a dynamic system from noisy measurements. It recursively updates a predicted state and its associated uncertainty based on new measurements. To explain the above equations in brief:</p>

<ol>
<li>The first equation predicts the system’s state during step <i>k</i> given the previous state estimate <i>k-1</i> and the control input <math><msub><mi>u</mi><mi>k</mi></msub></math>. The control input is like an external input that drives and influences the system’s state. For example, <math><msub><mi>u</mi><mi>k</mi></msub></math> can represent a moving object's applied force/acceleration.</li><br>

<li>The second equation predicts the uncertainty in the state estimate, with <math><msub><mi>P</mi><mrow><mi>k</mi><mo>&verbar;</mo><mi>k</mi><mo>-</mo><mn>1</mn></mrow></msub></math> being the predicted covariance matrix at a time of event <i>k</i> with information up to event <i>k-1</i> and <math><msub><mi>Q</mi><mi>k</mi></msub></math> being the noise covariance matrix, which models the uncertainty in the system dynamics. Covariant matrices help quantify the uncertainty or variability in a set of random variables and are essential to understanding the degree of uncertainty of our system. They also help adjust the uncertainty according to the constantly changing system state as per the output of the filter.</li><br>

<li>The third equation calculates the Kalman gain <math><msub><mi>K</mi><mi>k</mi></msub></math> which determines how much weight should be added to the measurement update. <math><msub><mi>H</mi><mi>k</mi></msub></math> is the observation model that relates the system state to the measurement, and <math><msub><mi>R</mi><mi>k</mi></msub></math> is the noise covariance matrix.</li>
</ol>

<h2>Closed Loop Control</h2>