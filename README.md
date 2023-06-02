# OLM030
A compact 68030 accelerator for Amiga 500 with 68030FE33 in TQFP package

Based on the great accelerator from Matthias Heinrichs: 68030-TK2 available at https://gitlab.com/MHeinrichs/68030-tk2

Major changes compared to 68030-TK2:
- CPU changed to TQFP version, FPU removed to make the pcb smaller.
- Commonized bus drivers to simplify BOM
- Clock is fixed and defined by oscillator clock (CPU_clock = OSC_clock / 2)
- IDE connector changed to 44 pin 


# 3D render

![image](https://user-images.githubusercontent.com/81614352/224541039-dd512456-0e68-41b7-bb94-c1bc8a557cf9.png)


# Real PCB

![image](https://user-images.githubusercontent.com/81614352/224541071-97e07b29-4300-4a08-ba81-47a74e8a40a7.png)

# Test results

![image](https://user-images.githubusercontent.com/81614352/224541085-f21ab219-3ea0-4f82-9f79-f65024492c85.png)

After some hours of testing:

![image](https://github.com/OlegMishin/OLM030/assets/81614352/3286b74d-58db-4611-a2db-d7b12d81b448)
