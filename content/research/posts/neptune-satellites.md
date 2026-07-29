---
title: "Neptune's Inner Moons and Rings Are Exposed Icy Body Interiors"
date: 2026-07-29
draft: false
image: "/img/neptune_nircam.jpg"
summary: "Using JWST/NIRSpec, we detected Mg-rich clay minerals on Neptune's inner moons and rings — the first definitive detection of aqueously altered phyllosilicates on any outer solar system body beyond Jupiter, pointing to a catastrophic origin from the destroyed interiors of Neptune's primordial satellite system."
tags: ["Ice Giants", "Neptune", "JWST", "Small Satellites", "Phyllosilicates", "Rings", "Moons"]
category: "Ice Giants"
---

# Neptune's Inner Moons and Rings Are Exposed Icy Body Interiors

## Neptune is Weird

{{< figure src="/img/GiantPlanetMoons_diagram.png"
width="70%"
caption=`The satellite systems of the four giant planets, showing ring moons (blue),
regular satellites (purple), and irregular satellites (red) as a function of distance
from the planet. Neptune is a clear outlier: where every other giant planet has a
system of large regular satellites, Neptune has only Triton -- a Pluto-sized object
orbiting backwards.` >}}

One of the things I love about this plot is how immediately obvious it is that
Neptune doesn't fit in. Every other giant planet in our solar system has a system of large regular satellites -- moons that formed
around the planet itself. Jupiter has the Galilean moons, Saturn has Titan and its mid-sized icy siblings, and Uranus has five mid-sized icy moons. Neptune has none of that. Over 99% of the mass of its satellite system is concentrated in a single object, Triton, which orbits retrograde. Triton didn't form around Neptune, it was captured from the Kuiper Belt, and in the process almost certainly destroyed whatever satellite system Neptune had before.

Whether Neptune ever had a system of large regular moons is actually an important open question. In the simplest picture, the answer takes our statistics on how commonly satellite systems form around ice giants from 50% to 100%, which is not trivial when we're trying to understand how these systems form around other stars as well.

One way to approach this question is to look at what's left behind: the small inner moons and rings that orbit close to Neptune today. These bodies are small, dark, and so close to the planet that Neptune's scattered light overwhelms them, making detailed spectroscopic characterization extremely difficult. Until very recently, almost nothing was known about their compositions.

## The Data

A few years ago, my co-PI Matthew Belyakov and I proposed to use JWST/NIRSpec to obtain the first near-infrared spectra of the small inner moons and rings of both Uranus and Neptune. NIRSpec's integral field unit (IFU) mode takes a spectrum at every pixel in the field of view simultaneously, which when combined with JWST's remarkably sensitivity, makes it possible to separate the faint moons from the planet's scattered light. It also produces some genuinely beautiful data:

{{< figure src="/img/JWST_IFU_larissa_rings.png"
width="50%"
caption=`JWST/NIRSpec IFU images of Larissa and Neptune's rings, created from
wavelength slices between 2.1--2.35 µm, acquired when Larissa was on opposite sides
of Neptune. Neptune's rings are clearly visible, with the calculated ring positions
overlaid in gray.` >}}

You can see Larissa on opposite sides of Neptune on two different dates, and the
rings are clearly visible and bright enough to extract spectra from, which was not a
given going in. From these data cubes, we extracted spectra of Proteus, Larissa,
Galatea, and the rings. And when we saw those spectra, we were pretty surprised and honestly a little baffled.

## Not What We Were Expecting

The first thing that stood out: all four targets have anomalously deep (~60-70%), broad 3 µm OH absorption bands. When outer solar system objects have OH bands this deep, they invariably show clear signatures of water ice as well -- overtone bands at 1.5 and 2 µm, a Fresnel peak at 3.1 µm, a broad 4.5 µm feature. The Uranian ring moons have all of these. Water-rich Kuiper Belt objects have all of these. Neptune's inner moons have none of them. There are also essentially no volatile signatures except maybe a trace of CO2 on Proteus, and nothing measurable on the others. These objects are unlike anything else known in the outer solar system: deeply hydrated, apparently volatile-depleted, and spectrally anomalous.

