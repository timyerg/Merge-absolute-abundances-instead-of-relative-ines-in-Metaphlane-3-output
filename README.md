This is a modified (only one line added to the original script from Metaphlan3) script to merge "absolute" abundances instead of relative ones from Metaphlan3 output. 

Note that to get "absolute" abundances in addition to relative ones you need to run Metaphlan3 with ```-t rel_ab_w_read_stats``` added to the command.

Download the script, make it executable (```chmod +x merge_metaphlan_tables_abs.py```) and run it as for relative abundance merging.
