Code created using OpenCode
Create Trees.Py file worked on first try
Tree_GUI.PY file had errors on lines 54, 102, and 150. 
Error on line 54 was fixed by fixing cmds.setAttr to set all three RGB values on overrideColorRGB
Erorr on line 102 caused the GUI to not work properly but was fixed by fixing cmds.intField → cmds.intFieldGrp with value1
Error on line 150 was fixed by converting select kwarg to the correct index and converting columWidth to columnWidth3
The GUI not changing tree color when clicking "Generate" was fixed by creating and assigning lambert materials via hypershade 
