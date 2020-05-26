#goHome validation
To know if the Robot has reached pre-programmed location after invoking goHome action, we can invoke action "rotate" with input "0" 
so that it rotates 0 degrees (that means no rotation - its x,y,z coordinates remains the same). Now if this rotate action's output 
co-ordinates (x,y,z) matches the pre-programmed location coordinates of goHome action, then it has succeeded.
