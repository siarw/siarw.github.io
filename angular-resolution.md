---
Title: Angular Resolution
Date: 2021-05-15 13:12
Author: Pedro Lacerda
Slug: angular-resolution
Status: published
---

# Angular Resolution

There is a **limit to our ability to see two separate sources** of light in the night sky. These could be two stars, or two Kuiper Belt objects orbiting each other in a [binary](binaries). The same limitation also prevents us from perceiving the shape of an object. If we cannot see separately the two tips of an egg-shaped asteroid, then it will appear to us as a round dot.





This limit is called **angular resolution**. Light arriving from two slightly different directions in the sky forms an narrow angle as it converges at our eyes or telescope. The smallest angle that we can still identify as two separate direction is the angular resolution.





You can imagine this if you think of the headlights of a car in the distance at nighttime. If the car is sufficiently far away you will see the two headlights as a single source of light. The two are **unresolved**. As you and the car approach each other, there is a point at which you begin to see the two headlights separately. Now you can **resolve** them. The angle between the directions from your eyes to the two headlights is very small in the distance, but increases as the car approaches.





The angular resolution (`theta`, in [radians](https://en.wikipedia.org/wiki/Radian)), which depends on the **wavelength of light** (`lambda`; for visible light, about 5000 Å or 5e-7 m) and the **aperture** (diameter, `D`) of the detector, is given by the **[Rayleigh criterion](https://en.wikipedia.org/wiki/Angular_resolution#The_Rayleigh_criterion)**, which is

`theta = 1.22 lambda / D`

<!-- <img align="center" src="figs/2023/08/theta=1.22_,_fra.png" /> -->
<!-- \theta=1.22\,\frac{\lambda}{D} -->

This relation, valid for circular detectors, is also called the **diffraction limit**. Incoming lightwaves arriving at different points of the detector interfere with each other in a way that blurs detail on scales smaller than `theta`.

For example, the human eye has a circular aperture with diameter `D_eye ~ 0.5 cm` and can achieve an angular resolution

`theta = 1.22 (5e-7 / 0.5e-2) = 1.22e-4 radians ~ 25 arcsec`

<!-- <img align="center" src="figs/2023/08/theta=1.22_times.png" />, -->

<!-- \theta=1.22\times \frac{5\times 10^{-7}}{0.5\times 10^{-2}}=1.22\times 10^{-4}\,\text{radians}\approx 25'' -->

which corresponds to about `0.1 mm` at a distance of `1 meter`. Note that `1 deg = 3600 arcsec`.

For a powerful telescope, `D_telescope = 5 m` and

`theta = 1.22 (5e-7 / 5) = 1.22e-7 radians ~ 0.03 arcsec`

<!-- \$latex \\theta=1.22\\times \\frac{5\\times 10\^{-7}}{5}=1.22\\times 10\^{-7}\\,\\text{radians}\\approx 0.03''&s=2\$ -->


The excellent angular resolution achieved by a 5-meter telescope is further blurred by air motions in the earth’s atmosphere. Over the few minutes exposure time required to detect a Kuiper Belt object, the atmosphere degrades the image to an angular resolution of around `1 arcsec`. This is called the **seeing** in observational astronomy. At very good observing sites the seeing can be as low as a few times `0.1 arcsec`. Advanced techniques such as adaptive or active optics and lucky imaging can compensate for the atmosphere’s blurring and approach the image quality promised by the diffraction limit.


Pedro Lacerda, May 2021


