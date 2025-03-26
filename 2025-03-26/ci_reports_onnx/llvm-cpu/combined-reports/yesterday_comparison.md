# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_agentmodel__AgentModel|Numerics|progression|1.465|1.3415|-0.1235|-8.43%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|4965.8552|5032.5549|66.6997|1.34%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5750.7822|5840.4742|89.692|1.56%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5336.3696|5392.8711|56.5015|1.06%|

## No Regressions Found

## One Progression Found:

|model name|old_status|new_status|
|---|---|---|
|xcit_nano_12_p16_224_dist|Numerics|PASS|

