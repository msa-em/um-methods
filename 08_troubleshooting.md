---
title: Troubleshooting Guide
numbering:
  enumerator: A.%s
---


::::{tab-set}

:::{tab-item} Compression

```{list-table}
:widths: 15 15 30
:header-rows: 1

*   - **Symptoms**
    - **Causes**
    - **Solutions**
*   - inconsistent thickness and shape, wrinkled appearance
    - dull knife, excessive feed rate, wrong clearance angle
    - reduce cutting speed, increase clearance angle, install sharper knife, reduce feed rate, monitor cutting force
```

```{figure} ./figures/fig_34a.png
:name: compression_stem
:width: 100%
**Compression artifacts in STEM micrograph.** Microtomed section exhibiting two co-occurring sectioning artifacts. Periodic bands of alternating contrast running perpendicular to the cutting direction indicate chatter, arising from cyclic vibration at the blade-sample interface during sectioning. Irregular wrinkling and distortion of structural features are consistent with compression, resulting from lateral forces exerted on the section as the blade advances through the block face. 
```


```{figure} ./figures/fig_29.png
:name: compression_solo_grain
:width: 100%
**Solo-grain compression artifacts to visualize integrity of sectioned sample.** Early sections (A) exhibit pronounced sample compression along the cutting axis, as evidenced by irregular wrinkling, accordion-like folding, and distortion of boundaries. These artifacts arise before the blade reaches a stable equilibrium. Later sections (B), collected after the block face has been trimmed to a consistent depth and has been stabilized, show markedly reduced compression, with more uniform thickness and minimal wrinkling.
```

:::

:::{tab-item} Chatter

```{list-table}
:widths: 15 15 30
:header-rows: 1

*   - **Symptoms**
    - **Causes**
    - **Solutions**
*   - regular oscillation marks on sections, "ripping"
    - vibration, loose mounting, resonance
    - identifying vibration sources, improve isolation, check block mounting stability, lower feed rate/speed
```

```{figure} ./figures/fig_34b.png
:name: chatter
:width: 100%
**Chatter artifacts in ultrathin sections prepared for transmission electron microscopy.** Artifacts of periodic bands of alternating lines, reflecting cyclic variation in section thickness caused by vibration at the blade-sample interface during sectioning. The spatial frequency of the chatter bands is determined by the interaction between cutting speed, blade advancement rate, and the resonant properties of the microtome arm and specimen holder. 
```

:::

:::{tab-item} Edge Chipping

```{list-table}
:widths: 15 15 30
:header-rows: 1

*   - **Symptoms**
    - **Causes**
    - **Solutions**
*   - irregular edges, debris in sections
    - knife dullness, excessive force, brittle fracture
    - lower feed rate, adjust approach angle, verify knife sharpness
```

```{figure} ./figures/chipped_edges_2.png
:name: edge_chip
:width: 100%
**Defects produced by a chipped diamond blade.** These appear as linear striations running parallel to the cutting direction, traversing the full section length. Unlike chatter bands, which are periodic and perpendicular to the cut, chip-derived marks occupy a fixed lateral position across all successive sections, reflecting the invariant location of the defect along the blade edge. Sample is displaced or torn at the striation, obscuring ultrastructural detail in affected regions. The artifact is confirmed by its consistency across a series and eliminated by advancing the specimen to an undamaged region of the knife edge.
```

:::

:::{tab-item} Crystallization Failure: Empty Space/Sample plucking

```{list-table}
:widths: 15 15 30
:header-rows: 1

*   - **Issue:**
    - **Symptoms**
    - **Causes**
    - **Solutions**
*   - Sample fails to crystallize properly (e.g., incomplete, uneven crystallization), or crystallizes too quickly before proper nucleation can occur 
    - Holes in section, sample drop out, chatter, splintering
    - Can result from residual stress from improper crystallization incorrect cooling rate (too fast or too slow), contamination, or insufficient nucleation time, or bubbling inside the molten sulfur
    - Remelt the sample and repeat the crystallization step, adjusting the cooling rate so nucleation has time to occur properly; follow the specified temperature ramp and hold times. In addition, avoid excess movement while embedding to prevent disruption
```

```{figure} ./figures/bubbles.png
:name: bubbles
:width: 100%
**Bubble formation within sulfur droplets.** This produces discrete voids upon solidification that compromise sample integrity in two principal ways. These bubbles disrupt adhesion between the embedding medium and the sample, leading to focal dropout during sectioning. In regions requiring mechanical stability for serial sectioning, bubble-derived holes propagate across successive sections, causing potential irreversible sample loss. 
```

:::

:::{tab-item} Discoloration/Heating

```{list-table}
:widths: 15 15 30
:header-rows: 1

*   - **Issue:** Sulfur overheating and discoloration when not intentionally following a polymerization protocol (which involves controlled color/phase changes at higher temps)
    - **Symptoms**
    - **Causes**
    - **Solutions**
*   - sulfur color change from light yellow to orange, smoking, catching fire
    - heated too much or too fast
    - Reduce heating rate and closely monitor temperature; remove from heat immediately if smoking occurs and allow to cool before reassessing. Do not re-use sulfur

```

```{figure} ./figures/overheated_annotated_final.png
:name: overheated_sulfur
:width: 100%
**Representative crystallized sulfur droplets showing correct (left) and overheated (right) samples.** The left droplet displays the expected coloration indicative of properly processed sulfur, while the right droplet exhibits an orange discoloration characteristic of thermal degradation or scorching. Overheating causes partial oxidation or structural changes in the sulfur crystal lattice, resulting in the observed color shift.
```


:::{tab-item} Contamination on Grid

```{list-table}
:widths: 15 15 30
:header-rows: 1

*   - **Issue:** 
    - **Symptoms**
    - **Causes**
    - **Solutions**
*   - Contaminated grids from environment and/or manufacturing defects
    - Debris, residue, or contamination visible across the grid surface
    - Typically due to poor water quality, improper handling, fingerprints, not effectively cleaning the boat
    - Keep the instrument clean throughout sample thinning, wear gloves when handling grids or related components, use and verify ultra-pure water, and inspect all new/empty grids for defects before attaching a sample to rule out pre-existing issues


:::

::::
