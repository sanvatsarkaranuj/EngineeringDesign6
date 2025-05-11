# Lab 9 
## YANG
### Instructions: 
Review lesson 9 in the GitHub repository. Install pyang and PlantUML. Copy ~/iot/lesson9/intrusiondetection.yang to ~/demo. Run pyang to generate intrusiondetection.yin and intrusiondetection.uml. Run PlantUML to generate intrusiondetection.png. Document results to your GitHub repository. 

---

## Installing pyang and PlantUML
To install pyang and PlantUML on my Mac I used the following commands: 
- `pip3 install -U lxml pyang`
- `pip3 install -U plantuml`

## Pyang
I copied intrusiondetection.yang into demo & switched to the demo directory with: 
- `cp ~/iot/lesson9/intrusiondetection.yang ~/demo`
- `cd ~/demo`

Then I executed the following commands to generate intrusiondetection.yin & intrusiondetection.uml while also showing the instrustiondetection file in .yang, .yin, and .uml forms.
- `cat intrusiondetection.yang`
- `pyang -f yin -o intrusiondetection.yin intrusiondetection.yang`
- `cat intrusiondetection.yin`
- `pyang -f uml -o intrusiondetection.uml intrusiondetection.yang --uml-no=stereotypes,annotation,typedef`
- `cat intrusiondetection.uml`

Pictured below are the contents of the intrusiondetection file in each format.
</br>

### .yang:
![Image](https://github.com/user-attachments/assets/30942101-5646-4793-9f97-4b454f480b4d)

</br>

### .yin:
![Image](https://github.com/user-attachments/assets/775d69d8-8b08-4efd-a121-2dc1a2e5c0cb)

</br>

### .uml: 
![Image](https://github.com/user-attachments/assets/d503c309-4a6b-4329-b82f-6cfe7693b17a)

</br>

## PlantUML
I ran the command `python3 -m plantuml intrusiondetection.uml` to create a sequence diagram in PNG format. Then I installed & ran GIMP and Pinta in order to display the PNG file. To do this I used the following commands: 
- `brew install gimp pinta`
- `cd ~/demo`
- `open -a Pinta ~/demo/intrusiondetection.png` Note: I used this command since `pinta intrusiondetection.png` was not working on my computer
- `gimp -h`
- `gimp -a intrusiondetection.png`

The same PNG image was shown within both the Pinta and GIMP applications. 
### PNG image
![Image](https://github.com/user-attachments/assets/bd838881-3bae-4ba9-821b-2ceaaf53efbb)
