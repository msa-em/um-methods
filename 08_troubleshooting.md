---
title: Troubleshooting Guide
---


::::{tab-set}

:::{tab-item} Compression 

:::{list-table}
:header-rows: 1

*   - **Symptoms**
    - **Causes**
    - **Solutions**
*   - inconsistent thickness and shape, wrinkled appearance
	- dull knife, excessive feed rate, wrong clearance angle
	- reduce cutting speed, increase clearance angle, install sharper knife, reduce feed rate, monitor cutting force
:::

:::{tab-item} Chatter


:::{list-table}
:header-rows: 1

*   - **Symptoms**
    - **Causes**
    - **Solutions**
*   - regular oscillation marks on sections, "ripping"
	- vibration, loose mounting, resonance
	- identifying vibration sources, improve isolation, check block mounting stability, lower feed rate/speed
:::

:::{tab-item} Edge Chipping


:::{list-table}
:header-rows: 1
 
*   - **Symptoms**
    - **Causes**
    - **Solutions**
*   - irregular edges, debris in sections
	- knife dullness, excessive force, brittle fracture
	- lower feed rate, adjust approach angle, verify knife sharpness
:::

:::{tab-item} Empty Space/Bubbles


:::{list-table}
:header-rows: 1

*   - **Symptoms**
    - **Causes**
    - **Solutions**
*   - holes in section, sample drop out, chatter
	- bubbles inside the molten sulfur
	- heat sulfur slowly and evenly, avoid excess movement while embedding

:::



:::{tab-item} Discoloration


:::{list-table}
:header-rows: 1

*   - **Symptoms**
    - **Causes**
    - **Solutions**
*   - sulfur color change from light yellow to orange
	- overheating
		- monitor temperature carefully, use temperature-controlled heating and consistent calibration to avoid scorching, keep sulfur temperature below 120°C, do not re-use sulfur, discard discolored sulfur

:::

::::

## Examples

### Compression Artifacts

```{figure} ./figures/fig_34a.png

**Compression artifacts in STEM micrograph.** Microtomed section exhibiting two co-occurring sectioning artifacts. Periodic bands of alternating contrast running perpendicular to the cutting direction indicate chatter, arising from cyclic vibration at the blade-tissue interface during sectioning. Irregular wrinkling and distortion of structural features are consistent with compression, resulting from lateral forces exerted on the section as the blade advances through the block face. 
```


```{figure} ./figures/fig_29.png
**Solo-grain compression artifacts to visualize integrity of sectioned sample.** Early sections (A) exhibit pronounced sample compression along the cutting axis, as evidenced by irregular wrinkling, accordion-like folding, and distortion of boundaries. These artifacts arise before the blade reaches a stable equilibrium. Later sections (B), collected after the block face has been trimmed to a consistent depth and has been stabilized, show markedly reduced compression, with more uniform thickness and minimal wrinkling.
```

### Chatter

```{figure} ./figures/fig_34b.png
**Chatter artifacts in ultrathin sections prepared for transmission electron microscopy.** Artifacts of periodic bands of alternating lines, reflecting cyclic variation in section thickness caused by vibration at the blade-sample interface during sectioning. The spatial frequency of the chatter bands is determined by the interaction between cutting speed, blade advancement rate, and the resonant properties of the microtome arm and specimen holder. 
```
### Edge Chipping

```{figure} ./figures/chipped_edges_2.png
:name: edge_chip
:width: 100%
**Defects produced by a chipped diamond blade.** These appear as linear striations running parallel to the cutting direction, traversing the full section length. Unlike chatter bands, which are periodic and perpendicular to the cut, chip-derived marks occupy a fixed lateral position across all successive sections, reflecting the invariant location of the defect along the blade edge. Sample is displaced or torn at the striation, obscuring ultrastructural detail in affected regions. The artifact is confirmed by its consistency across a series and eliminated by advancing the specimen to an undamaged region of the knife edge.
```
### Bubbles/Voids

```{figure} ./figures/bubbles.png
:name: bubbles
:width: 100%
**Bubble formation within sulfur droplets.** This produces discrete voids upon solidification that compromise sample integrity in two principal ways. These bubbles disrupt adhesion between the embedding medium and the sample, leading to focal dropout during sectioning. In regions requiring mechanical stability for serial sectioning, bubble-derived holes propagate across successive sections, causing potential irreversible sample loss. 
```

### Overheated Sulfur

```{figure} ./figures/overheated_annotated_final.png
**Representative crystallized sulfur droplets showing correct (left) and overheated (right) samples.** The left droplet displays the expected coloration indicative of properly processed sulfur, while the right droplet exhibits an orange discoloration characteristic of thermal degradation or scorching. Overheating causes partial oxidation or structural changes in the sulfur crystal lattice, resulting in the observed color shift.
```
:::
