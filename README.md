# LEO-Satellite
LEO Satellite 6-DOF Simulation implemented in C++ with project setup/build in C-make

Featuring Attitude Control, Orbit Control/station-keeping, and optimization for RCS thruster usage.

(Currently In Development), (I expect to be finished by the new year) (life got in the way)


Calendar progress goals:
  
  -by Dec 15 fully setup attitude portion of sim (does not include testing)
  
  -by Dec 17 have orbit controller/stationkeeping controller setup
  
  -by December 1st be in tuning phase
  
  -finish by Jan 23 the absolute latest
  
  [break until thanksgiving break]
  
  During holiday break:
    
    -setup orbit portion of sim for a simple circular LEO Orbit, no need to setup realistic perturbations just yet
    
    -setup VUW attitude frame as reference frame
    
    -work on making an in house r,v to keplerian elements conversion software in C++ to implement in this sim
  


Development progress log:

  -Nov 13: got controller setup to add and convert quaternions into the comparative MRP for the attitude control law, controller seems all setup
  -Nov 15: 
  -Dec 1: Paused progress on this project since I realized I didn't properly learn Linear Algebra well and opted to read and practice math instead of      this. Will continue progress once I have this sorted out.
