# fanuc virtual milling practices
practicas de fresado mediante codigo de simulacion para control de maquinaria CNC

## Practica
![image](https://github.com/Gaddiel0710/fanuc_virtual_milling_practices/assets/135661300/f57edd6d-fe06-41a6-9f96-784105eeaec3)

## Codigo en C++ para la fresadora CNC 
```C++
[BILLET X100 Y80 Z30;
[TOOLDEF T1 D2;
N10 G21 G94;
N20 G90 G28 X0 Y0 Z0;
N30 M06 T1 D2;
N40 M03 S600;
N50 G90 G00 X5 Y10 Z30;
N60 G01 Z-20 F120;
N70 G03 Y5 X10 R7.5;
N80 G01 X90;
N90 G03 X95 Y10 R7.5;
N100 G01 Y70;  
N110 G03 Y75 X90 R7.5;
N120 G01 X10;
N130 G03 X5 Y70 R7.5;
N140 Y10;

N150 G00 Z30;
N160 G90 G00 X21 Y17;
N170 G01 Z-20 F120;
N180 G03 R5;

N190 G00 Z30;
N200 G90 G00 X79 Y17;
N210 G01 Z-20 F120;
N220 G03 R5;

N230 G00 Z30;
N240 G90 G00 X21 Y63;
N250 G01 Z-20 F120;
N260 G03 R5;

N270 G00 Z30;
N280 G90 G00 X79 Y63;
N290 G01 Z-20 F120;
N300 G03 R5;

N310 G00 Z30;
N320 G90 G28 X0 Y0 Z0;
N330 M06 T2 D6;
N340 M03 S600;
N350 G90 G00 X35 Y40;
N360 G01 Z-20 F120;
N370 G02 R15;

N380 G00 Z30;
N390 G90 G28 X0 Y0 Z0;
N400 M28;
```

## CNC CODE RESULT
_Resultado en 2D_
![image](https://github.com/Gaddiel0710/fanuc_virtual_milling_practices/assets/135661300/35f1c1c3-0ad3-4d33-a87d-68dda87e4bbf)

_Resultado en 3D_
![image](https://github.com/Gaddiel0710/fanuc_virtual_milling_practices/assets/135661300/27deb448-4976-483e-b16a-e4aeadb98125)
