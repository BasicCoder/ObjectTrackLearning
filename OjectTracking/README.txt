Matlab script file to start:
  trackparam.m : loads a dataset and sets parameters up
  trackparamv6.m : trackparam script for matlab version 6.x
  runtracker.m : run tracking
so you can try 'trackparam; runtracker;' in matlab command window.
By default it tracks the 'dudek' sequence, but this can be changed by
editing the 'title' variable in trackparam.

Matlab functions:
  sklm.m : incremental SVD algorithm
  estwarp_condens.m : CONDENSATION affine warp estiomator
  affparam*.m : affine parameter handling functions
  interp2.dll : faster implementation of matlab interp2 function

Data files available:
  davidin300.mat : an indoor sequence of a person with lighting, pose changes
  car11.mat, car4.mat : cars on the street
  dudek.mat : subsampled dudek sequence from [15]
  sylv.mat : a toy under high light
  trellis70.mat : an outdoor sequence
  fish.mat : a fish porcelaine
  toycan.mat : a toy robot and a soda can
  
MoreData you can find in this site:
	http://cvlab.hanyang.ac.kr/tracker_benchmark/

Thank to Jongwoo Lim and David Ross, and this is their's personal site:
	http://www.cs.toronto.edu/~dross/ivt/