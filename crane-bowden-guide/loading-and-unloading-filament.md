# Loading and Unloading Filament

## Loading and Unloading Filament:

Once your printer has been **homed** you will need to **heat the nozzle** in order to **load your filament** and start your print.

{% hint style="info" %}
The temperature of the nozzle will be dependent upon the type of filament you choose to use for your first print, for the included test print we ask that **PLA** be used. Recommendations vary on the best temperature to use for PLA, but for this test print we ask that you **heat the nozzle to 200C.**
{% endhint %}

Using your **Duet Web Control Interface** you can set your nozzle tool temperature in the **tools section** by clicking in the **Active** column in the **Tool 0** row. 

![Duet Web Control Tool section](../.gitbook/assets/duettoolssettingthetemp.jpg)

You can also set the nozzle temperature by using the **LCD Menu** on your M3D Crane Bowden. Simply use the knob to select the **temperature value** and turn the knob until you reach the desired setting:

![Setting the Nozzle temperature](../.gitbook/assets/settemp.jpg)

 Once your nozzle is up to temperature you may insert your **PLA** filament. Send flush cut **filament** through the entrance of the **extruder** **located at left side of the printer**. While **depressing the leaver on the extruder, feed the filament through the bowden tube and into the hot end**.

![Loading the M3D Crane Bowden](../.gitbook/assets/loadingunloadingbowden.jpg)

 As the filament hits the hotend, it will heat up and start to liquefy. The filament may start to seep out of the nozzle.

![Loading the M3D Crane Bowden](../.gitbook/assets/loadingbowden.jpg)

{% hint style="info" %}
It is recommended to **extrude 50 to 100 mm** of filament right away to ensure correct loading, heating, and that there are no blockages in the nozzle or bowden tube. 
{% endhint %}

Using the **Duet Web Control Interface** you can easily control the Extruder. In the **Extruder Control** section you can **extrude** \(or retract\) filament, select the **Feed amount** and set the **Feedrate** in mm per second. Once you have set the Feed amount and Feedrate simply click **Extrude** \(or Retract should you need to\).

![Duet Web Control Extruder Control](../.gitbook/assets/duetextrudercontol.jpg)

Should you choose to use the **LCD Menu** on your M3D Crane Bowden when loading your filament, simply use the knob to select **Prepare** from the Main Menu Screen. 

![Main Menu](../.gitbook/assets/menu2.jpg)

Then select **Move Axis**:

![Move Axis ](../.gitbook/assets/moveaxisbowden.jpg)

Next select **Move E**:

![Move E](../.gitbook/assets/selectaxis.jpg)

Here you will find options to **extrude \(+\)** or **retract \(-\)** mm of filament, Selecting +10 will extrude 10mm, simply select **+10 multiple times** in a row to extrude 50 to 100mm:

![Extrude +10mm](../.gitbook/assets/extrudebowden.jpg)



To **Unload the Filament** simply maintain your nozzle temperature **while depressing the leaver on the extruder. \(This will disengage the extruder gears so the filament will be free to move\)** Grab hold of the filament and pull it out with a sweeping, fluid motion. The filament will be slide up and out of the nozzle, out of the bowden tube and out the extruder.  

After mastering the art of Loading and Unloading Filament on your M3D Crane Bowden, you'll want to start looking for 3D models to print as well as a slicer to convert them into gcode. Follow the guide to the next section to learn where to find your 3D models as well as the programs to slice them. 

