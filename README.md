# ML-Assn6
Author: Jacob Craiglow
Email: craiglowj16@students.ecu.edu

Between linear, radial, and polynomial SVC there was a clear leader in accuracy.
Radial on average performs better than linear and polynomial svc. However if degree is tuned,
polynomial can achieve the same accuracy as radial.

Parameters:  
Linear - C can vary a lot from test to test but seems to stay within 3-7  
Radial - Similarly C varies quite a bit from low values of 2 to higher values of 7. The average seems to be about 3. Gamma is usually quite low. Being ~0.004  
Polynomial - C's in this SVC tend to be high. 7-9. The degree however is very stable in the 3.2-3.5 range.  
