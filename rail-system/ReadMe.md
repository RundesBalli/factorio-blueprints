# :railway_track: Rail system

Right-hand rail system for five part trains.  
(e.g. 2x locomotive, 3x cargo-wagon)

## Blueprint-Book
All blueprints are collected in a blueprint book:  
[Blueprint book](blueprint-book.txt?raw=true)

## Various rail sections
:heavy_exclamation_mark: <b>Please refer to the notes at the end.</b>  

Straight:  
<img src="img/straight.png" alt="RundesBalli" width="450"/>  

T-Intersection:  
<img src="img/t-intersection.png" alt="RundesBalli" width="450"/>  

Intersection:  
<img src="img/intersection.png" alt="RundesBalli" width="450"/>  

Curve, 90 Degrees:  
<img src="img/curve%2C90deg.png" alt="RundesBalli" width="450"/>  

Turnaround:  
<img src="img/turnaround.png" alt="RundesBalli" width="450"/>  

Six waiting tracks and additionally two more after, as well as another one before:  
<img src="img/waiting-tracks.png" alt="RundesBalli" width="450"/>  

## Notes
### Traffic light before intersection
Please make sure you **remove** the traffic light before an intersection or T-intersection:  
<img src="img/traffic-light%2Cleft.png" alt="RundesBalli" width="600"/>  
<img src="img/traffic-light%2Cright.png" alt="RundesBalli" width="600"/>  

### No intersections one after the other
Don't place intersections one after the other, or you may create a train deadlock!  
<img src="img/intersection-placing%2Cdont.png" alt="RundesBalli" width="600"/>  
Place a straight line between intersections!  
<img src="img/intersection-placing%2Cdo.png" alt="RundesBalli" width="600"/>  
