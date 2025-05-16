# Comparator
- This is an analog voltage comparator which uses Strong Arm Latch as the comparator core.Strong Arm Latch is chosen because it has low dynamic offset , zero static power consumption and produces rail to rail output.Strong Arm latch works based onn the regenarative action.
- A pre amplifier used as the input stage to reduce the input referred offset of the strong arm latch.
- The strong arm latch is followed by NAND gate based SR latch to hold the output of the strong arm latch during the reset phase of the strong arm latch.
- The circuit is deesigned and developed using a 180nm PDK in cadence virtuoso.
