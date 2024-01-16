# AD_MagneticModel
Data analysis of AD magnets to calculate magnets strenghts


## Step 1 (%% stands for the type of magnet you're considering):
In each magnet type folder you will find 2 codes:
  1) AnalysisMagneticMeasurements_AD_%% is the FIRST ONE to be run. It will take the data, analyse them and give in output the strenghts as a function of current
  2)  AD_%%_FromCurrent_ToAngle_Viceversa is the SECOND ONE to be run. For a given input value of current or strenght will provide in output the strenghts or the current, respectively.

## Step 2
Check that in the Define Machine Parameters code everything is well set up.
it might be needed to change the path to look for the files.
You can find the data relating the current to the strenght 9for quads) and the current to the angles (for dipoles) in their corresponding folders.

## Step 3
Run AD_OpticsMagneticModel

Twiss is done together with plot of aperture and acceptance.
At the end a comparison between the optics functions obtained using the strenghts coming from the value of currents and those previously found by Pavel is done.
The good agreement between the 2 shows the correctness of the procedure.
