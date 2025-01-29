# AMS Lite Rotary Spool with Secondary Claws

This project provides a 3D printable rotary spool with an optional secondary claw setup for 3D printers. The rotary spool helps in maintaining the filament tension during printing, reducing the likelihood of tangled filament and print failure.

## Features & Advantages

1. **Easy to Print & Print Optimized**: The design is optimized for easy printing, the split makes it easy to print, reduces the need for the support structure, and the part that needs to be strengthened in the Z-axis direction is splited, and the printing direction can be changed to obtain better strength.
2. **Secondary Claw System**: The design includes a flexible secondary claw system that can be easily adapted to support filament rolls with varying core hole diameters, improving stability and reducing the risk of tangling. The secondary claws can be detached from the shell and assembled onto the main claw, allowing the spool to accommodate larger filament rolls with wider center holes (such as those from Jayo). This modular system ensures greater stability and minimizes the likelihood of filament tangling, making it versatile for different spool sizes.
3. **Cost-Effective**: The design is cost-efficient, requiring only 92g of filament material. The hardware cost is less than 1 RMB, making it an affordable option.
4. **Replaceable Parts**: Except for the claws, all other parts of the model are designed to replace the original versions, providing flexibility for upgrades and customization.

## Preview - Rotary Spool with Secondary Claws

Here are some shaded view images of the rotary spool with secondary claws:

- **Original and Combined Form**
  
  <img src="./assets/shaded-view-rotary-spool-with-secondary(original2combined).png" width="300" alt="Shaded View of Original and Combined Form" />

- **Exploded Assembly View**
  
  <img src="./assets/shaded-view-rotary-spool-with-secondary-explode-form.png" width="300" alt="Exploded Assembly View of Rotary Spool" />

- **Real Shots**
  
  <img src="./assets/real_shots/IMG_20250107_203339.jpg" width="300" alt="Real Shot - original view" />
  <img src="./assets/real_shots/IMG_20250107_202936.jpg" width="300" alt="Real Shot - assembly view" />
  <img src="./assets/real_shots/IMG_20250107_203029.jpg" width="300" alt="Real Shot - top" />
  <img src="./assets/real_shots/IMG_20250107_203210.jpg" width="300" alt="Real Shot - bottom" />


### Demonstration GIF

### Supports Standard Size Spool Center Hole  
The original form of the Ratory Spool (with secondary claws mounted on the shell), suitable for most filament brands, such as Bambu, Tinmorry, etc.  
<img src="./assets/gif/origin.gif" width="300" alt="Dynamic Display - Origin" />

### Supports Large Size Spool Center Hole  
The combined form of the Ratory Spool (with secondary claws mounted on the main claws), suitable for large-center-hole filament brands, such as Jayo, etc.  
<img src="./assets/gif/combined.gif" width="300" alt="Dynamic Display - Combined" />



## Required Hardware

This model requires two hardware components to function properly:

1. **Three-Wave Gasket**  
   - **Dimensions**: 27mm x 34mm x 0.4mm
   - **Height**: 3.1mm  
   - <img src="./assets/waveform_gasket.jpg" width="300" alt="Three-Wave Gasket" />

2. **Torsion Spring**  
   - **Wire Diameter**: 0.8mm  
   - **Outer Diameter**: 9mm  
   - **Number of Turns**: 5  
   - **Rotation**: 180-degree left-hand/right-hand twist  
   - <img src="./assets/torsion_spring.jpg" width="300" alt="Torsion Spring" />
  

## 3MF Files

To make printing easier, 3MF files have been provided for direct use with **Orca** or **Bambu Studio**:

