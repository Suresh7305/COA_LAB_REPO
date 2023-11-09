endsem project: kernal aware warp scheduler and warp sharing mechanism (KAWS).


kernal awareness : checks the last issued cta to switch from age based to progress based warp scheduling to prevent gpu underutilization

warp sharing : oparend collector units are shared between warp schedulers to maximize the performance.

On execution of kaws, the following are the comparisions of performances:


![image](https://github.com/Suresh7305/COA_LAB_REPO/assets/140541932/059be593-1a9a-4d90-b7e2-48941fc4e24b)

![image](https://github.com/Suresh7305/COA_LAB_REPO/assets/140541932/b99a4865-4629-48f3-8a4d-f33fbee9f3b0)

![image](https://github.com/Suresh7305/COA_LAB_REPO/assets/140541932/67a24a6d-a5bb-4063-a85d-bd9837f0c033)