{{< figure src="/img/figure1.png"
width="70%"
caption=`JWST/NIRSpec spectra of Neptune's inner moons and rings. (A) Normalized
reflectance spectra of Proteus, Larissa, Galatea, and the rings, showing the deep
3 µm OH band and absence of water ice signatures. (B) Continuum-removed 2.72 µm
absorption band compared to CM2 carbonaceous chondrite laboratory spectra (purple)
from the RELAB spectral library. (C) Comparison with asteroid spectra (Bennu and
Ceres) and CM2 chondrites in order of increasing aqueous alteration; Neptune's moons
match the most aqueously evolved end of the sequence.` >}}

The really diagnostic piece, though, is a subtle additional absorption feature sitting on the short-wavelength shoulder of that broad 3 µm band, visible on Larissa, Galatea, and the rings but absent or very weak on Proteus. To isolate it, we continuum-removed the spectra by dividing by a scaled version of Proteus's spectrum, essentially using Proteus as a proxy for the underlying 3 µm continuum behavior. The result: a sharp, somewhat asymmetric absorption band centered at 2.72 µm -- the characteristic fundamental absorption of phyllosilicates, the aqueously altered clay minerals seen in carbonaceous chondrite meteorites. Specifically, the match to CM2 carbonaceous chondrites is nearly perfect. Spectral matches this clean between planetary data and laboratory spectra are genuinely uncommon, which made this detection both exciting and immediately demanding of explanation.

## What CM2-Like Phyllosilicates Are Telling Us

CM and CI chondrites are among the most primitive solar system materials available for laboratory study. They contain phyllosilicates -- typically 60-80% by volume -- that formed through prolonged aqueous alteration of primary silicates (olivine, pyroxene) inside their asteroid parent bodies. This is not a surface process: the phyllosilicates form deep in the interior, where the parent body generated enough radiogenic heat to melt its water ice, allowing that liquid water to slowly react with the surrounding rock over millions of years.

The degree of aqueous alteration is recorded in the spectra. Less-altered samples show a broader, more iron-dominated feature centered around 2.85-2.9 µm; as alteration progresses, the feature sharpens and shifts to 2.72 µm as the composition becomes increasingly magnesium-dominated. The phyllosilicates on Larissa, Galatea, and the rings sit near the magnesium end of this spectrum, consistent with the most aqueously evolved CM2 chondrites -- a composition that probably required sustained contact with liquid water on timescales of order 1-10 Myr.

None of those conditions exist on small moons at 30 AU, where surface temperatures are around 40-60 K. In-situ formation is also ruled out thermodynamically: interior evolution models suggest that even Miranda (D ~470 km) almost certainly required substantial tidal heating to melt water ice in its interior. Larissa and Galatea are roughly 2.5 times smaller than Miranda. Collisional production doesn't work either -- impact-induced thermal metamorphism in meteorites is associated almost exclusively with the dehydration of phyllosilicates, not their formation.

This material had to have formed deep inside a much larger body, and then been exposed and incorporated into the small moons and rings we see today.

## A Catastrophic Origin

The most natural mechanism for exposing deep interior material is catastrophic disruption. At Neptune, the obvious candidate event is Triton's capture.

{{< figure src="/img/NepSats_press_diagram.png"
caption=`Proposed origin of Neptune's present-day inner moon system. Neptune once
had a system of large moons; Triton's arrival destroyed them, exposing material from
deep in their interiors. A small fraction reaccreted into today's small inner moons
and rings, carrying fingerprints of those ancient interiors.` >}}

We favor the interpretation that Neptune originally hosted a system of large regular moons -- perhaps comparable to what we see at Uranus today -- that were destroyed when Triton was captured. Triton's chaotic retrograde orbit would have fallen right in the middle of those moons' orbital space, driving them into crossing trajectories and ultimately into collisions with each other, creating a debris disk. Most of that material was lost: the current inner moon system contains only about 1% of the mass expected if Neptune had started with a Uranus-like system. A small fraction reaccreted into the inner moons and rings we see today.

