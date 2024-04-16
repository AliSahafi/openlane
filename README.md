# openlane
installation: https://www.youtube.com/watch?v=_AXknRBk4QI&t=444s

# Create a new dsign project
sudo make mount
./flow.tcl -design <design_name> -init_design_config -add_to_designs -config_file config.tcl

# Run code
./flow.tcl -interactive

source fa_synth.tcl
