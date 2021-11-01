# Turkish-German University  and Technical University Berlin
## Marlin-Configuration-with-G-Code-Translator-for-SCARA-Robot-based-3D-Printer

The aim of this project is to create a full solution for the reverse engineering process, from creating a 3D-Model of a real object using a simple camera to the manufacturing of that object using a SCARA-Robot based 3D-Printer (which is part of the project too).

This repository include the used marlin configuration with the necessary G-Code translator to generate G-Code that is compatible with the designed SCARA-Robot. The G-Code translator is a program that approximate the translational movements, which are automatically generated using a slicer software, using rotational movements of the joints of our SCARA-Robot. The quality of this approximation in the software can be adjusted by reducing the quality parameter in the setting.txt file, but this can lead to worse result if the robot is not able to achieve the required accuracy in its movements.

## Team Members:
    - Baraa ALSALEH
    - Barış Arya CANTEPE
    - Berin GÜLER
    - Beyzanur KAHYAOĞLU
    - Fırat ERCAN
    - Husam HAMU
    - Oğuzhan DEREBAŞI
    - Yiğit ATALAY
