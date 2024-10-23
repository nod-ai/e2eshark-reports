## Passing Summary

**TOTAL TESTS = 34**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 34 | 100.0% | 100.0% |
| IREE Compilation | 34 | 100.0% | 100.0% |
| Gold Inference | 34 | 100.0% | 100.0% |
| IREE Inference Invocation | 34 | 100.0% | 100.0% |
| Inference Comparison (PASS) | 34 | 100.0% | 100.0% |
## Fail Summary

**TOTAL TESTS = 34**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 0 | 0.0% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 0 | 0.0% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='local-task', backend='llvm-cpu', iree_compile_args=None, mode='ort-ep', torchtolinalg=False, stages=None, skip_stages=None, benchmark=False, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/onnxrt-iree-ep.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/onnxrt-iree-ep.md')

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| AlexNet_vaiq_int8 | PASS | None | |
| beit_base_patch16_384.in22k_ft_in22k_in1k | PASS | None | |
| deit3_large_patch16_224.fb_in1k | PASS | None | |
| deit_base_distilled_patch16_224.fb_in1k | PASS | None | |
| DenseNet201_vaiq_int8 | PASS | None | |
| efficientformer_l1.snap_dist_in1k | PASS | None | |
| EfficientNet_v2_s_vaiq_int8 | PASS | None | |
| eva_large_patch14_336.in22k_ft_in22k_in1k | PASS | None | |
| flexivit_base.1200ep_in1k | PASS | None | |
| flexivit_small.1200ep_in1k | PASS | None | |
| focalnet_base_lrf.ms_in1k | PASS | None | |
| focalnet_tiny_srf.ms_in1k | PASS | None | |
| gmixer_24_224.ra3_in1k | PASS | None | |
| gmlp_s16_224.ra3_in1k | PASS | None | |
| GoogLeNet_vaiq_int8 | PASS | None | |
| levit_256.fb_dist_in1k | PASS | None | |
| levit_384.fb_dist_in1k | PASS | None | |
| mixer_b16_224.goog_in21k_ft_in1k | PASS | None | |
| mixer_b16_224.miil_in21k_ft_in1k | PASS | None | |
| pit_b_distilled_224 | PASS | None | |
| pit_ti_224 | PASS | None | |
| poolformer_m36 | PASS | None | |
| poolformer_m48 | PASS | None | |
| RegNet_y_8gf_vaiq_int8 | PASS | None | |
| regnety_120.sw_in12k | PASS | None | |
| regnety_320.seer | PASS | None | |
| regnety_640.seer | PASS | None | |
| resmlp_big_24_224.fb_in1k | PASS | None | |
| ResNet152_vaiq_int8 | PASS | None | |
| resnet50_vaiq_int8 | PASS | None | |
| resnetrs420 | PASS | None | |
| VGG11_bn_vaiq_int8 | PASS | None | |
| VGG19_vaiq_int8 | PASS | None | |
| WideResNet_50_2_vaiq_int8 | PASS | None | |
