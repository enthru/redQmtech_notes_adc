# redQmtech_notes_adc

This is the working template/example of the LTC2208 ADC module for DIY HF receiver/transceiver.

This is the almost first PCB made by me and the purpose of the board is just to create cheap and simple ADC module for my test transceiver based on the Xilinx QMTech board without spending alot of time. It has non optimal design. 

So consider it as the start point of making your ADC module, because looks like there lot of space to improve.

Anyway it's working. So it's usable.

It has LPF in the input- cutoff frequency is around 60MHz.

Use R6 and R7 resistors to choose output mode of the ADC (check datasheet, but R6 should be soldered for my project).

Use R4 and R5 to enable LTC6400IUD driver or bypass it.




Github for Xilinx bitstream - https://github.com/enthru/redQmtech_notes

Some history of the project - https://enthru.net/?tag=qmtech

EasyEDA project - https://oshwlab.com/neuroworker/redqmtechadc