# AMSLite Rotary Spool Holder

This project provides 3D printable rotary spool holder models, including two versions: **Bambu Style** and **Universal Version**. The rotary spool holder helps maintain filament tension during printing, reducing the likelihood of tangling and lowering the risk of print failures.

## **Features and Benefits**

1. **Easy to Print & Print Optimized**  
   The design has been optimized to reduce the need for support structures and enhance Z-axis strength. By changing the print direction, you can achieve better strength.

2. **Low Cost**  
   The universal version uses only 59g of filament, and the version with secondary claws uses only 92g of filament. The hardware costs less than 1 RMB, making it very cost-effective.

3. **Wide Filament Reel Compatibility**  
   - **Secondary Claw System**: The design includes a flexible secondary claw system that can adapt to different filament reel hole diameters, improving stability and reducing the risk of tangling. The secondary claws can be removed from the shell and assembled onto the main claws, supporting larger reels, especially those with larger hole diameters (e.g., Jayo, Sunlu brands). This modular system ensures higher stability and minimizes the chances of tangling, making it suitable for filament reels with various core diameters.
   - **Universal Version**: The design keeps the bolt diameter as small as possible (the bolt area diameter is only 40.69mm), allowing for compatibility with smaller reels, such as Sunlu 250g filament reels. The original AMSLite cannot accommodate such reels, but the universal version can. The universal version has broader compatibility, uses fewer materials, and prints faster. While it requires screwing the nut for filament reel change, it won't suffer from plastic fatigue like the elastic claw version and won't have the dropping issue that the original version may have when locking the reel in place.

4. **Replaceable Parts**  
   Except for the claw components, all other parts of the Bambu style version are replaceable as spare parts in case the original version gets damaged.

## **Required Hardware**

The rotary spool holder requires two hardware components to function properly:

1. **Torsion Spring**  
   - **Wire Diameter**: 0.8mm  
   - **Outer Diameter**: 9mm  
   - **Number of Turns**: 5  
   - **Rotation Direction**: 180° Left or Right  
   - <img src="./assets/torsion_spring.jpg" width="300" alt="Torsion Spring" />

2. **Three-Wave Gasket**  
   - **For Universal Version**  
     - **Dimensions**: 25mm x 31mm x 0.4mm  
     - **Height**: 2.9mm  
     - <img src="./assets/waveform_gasket_m25_31.jpg" width="300" alt="Three-Wave Gasket" />
   - **For Bambu Style Version**  
     - **Dimensions**: 27mm x 34mm x 0.4mm  
     - **Height**: 3.1mm  
     - <img src="./assets/waveform_gasket.jpg" width="300" alt="Three-Wave Gasket" />

## **Project Folder Structure**

- **assets/**: Contains snapshots, real photos, and images of hardware components.
- **3mf/**: Contains 3MF files optimized for easy printing.
- **docs/**: Usage instructions.
- **stls/**: Contains 3D model files.
  - **xxx.stl**: Integrated model.
  - **xxx_pieces/**: Split model components for easier printing.

## **3MF Files**

To simplify the printing process, 3MF files are provided. The necessary model files, orientations, and support settings have been preconfigured in the 3MF files. These files have been tested, and you can directly use them in **Orca** or **Bambu Studio**.

### Bambu Style
- **all-in-one.3mf**: 3MF file for the rotary spool holder (with secondary claws), all parts are placed on one plate, including both green and yellow core options (select one).
- **amslite-rotary-spool-with-secondary-claws.3mf**: 3MF file for the rotary spool holder (with secondary claws), with parts distributed across three plates. The first plate includes the base, shell, main claw seat, and main claws; the second plate includes the shaft, shaft cover, core (green and yellow, choose one), and a 1.2mm gasket; the third plate includes the secondary claw seat and secondary claws.
- **others**: Five plates: the first plate includes all 10 sizes of gaskets, the second plate includes the torsion spring bending template (including both left and right versions), the third plate includes an all-in-one main claw seat, the fourth plate includes an all-in-one core (including both yellow and green), and the fifth plate includes an all-in-one shaft.

### Universal Version
- **universal-amslite-rotary-spool-holder-with-auto-rewind**: 3MF file for the universal rotary spool holder, including all required model files (base, shell, shaft, shaft cover, core, 1.2mm gasket, and reel nut).
- **universal-others**: Four plates: the first plate includes all 10 sizes of gaskets, the second plate includes the torsion spring bending template (including both left and right versions), the third plate includes an all-in-one core (including both yellow and green), and the fourth plate includes an all-in-one shaft.

### Other Files
- **torsion-spring-bending-template.3mf**: Includes the torsion spring bending template. The first plate is for left-hand springs, and the second plate is for right-hand springs.
- **amslite-spool-holder-cap-with-number.3mf**: Includes four numbered shaft caps (1, 2, 3, 4), useful for labeling filament reels.
- **ams-riser-v2-ams-lite-rotary-holder.3mf**: A rotary spool holder mount compatible with AMS Riser v2.
- **ams-riser-v2-ams-lite-rotary-holder-withAMS.3mf**: A rotary spool holder mount compatible with AMS Riser v2, printed separately with different colors for the yellow and green slots.

## **License**

This project is licensed under the [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/), feel free to modify and distribute with proper attribution.

## **Disclaimer**

Please note that the rotary spool holder and secondary claw system design is not intended for high-load applications or professional tool use. It is suitable for everyday 3D printing filament management.
