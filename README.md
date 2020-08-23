<!DOCTYPE html>
<html>
<head>
<style>
.column {
  float: left;
  width: 50%;
  padding: 5px;
}

.row::after {
  content: "";
  clear: both;
  display: table;
}
</style>
</head>
# Monte_Carlo_Stock_Simulation
Using the Alpaca API  to query the database for 5 years of data of daily stock returns for a hypothetical portfolio, Monte Carlo simulation of 1,000 simluations. Then visualizing the simulations.
<br>
<br>
<style>
.column {
  float: left;
  width: 50%;
  padding: 5px;
}

.row::after {
  content: "";
  clear: both;
  display: table;
}
</style>
### Equal weighted portfolio
<div class="row">
  <div class="column">
    <img src="Images/MC_fiveyear_sim_plot.png" alt="Snow" style="width:100%">
  </div>
  <div class="column">
    <img src="Images/MC_fiveyear_dist_plot.png" alt="Forest" style="width:100%">
  </div>
</div>
<!-- ![](Images/MC_fiveyear_sim_plot.png)
![](Images/MC_fiveyear_dist_plot.png) -->

### AT&T 60% Weight

![](Images/MC_att_fiveyear_sim_plot.png)
![](Images/MC_att_fiveyear_dist_plot.png)

### Nike 60% Weight

![](Images/MC_nike_fiveyear_sim_plot.png)
![](Images/MC_nike_fiveyear_dist_plot.png)

### Exxon 60% Weight
![](Images/MC_exxon_fiveyear_sim_plot.png)
![](Images/MC_exxon_fiveyear_dist_plot.png)

