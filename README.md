# CONFIGURAÇÕES DE IMPRESSORAS IFMAKER

## TITANIUM LIGHT
 - Eixo X: 300mm
 - Eixo Y: 300mm
 - Eixo Z: 220mm
 - Start G-CODE: 
	```
	G28 
	G29
	G1 X0 Y0 F7000
	M109 S{material_print_temperature} T0
	G92 E0
	M420 Z1,G1 Z2.0 F3000
	```
 - End G-CODE:
 	```
 	M104 S0
	M140 S0
	M84
	M107
	G28 X
	```
	
	

## GTMAX CORE H4
 - Eixo X: 300mm
 - Eixo Y: 200mm
 - Eixo Z: 420mm
 - Start G-CODE: 
	```
	G28
	G29
	G1 X0 Y0 F7000
	M109 S{material_print_temperature} T0
	G92 E0
	G1 Z1.0 F3000
	G1 X0.1 Y20 Z0.3 F5000.0
	G1 X1.1 Y150.0 Z0.3 F1500.0 E15
	G1 X1.4 Y150.0 Z0.3 F5000.0
	G1 X1.4 Y20 Z0.3 F1500.0 E30
	G92 E0
	```
 - End G-CODE:
 	```
 	M104 S0
	M140 S0
	M84
	M107
	G28 X
	```
	
	
