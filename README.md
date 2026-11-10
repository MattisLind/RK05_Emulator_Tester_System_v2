# RK05 Emulator/Tester System v2
The RK05 Emulator/Tester System v2

[HP 7900A / 13210A compatibility feasibility study](design_notes/HP7900A_13210_Feasibility_Study.md)

[HP 7900A development and diagnostic plan](design_notes/HP7900A_Development_Plan.md)

[HP drive-end adapter wiring and pin map](design_notes/HP7900A_Adapter_Wiring.md)

![Finished Emulator](https://github.com/user-attachments/assets/a5d5110d-fa6c-41bd-b9b7-0f5a37e94339)

<p>The RK05 Emulator/Tester v2 system consists of a main unit, various cables, a terminator, and a power supply. The primary improvement of v2 is that is can emulate and test drives with up to 32 sectors. The DEC RK05 has a maximum capability of 16 sectors but other drives such as some members of the Diablo series 30 family can support up to 32 sectors.

<p>The RK05 Emulator/Tester main unit can be configured to function either as an RK05 disk drive emulator or as an RK05 disk drive tester. The specific function is determined by the software in the Raspberry Pi Pico and the FPGA firmware. Currently, the RK05 disk emulator functions have been rigorously tested. The RK05 disk drive tester functions have been used to test the emulator but full tester functionality is not yet complete.

<p>The Emulator/Tester main unit is designed so it can be connected using the same cables and terminators used with a real RK05 disk drive.
