# Controller Problem

```bash
[ INFO] [1691759262.929574264, 739.627000000]: 0.367363 0.000000 -0.258914
[ INFO] [1691759262.929818219, 739.627000000]: 0.367363 0.000000 -0.258914
[ INFO] [1691759262.931006080, 739.628000000]: 0.367363 0.000000 -0.258914
[ INFO] [1691759262.974300270, 739.636000000]: 0.367363 0.000000 -0.258914
[ INFO] [1691759262.974702835, 739.636000000]: 0.367363 0.000000 -0.258914
```

The above is error output in delx, dely, delz
This turns out to be a persistent bias. Note that this has been printed from
`./pud_control/src/library/lee_position_controller.cpp`
![Alt text](image.png)
