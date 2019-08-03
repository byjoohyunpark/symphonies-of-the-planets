### Symphonies of the Planets

This project aims to generate "some" music based on the data we have about exoplanets. All the sounds here are distinctively mapped with dataset collected from [NASA Exoplanet Archive](https://exoplanetarchive.ipac.caltech.edu/index.html). You can check result [here](https://byjoohyunpark.github.io/symphonies-of-the-planets/).

The original dataset includes total of 3791 confirmed planets as of Sep. 27. For suitable synthesization, 10 parameters are selected and mapped to musical features starting 67. Based on a seven-note scale in B major, pitch for each note is mapped from the remainder of parameter value divided by 7. A duration is mapped from the scale of parameter value compared to the total.


```
[mapping detail]

Planet Name – just as reference
Distance [pc] – note order
Effective Temperature [K] – main note pitch
Planet Mass or M*sin(i) [Jupiter mass] – sub note pitch
Number of Planets in System – base note pitch
Orbit Semi-Major Axis [AU] – sub base note pitch
Stellar Radius [Solar radii] – main note duration
Orbital Period [days] – sub note duration
Stellar Mass [Solar mass] – base note duration
Planet Radius [Jupiter radii] – sub base note duration
```
