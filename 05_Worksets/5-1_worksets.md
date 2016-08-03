## DPS Worksets Best Practices

DPS has adopted a methodology for worksets that utilizes **UniFormat** to logically name worksets. The portion that applies is specifically the **Top Level** of UniFormat, with a discipline designator as a prefix.

**Naming and Organization System** <img align="right" src="images/01-uniformat.png">
* Based on Top Level of Uniformat
* Prefixed with a Discipline Designator
 * A Architectural
 * M Mechanical
 * E Electrical
 * P Plumbing
 * S Structural
 
>Example: **A_Shell**

<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>

##The following tables indicate the base worksets that DPS typically utilizes.
###Standard Worksets
Default Worksets (required)| Generic (off by default)
---------------------------|-------------------------
A_Workset1                 |X_Hidden (host elements)
A_Shared Datum Elements (levels, grids, scope boxes)   |X_Entourage (RPC content, rendering specific items)

###Additional Worksets
Optional                 | Linked Files (off by default)
---------------------------|-------------------------
A_Shell                |X_CAD
A_Interiors                |X_MEP
A_Interior Finishes                |X_Sketchup
A_Equipment & Furnishings                |
A_Services                 |
A_Sitework                 |
