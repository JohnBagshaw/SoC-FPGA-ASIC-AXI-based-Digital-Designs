# SoC-FPGA-ASIC-AXI-based-Digital-Designs
AXI-based digital design examples

Key steps taken:
- Developed a custom AXI-lite 32-bit multiplier IP
- Added desired functionality/logic
- Developed a validated block design using the custom AXI IP
- Added SystemILA for digital design verification and debugging (primarily for design integration)
- Generated Bitstream and exported HW to generate XSA file
- Launched Vitis, primarily for the next two steps
- Wrote C codes to test design functionality and trigger SystemILA
- Utilized the processing system (PS) to pass input test parameters

Attached are:
- Custom block design including the custom AXI IP SystemILA
- Generated schematic for implemented design
- PnR (Place and Route) diagram of custom digital design for ASICs and digital design prototyping

![FPGA_axiL_mult_CustomBlockDesign_ZynqPS](https://user-images.githubusercontent.com/84130776/186403811-f093eec3-b3ba-457c-a0b1-39901b1a2eb1.PNG)
![FPGA_axiL_mult_imp_ILA_DesignSchematic](https://user-images.githubusercontent.com/84130776/186403857-755a0cfc-0316-4a14-ac62-ebf79fb9f7e0.PNG)
![FPGA_axiL_mult_imp2PnR_ILA](https://user-images.githubusercontent.com/84130776/186403895-3c962114-da39-449a-a6e6-be9807ca54a0.PNG)
