endsem project: kernal aware warp scheduler and warp sharing mechanism.


kernal awareness : checks the last issued cta to switch from age based to progress based warp scheduling to prevent gpu underutilization
warp sharing : oparend collector units are shared between warp schedulers to maximize the performance.
