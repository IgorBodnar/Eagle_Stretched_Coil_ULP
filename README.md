# Stretched Coil Generation
 There are two ulp scripts that can be found in the ULP directory:
 ## Single side generation
 The spript 'stretched_coil_single_side.ulp' is capable of generating a stretched coil on a single side from the following parameters:
 * Length: the length of the outermost turn in mm
 * Width: the width of the outermost turn in mm
 * Inner Length: the length of the innermost turn in mm
 * Inner Width: the width of the innermost width in mm
 * Track Width: the width of the track making the coil in mm
 * Number of Turns: the total number of turns to be generated
 
 This spript is capable of generating coils in both winding directions being clockwise or counterclockwize.

 ## Single side generation
 The spript 'stretched_coil_double_side.ulp' is capable of generating a stretched coil on a both top and bottom sides of PCB,
 and shares the similar controls.

 ## Important
 * None of the scripts will generate anything besides the track itself, any connections and via placements are user responsability.
 * Neither of the scripts performs validity checking on the input parameters, hence the user is responsible of validating the design prior to running the script.
