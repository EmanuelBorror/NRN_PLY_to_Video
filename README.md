# NRN_PLY_to_Video
This script is designed to take .ply files describing a neuron morphology (froma an swc file) and apply a simulated current to the soma of the cell. The simulation then shows the propagation of the voltage through the cells neurites. This propagation of voltage is visualized with a colored .ply file iterated over time resulting in a video.

# How to use: 
Firstly, import run_nrn_sim.py into a new script with "import run_nrn_sim." Ensure that when you do this, the file run_nrn_sim.py is in the same folder as your new script. To run the simulation simply call the function "main". This might look like:
import run_nrn_sim as rns  
rns.main(input_ply, swc_file, frames_output_path)  

"main" has 4 input arguments described in the function definition.    
input_ply is the path to your input file on your computer. 
swc_file is the swc_file that describes the ply file. 
frames_output_path is a path to a folder on your device from which you want to have the frames of the generated video temporarily stored.
