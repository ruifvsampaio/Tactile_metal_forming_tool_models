# 3D-Printable Tactile Forming Tool Models for Teaching

This repository provides the 3D-printable tactile tool models and supporting teaching materials that accompany the article:

> Sampaio RFV, Rosado PMS, Pragana JPM, Bragança IMF, Silva CMA, Martins PAF (2026). A Hybrid Project Based Leaning Approach for MSc Advanced Metal Forming Courses. *Advances in Industrial and Manufacturing Engineering*, Submitted for publication.

The models are physical, hands-on representations of industrial forming tools. They were developed to help students understand tool architecture, the kinematics of the forming stages, and how the tool components function together. We share them so that educators can reproduce, adapt and extend the teaching activities described in the article.

---

## Contents

| Folder | Description |
|--------|-------------|
| `models/` | STEP files of all tool components, grouped by tool set |
| `images/` | Rendered views and photographs of the printed models |

---

## Tool sets

### (a) Modular single-stage vertical tool

[`models/vertical_tool/`](models/vertical_tool/)

The modular single-stage vertical tool demonstrates the fundamental components of metal forming tools and the potential for flexibility in the construction of both structural and passive elements, such as support plates. 
For demonstration purposes, the tool is assembled using cylindrical magnets measuring 5 mm in diameter and 2 mm in thickness. Three configurations were developed: an open-die forging set with flat dies, a double-action radial extrusion set with floating dies and two identical steel springs, and a forward extrusion set. In the latter two configurations, plasticine is placed within the die cavities to enable the corresponding forming operations during instructional sessions.
While not representative of industrial practice, the container in the forward extrusion set is divided along the symmetry plane to facilitate removal of the formed plasticine billet, and the container support features a hole at the base to allow observation of the extrusion process.

![Modular single-stage vertical tool](images/vertical_tool.png)

### (b) Double-action horizontal tool

[`models/double_action_tool/`](models/double_action_tool/)

The double-action horizontal set incorporates cam-slide unit components, including wedges, wedge actuators, sliders, and rails, to convert vertical motion into horizontal motion. It also employs horizontal M10 tension bolts and stoppers to ensure tool rigidity during forming operations. 

![Double-action horizontal tool](images/double_action_tool.png)

### (c) Multi-stage combination tool

[`models/multi_stage_tool/`](models/multi_stage_tool/)

The multi-stage combination tool features blank holders and ejectors that use steel springs for proper function, as well as two sets of fixed dies for multi-stage processing. In this tool, the first die set performs combined punching and blanking, while the second set bends the part and flares its inner hole. This process is demonstrated during instructional sessions using commercial reinforced aluminium foil with a thickness of approximately 0.15 mm as the workpiece. The operator or demonstrator serves as the transfer system for this tool.

![Multi-stage combination tool](images/multi_stage_tool.png)

---

## Printing recommendations

The models were printed and tested with the following settings:

| Parameter | Value |
|-----------|-------|
| Process | FDM |
| 3D printer | Bambu Lab X1-Carbon |
| Material | PLA |
| Travel speed | 120 mm/s |
| Layer height | 0.2 mm |
| Infill | 25% |
| Supports | Not required |

All dimensions are in millimetres. Moving components are designed with clearances suited to the settings above. If you use another printer or material, you may need to adjust the clearances.

Assembly: The modular single-stage vertical tool makes use of cylindrical magnets measuring 5 mm in diameter and 2 mm in thickness for quick demonstration purposes. The other tools make use of M3 socket head bolts and threaded heat set inserts were utilized to assemble the different parts of the tools. Guide pillars are recommended to be lightly sanded for better sliding in the top bosters; the assembly of the pillars into the bottom bolsters is force-fit so it stays fixed. The double-action horizontal tool makes use of horizontal M10 threaded rods (to serve as tension bolts) and nuts.

---

## Teaching materials

Refer to the article for how these materials were integrated into the course and for the evaluation of the learning outcomes.

---

## Citation

If you use these materials in your teaching or research, please cite the article above.

---

## License

The models and teaching materials are released under the [Creative Commons Attribution 4.0 International License (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/). You may share and adapt them for any purpose, provided appropriate credit is given.
