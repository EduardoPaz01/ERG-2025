Both SPICE models were based on LM08XX and LM09XX structures, and the approximate values are based on the datasheet by me, EduardoPaz01. For applications requiring higher reliability, check the values and suggest improvements.

WARNING : PSIM must be the full version

To be able to simulate in Full PSIM, we need some configurations:

1. Download LTSPICE from the official website: "https://www.analog.com/en/resources/design-tools-and-calculators/ltspice-simulator.html"

2. Set the paths for LTSPICE within PSIM: 
	* Open PSIM
	* Open path control: (Options->set path)
	* Add in "SPICE Model Path" link: "C:\Program Files\ADI\LTSpice\lib"
	* Add in "LTspice Executable File Path" link: "C:\Program Files\ADI\LTspice\LTspice.exe"

3. Copy both spice models to the PSIM models folder: "C:\Program Files (x86)\PSIM\SPICElib"

4. Run LTSpice Simulation

