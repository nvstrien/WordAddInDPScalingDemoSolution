# WordAddInDPScalingDemoSolution
Demo project to illustrate DPI scaling problems with the Word Ribbon
The Ribbon shows a normal layout on a HD monitor, 

![HD-Monitor Ribbon](https://github.com/nvstrien/WordAddInDPScalingDemoSolution/blob/master/WordAddInDPScalingDemoProject/Ribbon_HD.jpg)

but the layout gets distorted on a 4K monitor.

![4K-Monitor Ribbon](https://github.com/nvstrien/WordAddInDPScalingDemoSolution/blob/master/WordAddInDPScalingDemoProject/Ribbon_4K.jpg)

Steps to recreate:
Open the solution in Visual Studio 2019
Build the solution by pressing F5
Move the Word Application Window between a full HD monitor and a 4K monitor and see the different ways in which the tab RibbonDPIScaling is shown.

Notes: 
- You need to have Office Word installed to run this solution.
- The Tab is called RibbonDPIScaling - the screenshots say EPD2022. 
