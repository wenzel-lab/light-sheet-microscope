# light-sheet microscope
Appropriate technology open source light sheet microscope design, for 3d imaging and high throughput droplet cytometry.
This is a modification of the OpenUC2 light sheet design - a project that can be explored by [website](https://openuc2.com) and [GitHub](https://github.com/openUC2/openUC2.github.io). This version has been developed as part of a [crowd funded project](https://experiment.com/projects/developing-a-low-cost-high-sensitivity-solution-for-phage-viral-load-detection) on experiment.com by Tobias Wenzel and Benedict Diederich. In the Wenzel Lab, Matías Hurtado has also contributed to the design of several cubes, and the re-design of Inventor designs of [UC2 cubes in OnShape](https://cad.onshape.com/documents/6ad90b1b9211810137d71b1d/w/b1b0cc05a0494bf4bc912f91/e/37e5ce9fc21af2a3e931ec46?configuration=Distances%3D0.03%2Bmeter&renderMode=0&uiState=668f4aab4587f461c0a71ce5).

<p align="left">
<img src="./images/cube-arrangement.png" width="400">
</p>

Illumination arm:
1) Fiber coupler, colimator, 5mm mask, all mounted on one threaded UC2 insert. Fiber coupler and colimator: Thorlabs AD11F with F280FC-A. The 5mm mask was 3d printed to cut the beam to the optimal size for the Powell lense.
3) Powell-lense and optional slit
   <p align="left">
  <img src="./images/Powell_lense_aligner.jpg" height="300"> <img src="./images/adjustable_slit.gif" height="300" width="300">
  </p>
4) cylindrical lense f=150mm (or 100mm in cube 5, or 50mm in cube 6)
   <p align="left">
  <img src="./images/cylindrical_lense1.jpg" height="300">
 <img src="./images/cylindrical_lense2.jpg.jpg" height="300">
  </p>
  
5) kinematic mirror (optional if using a straight illumination arm or a shorter focal length cylindrical lense)
6) empty
7) sample holder
8) XYZ stage for sample
   
Detection arm:
10) 1- 5x Objective
  2- Focus motor 
11) 1- Optical filter
   2- Tube-lense and camera
   
There is also crontol electronics, a playstation controller, and an a computer running Ubuntu
