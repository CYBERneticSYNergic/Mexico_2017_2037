# Mexico_2017_2037
# Details of the parameters for the generation expansion planning in Mexico during the period 2017-2037
## December 2017
## Rodrigo Palacios 
## Eduardo Valdes eduardo.valdesga@uanl.edu.mx

The present data have been gathered from several sources with a strong concern to be as much as possible in agreement with real values to the Mexican situation. 

There are 50 regions of generation and 66 transmission lines. There are nine generation technology options for capacity additions include:  coal units, conventional steam units, gas turbines, gas combined cycle, nuclear, wind, solar, geothermal and hydro units.

The installed capacity of each region in 2016 appears in the file `ExiCap.txt` as a 50X9 matrix, where the rows are the regions  and the columns are the generation technologies. The installed capacity for the transmission lines appears in `ExiLin.txt`as a 66X9 matrix where each rows represent each transmission line. The first two columns are the tails nodes of the line, the third  column is the amount of installed capacity, the next columns represent the efficiency, the inversion cost for the installation of new line, the maintenance cost, the number of employments generated for the installation and the nu,ber of employments generated by maintenance, respectively. The number of employments are scaled to employment per transmited megawatt. <a href="#fig1">Figure 1</a> shows the geographical ubication of the generation regions, their names according to SENER Mexico and the transmission lines.

<p align="center">
<div id="fig1" style="width:300px; height=200px">
<img src="https://github.com/eduardovaldesga/Mexico_2017_2037/blob/patch-2/ExiLin.png" height="100%" width="100%"/><br>
<b>Figure 1.</b> Generation and transmission capacity for each region and transmission line respectively.  
</div>
</p>
