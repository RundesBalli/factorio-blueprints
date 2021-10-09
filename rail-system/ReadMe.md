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

Curve, 90 Degrees:  
<img src="img/curve%2C90deg.png" alt="RundesBalli" width="450"/>  

T-Intersection:  
<img src="img/t-intersection.png" alt="RundesBalli" width="450"/>  

Intersection, small:  
<img src="img/intersection-s.png" alt="RundesBalli" width="450"/>  

Intersection, large, space saving:  
<img src="img/intersection-l,ss.png" alt="RundesBalli" width="450"/>  

Intersection, large, space wasting:  
<img src="img/intersection-l,sw.png" alt="RundesBalli" width="450"/>  

Turnaround:  
<img src="img/turnaround.png" alt="RundesBalli" width="450"/>  

Six waiting tracks and additionally two more after, as well as another one before:  
<img src="img/waiting-tracks.png" alt="RundesBalli" width="450"/>  

Station with 1 loading area and 3 waiting tracks:  
<sub>(alternative with 1 loading area and 5 waiting tracks)</sub>  
<img src="img/station-1l,3w.png" alt="RundesBalli" width="450"/>  

Station with 2 loading areas and 6 waiting tracks:  
<sub>Make sure that both stations have the same names!</sub>  
<img src="img/station-2l,6w.png" alt="RundesBalli" width="450"/>  

Evenly (un-)loader:  
<sub>The circuit empties/fills the tanks so that liquid wagons are not (un-)loaded gradually but evenly.</sub>  
<img src="img/evenly-loader.png" alt="RundesBalli" width="450"/>  
<img src="img/evenly-unloader.png" alt="RundesBalli" width="450"/>  

## Notes
### Traffic light before intersection
Please make sure you **remove** the traffic light before an intersection or T-intersection or use the *«Straight, before intersection»* blueprint:  
<img src="img/traffic-light%2Cleft.png" alt="RundesBalli" width="600"/>  
<img src="img/traffic-light%2Cright.png" alt="RundesBalli" width="600"/>  

### No intersections one after the other
Don't place intersections one after the other, or you may create a train deadlock!  
<img src="img/intersection-placing%2Cdont.png" alt="RundesBalli" width="600"/>  
Place a straight line between intersections!  
<img src="img/intersection-placing%2Cdo.png" alt="RundesBalli" width="600"/>  

### Grid
If you don't place the blueprints on top of each other but next to each other, then you can build a grid that fits in itself.  
