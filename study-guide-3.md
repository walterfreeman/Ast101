---
layout: page
title: Study Guide 3
permalink: exam3study.html 
use_math: true
---

# Study guide for Exam 3

In this unit, we studied:

* the nature of light   
* how light interacts with matter
* how the spectra we observe can tell us about things in the sky 
* how telescopes work and why the James Webb Space Telescope is uniquely capable 

I'll talk about each in turn.

## The nature of light: wave properties

Light is an electromagnetic wave. Like any other sort of wave, light has the following properties:

* a wavelength 
* a frequency ("number of waves per second")
* a speed (always the speed of light, in empty space)

These things are related by the formula (wavelength) $\times$ (frequency) = (speed). So, **light with a higher frequency will have a shorter wavelength**.

Electromagnetic waves can have any wavelength they like. The human eye can only see a narrow range of wavelengths, from about 380 nanometers to 750 nanometers. The only difference
between visible light in this range and other electromagnetic waves is the wavelength; radio waves, infrared, ultraviolet, and so forth obey the same physics as visible light.

Within the visible band, different wavelengths correspond to different colors. From shortest to longest wavelength, the colors are violet, blue, green, yellow, orange, and red. 

On terminology: "light" means *any electromagnetic wave*; "visible light" means only the wavelength range we can see.

## The nature of light: quantum properties

Quantum mechanics says that light also acts as a particle. These particles are called **photons** -- little chunks of light. According to the laws of physics, light with a 
higher frequency has more energy per photon. Thus, gamma rays (the shortest-wavelength electromagnetic waves) have far more energy per photon than visible light, which in turn
has far more energy per photon than radio waves.

An excellent quick-reference chart is published by Lawrence Berkeley National Lab:

<img src="http://www2.lbl.gov/images/MicroWorlds/EMSpec.gif">

## Thermal radiation/blackbody radiation

Objects with a temperature emit light of a wide range of wavelengths. This is called **blackbody radiation**, since even a "black" object (with no special emission properties related to atomic
transitions) will emit light if it is warm. It is also called **thermal radiation**, since it is associated with an object's temperature.

The properties of this light depend on its temperature. Specifically:

* the total amount of light increases *rapidly* as the object warms up (doubling the temperature increases the amount of light by a factor of 16)
* the frequency containing the most light increases proportionate to the temperature (doubling the temperature doubles the peak frequency)

Here we measure temperature in "Kelvins", which are the same as the Celsius scale except absolute zero is at 0K; this puts room temperature at about 300K and the boiling point of water at
373K. 

Note that a temperature of 5000K corresponds to a blackbody spectrum that has its peak in the middle of the human visible range. This is about the temperature of the Sun, so it should
come as no surprise that our eyes have evolved to see the kind of light that the Sun gives off.

This explains the change in color as a glowing object heats up (and why hot objects glow): objects first glow a dull red (emitting most of their light in the infrared), then begin
to glow orange and then white. Objects hotter than those encountered on Earth (such as very hot stars) will shift so that they glow mostly in the blue or even UV.


## Light interacting with matter: quantum transitions

Quantum mechanics tells us that physical systems can have only **discrete energy levels**, corresponding to particular ways that they can vibrate. For atoms, these correspond to the
electron orbitals discussed in chemistry. These have the following properties:

* The pattern of energy levels is unique to each chemical element
* These levels are numbered starting at $n=1$ (the lowest energy), with larger values of $n$ corresponding to higher energies
* These levels become increasingly close-packed as $n$ increases. See the diagram for hydrogen <a href="http://astro.unl.edu/naap/hydrogen/graphics/bohr_transitions.png">here</a>. 
(The "Lyman series" is the group of UV transitions down to $n=1$; the "Ballmer series" is the group of red transitions down to $n=2$. But you don't need to know those names.)
* $n=1$ is called the "ground state" and higher values of $n$ are called "excited states"
* Atoms are almost always found in their ground state unless something is done to excite them

Since energy is conserved, an atom (or other state) must absorb energy to get to a higher energy level, and must give up energy to fall back to a lower energy level. This is most often
done by **emitting and absorbing light**. So:

* an atom can jump to a higher energy level by absorbing light
* an atom can fall to a lower energy level by emitting light
* in both cases, the energy of the photon is equal to the **difference** in energy between the two atomic energy levels

Matter, especially solids, will absorb light of other wavelengths as well, but much less strongly.

## Discrete spectra

### Emission spectra

If a chemical element is heated or excited by electricity, then its electrons will be kicked up to higher energy levels, or ripped completely free of their atoms. As they fall back down
(being recaptured by their atoms if necessary), they will emit photons of specific energies corresponding to the differences between their energy levels. This spectrum is a unique 
fingerprint of that element; by examining the spectra of objects, we can determine what elements they are made of. (These spectra show up as bright lines, since only photons of a few
energies are present; because of their origins, these are called **emission spectra**.)

There are also emission spectra associated with things other than atoms. Quantum transitions in the vibrations and rotations of molecules are much lower energy; these lie in the infrared
and microwave bands, respectively. Thus, observations in the IR and the microwave can tell us a great deal about what kinds of molecules are in space, just like observations in the 
visible band can tell us about what kinds of atoms are in space.

Finally, the lowest-energy transitions of all involve magnetic interations between an electron and an atom's nucleus. The most notable of this is the 21 cm waves produced by these
transitions in hydrogen, which are a universal calling card: "hydrogen is here".

### Absorption spectra

This process works in reverse. If light of many different wavelengths passes through a cloud of cool gas, the cool gas will absorb light corresponding to the transitions from its
ground state to its excited states. When it passes through the other side, that light contains all colors *except* the ones absorbed by the intervening gas, allowing us once again
to take its "fingerprint". This is the sort of spectrum we see from the Sun: an otherwise bright swath of color, with dark lines corresponding to those wavelengths absorbed by the
different elements in the Sun's atmosphere.

### Telescopes

The high points of the presentation on telescopes:

Making them larger:
* Telescopes gather light and focus it on an image sensor, just like our eyes or a camera
* Telescopes with a larger aperture ("bigger eyes") can both see fainter objects and see more detail
* Telescopes that use mirrors rather than lenses can be much smaller and cheaper for the same aperture size

Seeing many wavelengths:
* Telescopes can be combined with spectroscopes to see precise colors (like you did in lab)
* Image sensors can be made that are sensitive to ultraviolet and IR in addition to visible
* Ultraviolet and infrared do not pass through the atmosphere readily
* We can put telescopes in space (like Hubble and JWST) to avoid this

The cosmological redshift:
* Objects moving away from us have their spectra shifted to longer wavelengths; this is called the "redshift"
* The oldest and most distant things in the universe are moving away from us very quickly; their redshift may be 20x or more
* This means that light from the oldest stars is shifted to around 10,000 nm -- the wavelengths of thermal radiation from room temperature things
* A telescope that can see these wavelengths clearly has to be cooled down far below room temperature, so it is not blinded by its own light

Design of JWST:
* It achieves a large aperture size by using hexagonal mirrors that could be unfolded once in space
* It is mostly an infrared telescope
* It is located in a special orbit so that the Sun, Moon, and Earth are all on the same side, and uses a special sun-shade to block the light from them from warming it up
* It is able to clearly see the infrared light from very old galaxies since it is so cold
* It has also been able to see water in the absorption spectra of a planet orbiting another star
 
