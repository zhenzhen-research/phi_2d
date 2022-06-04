#phi_2d

##usage\
Calculating gravitational potential of a 2D surface density map using Fast Fourier method (FFT)\

Parameters:&emsp;data:Surface density array in unit of g/cm^2\
&emsp;&emsp;&emsp;dx  : Array pixel length in unit of cm\
&emsp;&emsp;&emsp;dy  : Array pixel width in unit of cm\
&emsp;&emsp;&emsp;H   : Half-thickness of density layer in unit of cm\
Returns:&emsp;phi : Gravitational potential array of the surface density

##how to run
'''
import phi_2d

phi = phi_2d.phi_2d(data=2d_density_array, dx=1, dy=1, H=0)
'''

##notes
If you use this code in your project, please refer to the paper [Gong H., Ostriker E. C., 2011, ApJ, 729, 120]