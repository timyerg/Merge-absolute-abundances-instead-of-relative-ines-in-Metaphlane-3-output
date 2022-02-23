This is a modified (only one line added to the original script from Metaphlan3) script to merge "absolute" abundances instead of relative ones from Metaphlan3 output. 

Note that to get "absolute" abundances in addition to relative ones you need to run Metaphlan3 with ```-t rel_ab_w_read_stats``` added to the command.

### How to use:
Download the script, make it executable:

```wget https://github.com/timyerg/Metaphlan3-absolute-abundance-merger/blob/main/merge_metaphlan_tables_abs.py?raw=true -O merge_metaphlan_tables_abs.py```
```chmod +x merge_metaphlan_tables_abs.py```


Then run it as for relative abundance merging.

Here is the link to Metaphlan3 repository: https://github.com/biobakery/MetaPhlAn
