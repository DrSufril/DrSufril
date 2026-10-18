# SayongVR — A Virtual Labu Sayong Experience

**Immersive heritage · Hand tracking · Volumetric 3D modelling · Digital fabrication**

SayongVR is a virtual pottery project that connects the traditional Malaysian craft of **Labu Sayong** with interactive 3D modelling and physical fabrication. It is designed to let learners and artisans explore pottery forms, sculpt digital clay with their hands, and take a finished design towards 3D printing.

## Why the project matters

Learning pottery usually requires access to materials, tools, and a suitable studio. SayongVR provides a virtual space for practising shapes and experimenting with designs before committing physical materials. Its cultural focus includes traditional vessel forms such as **Tela, Bocong, and Lepap**, supporting heritage education alongside creative design.

## Project demonstration

![SayongVR demonstration using a VR headset](../assets/sayongvr-demo.png)

*A project demonstration showing a VR headset and the pottery environment on connected displays.*

## Interaction and creative workflow

1. **Explore pottery forms:** work with Labu Sayong-inspired vessels in a virtual workshop.
2. **Shape the clay:** use tracked hands to pinch, push, and sculpt without handheld controllers.
3. **Refine the design:** adjust selected regions of the vessel through localized deformation.
4. **Decorate:** carve details, paint, and apply floral or geometric motifs through gesture-based interaction.
5. **Prepare physical output:** export the finished design for a ceramic or plastic 3D-printing workflow.

## How the 3D modelling works

![3D pottery model in the SayongVR modelling environment](../assets/sayongvr-model.jpg)

*A pottery model shown in the project's 3D modelling environment.*

The core approach is **Slice-Based Volumetric Modelling with Localized Deformation**:

| Component | Role in the system |
| --- | --- |
| **Stacked-disc representation** | Represents digital clay as a vertical stack of discrete slices, giving the modelling engine a volumetric structure. |
| **Localized deformation** | Updates the slices contacted by the user's fingers, limiting the region that must be recalculated during sculpting. |
| **Normalized slice height** | Expresses slice positions relative to the object's total height to support scaling and changes in resolution. |
| **Closed-loop structure** | Constrains the model with the aim of maintaining watertight geometry suitable for export. |
| **Export module** | Connects virtual design with downstream ceramic and plastic 3D-printing workflows. |

The architecture targets responsive sculpting on standalone mobile VR hardware while reducing geometry-repair work between modelling and fabrication.

## Prototype testing

The project presentation reports successful **ceramic printing through a specialist service in Thailand** and **internal PLA printing tests**, with the tested models requiring no manual mesh repair. These are reported prototype outcomes; they do not establish that every possible design or printer configuration will produce the same result.

## Intended applications

- **Heritage education:** introduce learners to Labu Sayong forms and traditional decorative motifs.
- **Schools, art programmes, and TVET:** support practice in spatial design, sculpting, and digital fabrication.
- **Museums and cultural centres:** provide an interactive way to engage visitors with traditional craft.
- **Artisans and small enterprises:** explore new vessel designs and prototypes before physical production.

Virtual iteration can reduce material use during design exploration. Physical printing and finishing still require the appropriate equipment, materials, and process.

## Project team

The project presentation credits:

- **Ahmad Sufril Azlan bin Mohamed** — School of Computer Sciences, Universiti Sains Malaysia
- **Siti Suhaily binti Surip** — School of the Arts, Universiti Sains Malaysia
- **Abhishek Kumar** — Computer Sciences, Universiti Sains Malaysia
- **Luo Yuqi** — School of the Arts, Universiti Sains Malaysia

## Intellectual property

**MyIPO patent application: PI 2026005263**  
**Title: Slice-Based Volumetric Modelling with Localized Deformation**  
**Status: Patent filed**

[← Back to profile](../README.md)
