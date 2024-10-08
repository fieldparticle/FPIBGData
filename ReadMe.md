# FPIBGDAta
Fast Index-based GPU particle Collision Detection

Overview

	This is the particle only version of the Fast Particle Index Based GPU (FPIBG) Collision detection repository.
	This version is for performance testing and software evaluation.
	
	The stepwise process for using the software is as follows:
	1. Download or clone the FPGIBG repository to some root directory
		<rootdir>/FPIBG
	2. Create a directory in the same root named FPIBG3rdPty
		<rootdir>/FPIBG3rdPty
	3. Follow the directions for dowloading 3rd party dependencies in the ReadMe.md located in 
		<rootdir>/FPIBG/vulkan directory.
	4. Clone tne data directory in the same root named 
		<rootdir>/FPIBGData
	5. Open the Vullkan Project and compile ParticleObly.exe, GenBenchData.exe, and PerformanceData.exe as debug.
	6. Run GenBenchData.exe to generate the three particle configuration data sets.
	7. Run particleOnly.exe in debug mode for the verification process. Three data sets will be created labelled as debug.
	8. Run PerformanceData.exe on the debug data which will verify the number of particles, threads, and collsions.
		If there are problems the application will alert you and stop. Ascertian what went wrong and run until all data sets are verifgied.
	9. Run particleOnly.exe in release mode for the performance process. Three data sets will be created labelled as release.
	10. Run PerformanceData.exe on the release data which will accumulate performance data and save it in a comma seperated performance file. 
	
	
