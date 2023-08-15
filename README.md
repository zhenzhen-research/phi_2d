
#usage

Calculating gravitational potential of a 2D surface density map using Fast Fourier method (FFT)

#how to run

import phi_2d
import acc_map_2d

phi = phi_2d.phi_2d(data=2d_density_array, dx=pixel_length, dy=pixel_length, H=layer_Half-thickness)
acc = acc_map_2d.acc(phi_2d=2d_phi_array, dx=pixel_length)