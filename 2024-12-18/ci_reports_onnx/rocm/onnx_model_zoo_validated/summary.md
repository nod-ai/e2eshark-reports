## Passing Summary

**TOTAL TESTS = 190**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 179 | 94.2% | 94.2% |
| IREE Compilation | 50 | 26.3% | 27.9% |
| Gold Inference | 50 | 26.3% | 100.0% |
| IREE Inference Invocation | 50 | 26.3% | 100.0% |
| Inference Comparison (PASS) | 45 | 23.7% | 90.0% |
## Fail Summary

**TOTAL TESTS = 190**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 11 | 5.8% |
| IREE Compilation | 129 | 67.9% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 5 | 2.6% |
## Test Run Detail
Test was run with the following arguments:
Namespace(sources=['./e2eshark-reports/ci_reports_rocm_onnx_model_zoo_validated_text_onnx_json/onnx_model_zoo_validated_text.json', './e2eshark-reports/ci_reports_rocm_onnx_model_zoo_validated_vision_onnx_json/onnx_model_zoo_validated_vision.json'], output='./e2eshark-reports/onnx_model_zoo_validated.json', report=True, report_file='./e2eshark-reports/onnx_model_zoo_validated.md')

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| bertsquad-10 | compilation | None | |
| bertsquad-12 | compilation | None | |
| bertsquad-12-int8 | compilation | None | |
| bertsquad-8 | compilation | None | |
| bidaf-11-int8 | compilation | None | |
| bidaf-9 | compilation | None | |
| gpt2-10 | compilation | None | |
| gpt2-lm-head-10 | compilation | None | |
| gpt2-lm-head-bs-12 | setup | None | |
| roberta-base-11 | PASS | None | |
| roberta-sequence-classification-9 | compilation | None | |
| t5-decoder-with-lm-head-12 | PASS | None | |
| t5-encoder-12 | PASS | None | |
| FasterRCNN-10 | compilation | None | |
| FasterRCNN-12 | compilation | None | |
| FasterRCNN-12-int8 | compilation | None | |
| FasterRCNN-12-qdq | compilation | None | |
| MaskRCNN-10 | compilation | None | |
| MaskRCNN-12 | compilation | None | |
| MaskRCNN-12-int8 | compilation | None | |
| MaskRCNN-12-qdq | compilation | None | |
| ResNet101-DUC-12 | compilation | None | |
| ResNet101-DUC-12-int8 | compilation | None | |
| ResNet101-DUC-7 | import_model | None | |
| age_googlenet | setup | None | |
| arcfaceresnet100-11-int8 | compilation | None | |
| arcfaceresnet100-8 | PASS | None | |
| bvlcalexnet-12 | PASS | None | |
| bvlcalexnet-12-int8 | compilation | None | |
| bvlcalexnet-12-qdq | PASS | None | |
| bvlcalexnet-3 | import_model | None | |
| bvlcalexnet-6 | import_model | None | |
| bvlcalexnet-7 | PASS | None | |
| bvlcalexnet-8 | PASS | None | |
| bvlcalexnet-9 | PASS | None | |
| caffenet-12 | PASS | None | |
| caffenet-12-int8 | compilation | None | |
| caffenet-12-qdq | PASS | None | |
| caffenet-3 | import_model | None | |
| caffenet-6 | import_model | None | |
| caffenet-7 | PASS | None | |
| caffenet-8 | PASS | None | |
| caffenet-9 | PASS | None | |
| candy-8 | setup | None | |
| candy-9 | compilation | None | |
| densenet-12 | compilation | None | |
| densenet-12-int8 | compilation | None | |
| densenet-3 | import_model | None | |
| densenet-6 | compilation | None | |
| densenet-7 | compilation | None | |
| densenet-8 | compilation | None | |
| densenet-9 | compilation | None | |
| efficientnet-lite4-11 | compilation | None | |
| efficientnet-lite4-11-int8 | compilation | None | |
| efficientnet-lite4-11-qdq | Numerics | None | |
| emotion-ferplus-12-int8 | compilation | None | |
| emotion-ferplus-2 | import_model | None | |
| emotion-ferplus-7 | PASS | None | |
| emotion-ferplus-8 | PASS | None | |
| fcn-resnet101-11 | PASS | None | |
| fcn-resnet50-11 | PASS | None | |
| fcn-resnet50-12 | PASS | None | |
| fcn-resnet50-12-int8 | compilation | None | |
| fcn-resnet50-12-qdq | Numerics | None | |
| gender_googlenet | setup | None | |
| googlenet-12 | compilation | None | |
| googlenet-12-int8 | compilation | None | |
| googlenet-12-qdq | PASS | None | |
| googlenet-3 | compilation | None | |
| googlenet-6 | compilation | None | |
| googlenet-7 | compilation | None | |
| googlenet-8 | compilation | None | |
| googlenet-9 | compilation | None | |
| inception-v1-12 | compilation | None | |
| inception-v1-12-int8 | compilation | None | |
| inception-v1-12-qdq | compilation | None | |
| inception-v1-3 | import_model | None | |
| inception-v1-6 | import_model | None | |
| inception-v1-7 | compilation | None | |
| inception-v1-8 | compilation | None | |
| inception-v1-9 | compilation | None | |
| inception-v2-3 | import_model | None | |
| inception-v2-6 | import_model | None | |
| inception-v2-7 | compilation | None | |
| inception-v2-8 | compilation | None | |
| inception-v2-9 | compilation | None | |
| mnist-1 | import_model | None | |
| mnist-12 | PASS | None | |
| mnist-12-int8 | compilation | None | |
| mnist-7 | PASS | None | |
| mnist-8 | PASS | None | |
| mobilenetv2-10 | compilation | None | |
| mobilenetv2-12 | compilation | None | |
| mobilenetv2-12-int8 | compilation | None | |
| mobilenetv2-12-qdq | Numerics | None | |
| mobilenetv2-7 | compilation | None | |
| mosaic-8 | setup | None | |
| mosaic-9 | compilation | None | |
| pointilism-8 | setup | None | |
| pointilism-9 | compilation | None | |
| rain-princess-8 | setup | None | |
| rain-princess-9 | compilation | None | |
| rcnn-ilsvrc13-3 | import_model | None | |
| rcnn-ilsvrc13-6 | import_model | None | |
| rcnn-ilsvrc13-7 | PASS | None | |
| rcnn-ilsvrc13-8 | PASS | None | |
| rcnn-ilsvrc13-9 | PASS | None | |
| resnet-preproc-v1-18 | import_model | None | |
| resnet101-v1-7 | compilation | None | |
| resnet101-v2-7 | compilation | None | |
| resnet152-v1-7 | compilation | None | |
| resnet152-v2-7 | compilation | None | |
| resnet18-v1-7 | PASS | None | |
| resnet18-v2-7 | PASS | None | |
| resnet34-v1-7 | PASS | None | |
| resnet34-v2-7 | PASS | None | |
| resnet50-caffe2-v1-3 | import_model | None | |
| resnet50-caffe2-v1-6 | import_model | None | |
| resnet50-caffe2-v1-7 | compilation | None | |
| resnet50-caffe2-v1-8 | compilation | None | |
| resnet50-caffe2-v1-9 | compilation | None | |
| resnet50-v1-12 | compilation | None | |
| resnet50-v1-12-int8 | compilation | None | |
| resnet50-v1-12-qdq | PASS | None | |
| resnet50-v1-7 | compilation | None | |
| resnet50-v2-7 | compilation | None | |
| retinanet-9 | compilation | None | |
| shufflenet-3 | import_model | None | |
| shufflenet-6 | import_model | None | |
| shufflenet-7 | PASS | None | |
| shufflenet-8 | PASS | None | |
| shufflenet-9 | PASS | None | |
| shufflenet-v2-10 | compilation | None | |
| shufflenet-v2-12 | compilation | None | |
| shufflenet-v2-12-int8 | compilation | None | |
| shufflenet-v2-12-qdq | Numerics | None | |
| squeezenet1.0-12 | compilation | None | |
| squeezenet1.0-12-int8 | compilation | None | |
| squeezenet1.0-13-qdq | compilation | None | |
| squeezenet1.0-3 | import_model | None | |
| squeezenet1.0-6 | import_model | None | |
| squeezenet1.0-7 | compilation | None | |
| squeezenet1.0-8 | compilation | None | |
| squeezenet1.0-9 | compilation | None | |
| squeezenet1.1-7 | compilation | None | |
| ssd-10 | compilation | None | |
| ssd-12 | compilation | None | |
| ssd-12-int8 | compilation | None | |
| ssd-12-qdq | compilation | None | |
| ssd_mobilenet_v1_10 | compilation | None | |
| ssd_mobilenet_v1_12 | compilation | None | |
| ssd_mobilenet_v1_12-int8 | compilation | None | |
| ssd_mobilenet_v1_13-qdq | compilation | None | |
| super-resolution-10 | compilation | None | |
| tiny-yolov3-11 | compilation | None | |
| tinyyolov2-7 | compilation | None | |
| tinyyolov2-8 | compilation | None | |
| udnie-8 | setup | None | |
| udnie-9 | compilation | None | |
| version-RFB-320 | compilation | None | |
| version-RFB-320-int8 | compilation | None | |
| version-RFB-640 | compilation | None | |
| vgg16-12 | PASS | None | |
| vgg16-12-int8 | compilation | None | |
| vgg16-12-qdq | Numerics | None | |
| vgg16-7 | PASS | None | |
| vgg16-bn-7 | import_model | None | |
| vgg19-7 | PASS | None | |
| vgg19-bn-7 | import_model | None | |
| vgg19-caffe2-3 | import_model | None | |
| vgg19-caffe2-6 | import_model | None | |
| vgg19-caffe2-7 | PASS | None | |
| vgg19-caffe2-8 | PASS | None | |
| vgg19-caffe2-9 | PASS | None | |
| vgg_ilsvrc_16_age_chalearn_iccv2015 | setup | None | |
| vgg_ilsvrc_16_age_imdb_wiki | setup | None | |
| vgg_ilsvrc_16_gender_imdb_wiki | setup | None | |
| yolov2-coco-9 | compilation | None | |
| yolov3-10 | compilation | None | |
| yolov3-12 | compilation | None | |
| yolov3-12-int8 | compilation | None | |
| yolov4 | compilation | None | |
| zfnet512-12 | PASS | None | |
| zfnet512-12-int8 | compilation | None | |
| zfnet512-12-qdq | PASS | None | |
| zfnet512-3 | import_model | None | |
| zfnet512-6 | import_model | None | |
| zfnet512-7 | PASS | None | |
| zfnet512-8 | PASS | None | |
| zfnet512-9 | PASS | None | |