Interestingly, the debris disk is also dynamically convenient for another reason. Capturing Triton is straightforward, but circularizing its orbit fast enough that it doesn't escape the system again has been a long-standing problem in the literature. Interactions with a satellite debris disk provide a highly efficient mechanism for dissipating that orbital energy. The destruction of Neptune's original satellite system and the stabilization of Triton's orbit may therefore be two sides of the same process.

Independent support for this picture comes from our companion paper (Belyakov et al. 2026, Science Advances), which presents JWST/NIRSpec spectroscopy of Nereid. Long classified as an irregular satellite, Nereid is compositionally and dynamically anomalous relative to every other irregular satellite in the solar system. Its spectrum does not match any known Kuiper Belt population; the closest spectral analogue in the outer solar system is actually Miranda. Matt's dynamical simulations demonstrate that it is possible to perturb an initial regular satellite onto a Nereid-like orbit during Triton's capture and have it survive Triton's circularization -- something that occurs in roughly 20% of the simulations he ran. Nereid may be the only surviving intact member of Neptune's original satellite system.

We cannot entirely rule out the alternative scenario in which a large differentiated KBO was tidally shredded within Neptune's Roche limit, which would also expose interior phyllosilicate material. But the Nereid evidence and the dynamical constraints on Triton's capture make the primordial satellite destruction scenario the more compelling explanation.

## Open Questions

There are two glaring open questions that we don't yet have answers to.

The first is the missing water ice. If these moons reaccreted from a debris disk that included material from large icy moons, a significant water ice component would be expected. We see essentially none. One possibility is that if the moons were still predominantly liquid water oceans with thin ice shells at the time of disruption, collisional heating could have vaporized much of the water to escape velocity -- but this requires careful modeling that hasn't been done.

The second is the identity of the 3 µm hydrated phase. Every moon and the rings share a deep OH band from an unidentified mineral that doesn't match anything in existing spectral databases -- and I have genuinly looked at thousands of laboratory spectra in the process of trying to identify it. It is present across the entire inner system, including Proteus, which lacks the phyllosilicates, suggesting it represents a distinct hydrated component shared by all of these bodies. Identifying it will likely require new laboratory measurements under outer solar system conditions, but could ultimately place constraints on the peak temperatures and pressures reached inside Neptune's original moons, and therefore on how large they were.

## Why This Matters

The interiors of large icy moons are normally inaccessible. Spacecraft can measure gravity fields and magnetic signatures, and thermal models can make predictions, but the actual bulk composition of the deep interior remains largely unconstrained by direct observation. Neptune's inner moons may be the only place in the solar system where that material is directly exposed -- because a catastrophic event essentially turned those ancient worlds inside out.

Beyond Neptune, the clay mineralogy we're seeing looks strikingly similar to what is found in the most aqueously altered meteorites and on Ceres. This implies that when icy outer solar system material is heated enough to melt water ice, it undergoes essentially the same geochemical evolution as inner solar system material -- either because the rocky building blocks were broadly similar across the protosolar disk, or because aqueous alteration drives them toward the same mineralogical end state regardless of their initial composition.

Stay tuned for more upcoming results from this JWST program!

---

**Paper:** Davis, M.R., Belyakov, M., Wong, I., Milby, Z., and Brown, M.E. (2026).
"Neptune's Inner Moons and Rings Are Exposed Icy Body Interiors."
*Science Advances*. [https://doi.org/10.1126/sciadv.aeb1437](https://doi.org/10.1126/sciadv.aeb1437)

**Nereid paper:** Belyakov, M., Davis, M.R., Wong, I., Batygin, K., and
Brown, M.E. (2026). "Nereid as a Regular Satellite of Neptune."
*Science Advances*, 12(21), eaeb1429.
[https://doi.org/10.1126/sciadv.aeb1429](https://doi.org/10.1126/sciadv.aeb1429)

**Data:** Available at MAST under program ID 4645. Reduction code archived at
[Caltech Data](https://data.caltech.edu/records/vwdse-4d488).