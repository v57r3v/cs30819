java c
MENG 4019 - Practical 1 – 2022
Task: design and simulate the operation of a hydraulic curcuit. A hydraulic cylinder, stroke 2000 mm, D piston 60 mm, d rod 40 mm angled 60 degrees from horizontal is lifting a mass load of 4000 kg. The cylinder needs to be able to stop at intermediate positions.
Firrst, we build a conceptual circuit:
1. Open Automation studio, select and insert the following components from the Hydraulic set of components


2. Click on Filter to select, Right click on Filter, click on Lock Size to unlock, reduce size of Filter (drag it to a smaller size), Right Click on Filter, click on Lock Size to lock


3. Connect circuit as shown below:


4. Select the Simulation tab and run a Normal Simulation. Then, Stop Simulation and run a Slow-Motion Simulation


5. This shows that the circuit is correct, and it works. The cylinder can extend, stop when needed, and retract. The components are all connected, there is no error reported by the system
(To emulate an error, remove the connection between the filter and the tank. Try to run the circuit. An error will appear)


Re-connect the filter and the tank. Check that all is correct and works.
6. Double click on the hydraulic cylinder. Open the Data tab. Ensure the star at the top of the Component Properties is unselected. Modify the characteristics of the cylinder as in the task definition and close the Component Properties:


7. Run the circuit. It is clear that the force exerted by the pressure (at approx. 80 bar – due to the relief valve) is insufficient to move the load. The reading on the flow meter is zero, the piston is stuck.


8. Click on the relief valve and increase the cracking pressure CP to 120, 121, 122 bar. See the influence of increased pressure. The piston starts moving. 代 写MENG 4019 - Practical 1 – 2022SQL
代做程序编程语言To have a smooth and fast motion, set the pressure at 150 bar.


9. Decrease the pump’s displacement to 40 cm 3/rev. Examine the flow in the circuit.


10. Insert Node Dynamic, Differential Dynamic and Component Dynamic Measuring Instruments in strategic places to examine the operation of the circuit


11. Examine the dynamics of the operation of the circuit. Of particular importance are the pressure drops through different components. The whole circuit can be modelled as a series of resistances.


12. Click on the Y(t) plotter in the Simulation tab. Click on and drag the cylinder on the plotter. Select Linear Position, Linear Speed, Piston Side Pressure and Rod Side Pressure


13. Run the simulation in Slow Motion. You can see the wild and realistic variation of pressures and positions (due to oil and oil lines elasticity, inertia and friction). You can insert cursors, zoom in and out on x and y, display legend, select one or a couple of signals only, copy the plot and export the values for supplementary analyses.


14. Open Simulation Options in the Simulation Tab and in the Fluid Simulation pane, select perfect Lines.


15. Re-run the simulation. The spikes in pressure are a bit smaller, due to the elasticity of the hydraulic lines being removed as variable.


16. We want to be able to reduce the speed to about 150 mm/s (150 ±5 mm/s). This means we need to insert a variable throttle valve in the circuit (a variable hydraulic resistance).


17. Run the circuit in slow motion and modify the throttle valve opening (internal diameter) to set the speed as required. You can examine the speed value on the plotter or on the Component Dynamic Measuring Instrument


Save the project.





         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
