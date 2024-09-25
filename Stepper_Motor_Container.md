# Stepper Motor Container: Y axis control

{{BOM}}

[M3 x 10mm screw]: parts/mech/M3-10.md "{cat:mechanic}"
[M3 x 12mm screw]: parts/mech/M3-12.md "{cat:mechanic}"
[M2.5 x 5mm screw]: parts/mech/M2.5-5.md "{cat:mechanic}"
[M3 x 25mm HEX screw]: parts/mech/HEX-M3-25.md "{cat:mechanic}"
[Nut]: parts/mech/nuts.md "{cat:mechanic}"
[Blades]: parts/mech/blade.md "{cat:mechanic}"

[2 mm Ball-end Allen key]: parts/tools/2mmBallEndAllenKey.md "{cat:tool}"
[2.5 mm Ball-end Allen key]: parts/tools/2.5mmBallEndAllenKey.md "{cat:tool}"

[Inner Motor Holder]: models/Stepper_Motor_Container/LightSheet_Remake-Inner_Motor_Holder.stl "{previewpage}"
[New Axis Cube - Top]: models/Stepper_Motor_Container/LightSheet_Remake-New_Axis_Cube_Top.stl "{previewpage}"
[New Axis Cube]: models/Stepper_Motor_Container/LightSheet_Remake-New_Axis_Cube.stl "{previewpage}"
[Objective arm]: models/Stepper_Motor_Container/LightSheet_Remake-Objective_arm.stl "{previewpage}"

[Stepper Motor]: parts/elect/linear-stepper-motor.md "{cat: Electronic}"

[Objective]: parts/optics/objective.md "{cat: Optical}"

[Axis Control]: parts/mech/Axis-Control.md "{cat:mechanic}"
[LBX40-21H4U adapter]: parts/mech/Adapter_LBX40-21H4U.md "{cat:mechanic}"


![](images/Stepper_Motor_Container/Stepper_Motor_Container.jpg)

##Assembly

![](images/Stepper_Motor_Container/stepper-motor.gif)

## Base Structure:{PageStep}

* As shown in the GIF, join 2 [New Axis Cubes][New Axis Cube]{qty:2, cat: PrintedPart}, leaving its walls to the back, then add 2 [UC2 cubes](UC2files.md){qty:2, cat: PrintedPart}, generating an inverted "**L**" shaped structure.

## Place the guide and the motor:{PageStep}
* Place the [Inner Motor Holder]{qty:1, cat: PrintedPart} into the [UC2 cube][UC2 cubes] of the left.

## Stepper motor assembly:{PageStep}


1. Join the [Stepper Motor]{qty:1} with the [LBX40-21H4U adapter]{qty:1} using 4 [M2.5 x 5mm screws][M2.5 x 5mm screw]{qty:4} and tight with the [allen key][2 mm Ball-end Allen key]{qty:1}.


![](images/Stepper_Motor_Container/stepper-parts.jpg)



2. Take the assembled pieces and join the opposite side of the [LBX40-21H4U adapter] with the [Axis Control]{qty:1}, using 2 [M2.5 x 5mm screws][M2.5 x 5mm screw]{qty:2}

![](images/Stepper_Motor_Container/stepper-parts2.jpg)

## Place the [Stepper Axis Controller][Axis Control]:{PageStep}

* Using the [Allen key][2.5 mm Ball-end Allen key]{qty:1} and 4 [M3 x 12mm screw]{qty:4} screw the [Axis Control] into the wall of the [axis cube][New Axis Cube] on the edge.

## [Objective arm]:{PageStep}

* Using 3 [M3 x 10mm screw]{qty:3} place the [Objective arm]{qty:1, cat: PrintedPart} with the [Allen key][2.5 mm Ball-end Allen key], leave the middle screw pointing to the stepper motor.

![](images/Stepper_Motor_Container/objective-arm.jpg)



## Close the cubes:{PageStep}

![](images/Stepper_Motor_Container/screws-new-cube.gif)

 * Using the 2 [axis cube tops][New Axis Cube - Top]{qty:2, cat: PrintedPart} close the [new axis cubes][New Axis Cube]. For that take 4 [M3 x 10mm screw]{qty: 4} and tight them with the [Allen key][2.5 mm Ball-end Allen key], then do the same with the 2 [UC2 cubes](UC2files.md).

## The Objective:{PageStep}

Carefully screw the needed [objective][Objective]{qty: 1} into the [Objective arm].


![](images/Stepper_Motor_Container/objective-arm-installed.jpg)

>! Do not touch the lens directly to avoid getting it dirty or scratched.

---

#Now it's ready!

