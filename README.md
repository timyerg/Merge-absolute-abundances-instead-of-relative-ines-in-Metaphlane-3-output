This is a modified (only one line added to the original script from Metaphlan) script to merge "absolute" abundances instead of relative ones from Metaphlan output. 

Note that to get "absolute" abundances in addition to relative ones you need to run Metaphlan with ```-t rel_ab_w_read_stats``` added to the command.

### How to use:
Download the script, make it executable:

```
v=4 #metaphlan version
wget -O merge_metaphlan_tables_abs.py \
https://github.com/timyerg/Metaphlan-absolute-abundance-merger/blob/main/merge_metaphlan${v}_tables_abs.py?raw=true
```

```
chmod +x merge_metaphlan_tables_abs.py
```


Then run it as for relative abundance merging (provide the full path to the script to call it from the terminal).

Here is the link to Metaphlan3 repository: https://github.com/biobakery/MetaPhlAn
