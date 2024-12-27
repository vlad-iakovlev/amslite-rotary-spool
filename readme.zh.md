# 回转轴复制品

本项目是回转轴（Ratory Spool）的3D模型复制品，旨在替代大部分原始部件。它需要两个额外的硬件组件：**三波形垫片**和**扭簧**。该项目包含用于打印的3D模型文件、方便在Orca或Bambu Studio中打印的3MF文件，以及硬件组件的规格说明。

## 目的

回转轴的目的是在使用过程中保持耗材的张力，减少缠线的可能性，降低打印失败的风险。

本项目的目标是**降低成本**，因为官方售价为69元人民币每个。

## 项目优势

- **易于打印**：模型经过3D打印优化和加固，确保易于打印，并且适用于常见的3D打印机。
- **低成本**：切片仅需要82g的材料，所需硬件组件的成本约为1元人民币。

## 文件夹结构

- **assets/**：包含快照、实物照片和硬件组件图片。

- **stls/**：包含用于打印的3D模型文件。

  - **torsion_spring_bending_templates/**：包含用于弯折扭簧的模板。
    - **torsion_spring_bending_template_left.stl**：用于左旋扭簧的模板。
    - **torsion_spring_bending_template_right.stl**：用于右旋扭簧的模板。

  - **core_parts/**：包含核心部件，分为两种版本（绿色和黄色）。根据需要打印绿色或黄色版本。
    - **green_version/**：绿色版本的核心部件。
      - **body_part.stl**：核心本体部分（绿色）。
      - **core_fixed_clip.stl**：核心固定卡子（绿色）。
    - **yellow_version/**：黄色版本的核心部件。
      - **body_part.stl**：核心本体部分（黄色）。
      - **core_fixed_clip.stl**：核心固定卡子（黄色）。
    - **common_parts/**：通用部件（绿色和黄色通用）。
      - **torsion_spring_center.stl**：扭簧中心部分（通用）。
      - **torsion_spring_short_end_clip.stl**：扭簧短端固定卡子（通用）。

  - **shaft_parts/**：包含中轴部件，分为四个部分，方便打印。
    - **round_shaft_part.stl**：圆轴部分。
    - **bottom_disc_contact_waveform_gasket.stl**：与三波形垫圈接触的下圆饼。
    - **top_disc_contact_core.stl**：与核心接触的上圆饼。
    - **torsion_spring_long_end_clip.stl**：扭簧长端固定卡子。

  - **shaft_cover.stl**：中轴盖。
  - **base.stl**：底座。
  - **pressure_gaskets/**：一系列压力调节垫片，厚度范围从0.2mm到2.0mm。
  - **claw_seat/**：包含爪座部件。
    - **claw_seat_complete/**：完整的爪座。
    - **claw_seat_base/**：爪座本体部分。 # 请打印3个
    - **claw_seat_clip/**：卡爪片，每个爪座需要2个卡爪片。 # 请打印6个卡爪片（每个爪座需要2个卡爪片）
  - **claw/**：爪部件。
    - **basic/**：基本款爪，形状与原始爪相似。 # 请打印3个
  - **shell(thickened).stl**：加厚后的外壳。

- **3mf/**：包含方便打印的3MF文件。

  - **all-in-one.3mf**：回转轴的3MF文件，所有部件在一个板上，包括绿色和黄色核心，根据需要选择一个版本并取消选中另一个。

- **docs/**：使用说明文档。

  - **user_guide.md**：用于组装和使用回转轴的用户指南。

- **LICENSE**：本项目的许可协议。

## 所需硬件

此模型需要两个硬件组件才能正常工作：

1. **三波形垫片**  
   - **尺寸**：27mm x 34mm x 0.4mm  
   - **高度**：3.1mm  
   - ![三波形垫片](./assets/waveform_gasket.jpg)

2. **扭簧**  
   - **线径**：0.8mm  
   - **外径**：9mm  
   - **旋转角度**：180度，左旋/右旋  
   - ![扭簧](./assets/torsion_spring.jpg)

## 3MF文件

为了简化打印过程，提供了3MF文件，直接在Orca或Bambu Studio中使用：

- **all-in-one.3mf**：回转轴的3MF文件，所有部件在一个板上，包括绿色和黄色核心，您可以根据需要选择一个版本并取消选中另一个。

只需在Orca或Bambu Studio中打开3MF文件，您就可以开始打印了！

## 组装说明

1. 使用合适的扭簧弯折模板（torsion_spring_bending_template_left.stl或torsion_spring_bending_template_right.stl）弯折扭簧，具体使用哪一个取决于您需要左旋还是右旋的扭簧。
2. 组装核心部件，选择适合的版本（绿色或黄色）。
3. 中轴部件已拆分成四个部分，组装时需要粘合部件。
4. 选择适当的压力垫片进行安装。

