# Preliminary results (RFMiD, 128 px, ResNet-18, 80 epochs)

Linear probe, binary Disease_Risk, held-out 20%, mean test AUROC over 5 seeds.

```
n_per_class              10     25     50    all
encoder                                         
ImageNet              0.645  0.667  0.692  0.757
SimCLR (spatial)      0.587  0.589  0.619  0.692
SimCLR + FACT (ours)  0.592  0.598  0.632  0.744
random init           0.582  0.611  0.649  0.736
```

Preliminary: short schedule, single dataset, binary proxy task.
