# claudi-hyde

A pcb only project.



## About

A pcb only project.

## Why I Made This

_Explain your motivation and inspiration for this project._

## How to Build / Use

1. Order PCB from JLCPCB using files in `production/pcb/`
2. Print case from STL files in `CAD/case/`
3. Flash firmware from `firmware/`
4. Assemble using BOM.csv

## PCB

![PCB](docs/images/pcb.png)

## 3D Model

![Render](docs/images/render.png)

## Repository Structure

```
claudi-hyde/
├── CAD
  ├── 3d_pcb_pcb_claudia-2.0-the-real-thing_2026-05-14_2026-05-14.step
  ├── claudia-housing-3d-edit-file.step
  ├── claudia-housing-3d-edit-file.stl
  ├── claudia-housing-top-and-bottom-seperated.stl
  ├── inmp441-i2s-microphone-module-v15.step
  ├── mh-cd42.step
  ├── pcb-render-with-components.fcstd
  ├── pcb-render-with-components.step
  ├── sdreader.sldprt
  ├── sdreader.step
  ├── ssd1306_oled_display(128x64).f3d
  ├── ssd1306_oled_display(128x64).step
├── PCB
  ├── production
    ├── claudia-hyde.zip
    ├── gerbers.zip
├── assets
  ├── claudia-housing-3d-edit-file.slvs
  ├── pcb-render-with-components.20260515-083023.fcbak
  ├── sdreader.igs
├── docs
  ├── images
    ├── bottom.jpg
    ├── inmp441_i2s_microphone_module_2024-jan-21_01-26-45am-000_customizedview23271920973.png
    ├── inmp441_i2s_microphone_module_2024-jan-21_01-26-59am-000_customizedview22886314432.png
    ├── inmp441_i2s_microphone_module_2024-jan-21_01-33-05am-000_customizedview27688585423.png
    ├── inmp441_i2s_microphone_module_2024-jan-21_01-33-28am-000_customizedview11432358731.png
    ├── inmp441_i2s_microphone_module_2024-jan-21_01-34-49am-000_customizedview28916707655.png
    ├── oled-display-height.jpg
    ├── oled-display-width.jpg
    ├── ssd1306_oled_display(128x64)_angle_view.jpg
    ├── ssd1306_oled_display(128x64)_iso_view.jpg
    ├── top.jpg
├── firmware
  ├── config
    ├── pcb_pcb_claudia-2.0-the-real-thing_2026-05-14.json
    ├── pcb_pcb_claudia-2.0-the-real-thing_2026-05-15.json
    ├── sch_claudia-2.0-the-real-thing_2026-05-15.json
```

## Bill of Materials

| Part | Quantity | Link | Price (USD) |
|------|----------|------|-------------|
| _See BOM.csv_ | — | — | — |

---
*Organized with HackOrganizer v3 — Blueprint-compliant project structurer*