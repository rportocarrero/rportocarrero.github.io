
Cascaded systems break up the system into more manageable systems.  In the cascaded systems, outer and inner loops can be designed with root locus, bode plots ,or coefficient matching.   For cascaded feedback loops, the outer loops must be slower than the inner loops.  First, you build the controller for the inner loop, and make its dynamic soo fast that you can approximate it with a constant.  Cascaded control systems are used in vehicle steering systems   
  
![[Pasted image 20231019204936.png]]  
  
Outer-loop controller with 'fast' inner loop  
![[Pasted image 20231019210733.png]]  
  
After designing the outer loop you can verify that the inner loop has not altered the dynamics much. 
  
[[Cascaded Control for Bicycle Vehicle Control Systems]]  
[[Splitting higher-order control systems into smaller ones]] - prerequisite for building cascaded controllers.   
[[Cascaded control system design]] - build this first.  
[[Cascaded Control for Bicycle Vehicle Control Systems]]  

#bevlyMECH4420Lecture  
#bevlyMECH3140Lecturea