- **all-in-one.3mf**: 3MF file for the ratory spool(include secondary claws), all in one plate, include both green and yellow core, you should uncheck one according to yourself.
- **amslite-rotary-spool-with-secondary-claws.3mf**: 3MF file for the ratory spool(include secondary claws), divide into 3 plates, first one include main claw seats, main claws, base, shell; second one include core(both green and yellow, you should uncheck one according to yourself), shaft, cover, 1.2mm gasket; third one include secondary claw seats and secondary claws
- - **others**: Five plates: the first includes all 10 sizes of gaskets, the second includes torsion spring bending templates (both left and right versions), the third is the integrated main claw seat, the fourth is the integrated core (green and yellow), and the fifth is the integrated shaft.

Simply open the 3MF files in **Orca** or **Bambu Studio**, and you'll be ready to print!

## Assembly Instructions

1. **Main Assembly**:
   - First, print the **base.stl**, **shaft_cover.stl**, and **shell_with_secondary-claws(thickened).stl** files. These parts are the foundation of the rotary spool. 
   - **Recommendation**: It is recommended to print **shell_with_secondary-claws(thickened).stl** because it includes all the functionality of **shell(thickened).stl**. If you wish to add the secondary claw system later, based on this shell, you only need to add the secondary claw seats and claws. If you don’t need the secondary claw system, simply use **shell_with_secondary-claws(thickened).stl** without the additional parts.

2. **Claw Assembly**:
   - The **basic.stl** is designed for the standard rotary spool and does not have the necessary slots for secondary claws. It should not be used if you want to add the secondary claw system.
   - The **main claws** should be printed using **main_claw_with_secondary_slots.stl** if you plan to use the secondary claws to support larger filament rolls with bigger center holes. This main claw has slots that can accommodate **secondary_claw.stl**.
   - The **secondary_claw.stl** can only be combined with **main_claw_with_secondary_slots.stl** or **secondary_claw_seat.stl**. These parts include the necessary slots to fit the secondary claws.
   - **Recommendation**: It is recommended to print **main_claw_with_secondary_slots.stl** because it includes all the functionality of **basic.stl**. If you wish to add the secondary claw system later, based on this claw, you don't need to reprint the main claw. If you don’t need the secondary claw system, simply use **main_claw_with_secondary_slots.stl** without the additional parts.

3. **Claw Seats**:
   - The main and secondary claw seats are printed using **main_claw_seat.stl** and **secondary_claw_seat.stl**, respectively.

4. **Core Parts**:
   - If you prefer to print the core as a single piece, use **green_version.stl** for the green version or **yellow_version.stl** for the yellow version.
   - If you prefer to print the core in separate parts and assemble them with glue, use the following, the advantage of printing separately is reduced support material and optimized strength.:
     - For the green version, print the parts from **green_version_pieces/** and **common_pieces/**.
     - For the yellow version, print the parts from **yellow_version_pieces/** and **common_pieces/**.
   - The **common_pieces/** folder contains parts that should be printed regardless of which version you choose (green or yellow), such as the torsion spring center and short-end clip.

5. **Pressure Gaskets**:
   - Select a suitable gasket thickness based on your assembly's needs, from **pressure_gaskets/**. 

6. **Shaft**:
   - The shaft assembly has two versions:
     - **One-piece version**: **shaft.stl** is the complete model for the shaft, which can be printed as a single piece.
     - **Separate pieces version**: If you prefer to print the shaft in parts and assemble them with glue, print the parts from the **shaft_pieces/** folder. The advantage of printing separately is reduced support material and optimized strength.

7. **Torsion Spring Bending**:
   - If you need to bend the torsion spring, use the **torsion_spring_bending_template_left.stl** or **torsion_spring_bending_template_right.stl** from the **torsion_spring_bending_template/** folder.


## Licensing

This project is licensed under the [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).

## Notes

- Ensure you check the correct version (green or yellow) of the core parts for compatibility with your other components.
- The assembly may require a few additional tools such as screws or clips, which are not included in the 3D model files but are commonly available.

## Conclusion

The AMS Lite Rotary Spool with Secondary Claws provides an easy-to-print solution for managing filament spools, reducing print failures, and accommodating larger filament rolls.
