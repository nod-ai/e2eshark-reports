# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|regression|99.643|112.0068|12.3638|12.41%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|99.6125|99.2046|-0.4079|-0.41%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|502.19|501.0277|-1.1624|-0.23%|
|migraphx_ORT__distilgpt2_1|PASS|progression|103.5463|53.1468|-50.3995|-48.67%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|progression|118.2462|61.206|-57.0402|-48.24%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|292.5433|290.4201|-2.1232|-0.73%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|progression|50.2019|30.6643|-19.5376|-38.92%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.2848|19.2405|-0.0442|-0.23%|
|migraphx_cadene__inceptionv4i16|PASS|progression|244.144|148.7806|-95.3634|-39.06%|
|migraphx_cadene__resnext101_64x4di1|Numerics|within tol|114.2628|114.3033|0.0405|0.04%|
|migraphx_cadene__resnext101_64x4di16|Numerics|within tol|363.9049|363.9565|0.0516|0.01%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.611|7.5596|-0.0514|-0.67%|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|24.8711|29.1474|4.2763|17.19%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|33.6606|34.0421|0.3815|1.13%|
|migraphx_models__whisper-tiny-encoder|Numerics|progression|167.3374|143.0302|-24.3072|-14.53%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|15.9355|15.7221|-0.2134|-1.34%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|5.7053|6.4789|0.7736|13.56%|
|migraphx_torchvision__densenet121i32|Numerics|within tol|75.2678|76.3734|1.1056|1.47%|
|migraphx_torchvision__inceptioni1|PASS|within tol|39.9944|39.7514|-0.243|-0.61%|
|migraphx_torchvision__inceptioni32|PASS|within tol|127.2838|121.8651|-5.4187|-4.26%|
|migraphx_torchvision__resnet50i1|Numerics|within tol|11.3291|11.3235|-0.0056|-0.05%|
|migraphx_torchvision__resnet50i64|Numerics|within tol|188.7122|189.8239|1.1117|0.59%|
|migx_bench_bert-large-uncased_16_128|PASS|regression|35.4095|339.502|304.0925|858.79%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|58.4043|58.4146|0.0103|0.02%|
|migx_bench_bert-large-uncased_16_384|Numerics|regression|85.322|218.4441|133.1221|156.02%|
|migx_bench_bert-large-uncased_1_128|PASS|regression|13.0792|36.695|23.6158|180.56%|
|migx_bench_bert-large-uncased_1_256|PASS|regression|13.3365|40.047|26.7105|200.28%|
|migx_bench_bert-large-uncased_1_384|PASS|regression|19.4048|30.4523|11.0475|56.93%|
|migx_bench_bert-large-uncased_2_128|PASS|regression|12.6166|15.7401|3.1235|24.76%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|13.2225|13.2494|0.0269|0.2%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|21.6712|21.6974|0.0262|0.12%|
|migx_bench_bert-large-uncased_32_128|PASS|regression|70.8529|142.0646|71.2117|100.51%|
|migx_bench_bert-large-uncased_32_256|PASS|regression|111.0345|239.1404|128.1059|115.37%|
|migx_bench_bert-large-uncased_32_384|Numerics|regression|159.1778|1203.7946|1044.6167|656.26%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|29.7208|29.6461|-0.0748|-0.25%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|43.4407|43.4493|0.0086|0.02%|

## 87 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|convnext_xlarge.fb_in22k_ft_in1k|PASS|compiled_inference|
|convnext_xlarge.fb_in22k_ft_in1k_384|PASS|compilation|
|convnextv2_atto.fcmae|PASS|compilation|
|convnextv2_atto.fcmae_ft_in1k|PASS|compilation|
|convnextv2_base.fcmae|PASS|compilation|
|convnextv2_base.fcmae_ft_in1k|PASS|compilation|
|convnextv2_base.fcmae_ft_in22k_in1k|PASS|compilation|
|convnextv2_base.fcmae_ft_in22k_in1k_384|PASS|compilation|
|convnextv2_femto.fcmae|PASS|compilation|
|convnextv2_femto.fcmae_ft_in1k|PASS|compilation|
|convnextv2_large.fcmae|PASS|compilation|
|convnextv2_large.fcmae_ft_in1k|PASS|compilation|
|crossvit_tiny_240|PASS|compilation|
|gluon_xception65|PASS|Numerics|
|maxvit_base_tf_224.in1k|Numerics|compilation|
|maxvit_base_tf_384.in1k|PASS|compilation|
|maxvit_base_tf_384.in21k_ft_in1k|PASS|compilation|
|maxvit_base_tf_512.in1k|PASS|compilation|
|maxvit_base_tf_512.in21k_ft_in1k|PASS|compilation|
|maxvit_large_tf_224.in1k|Numerics|compilation|
|migraphx_cadene__dpn92i1|Numerics|compilation|
|migx_bench_bert-large-uncased_4_128|PASS|compilation|
|migx_bench_bert-large-uncased_4_256|PASS|compilation|
|migx_bench_bert-large-uncased_4_384|PASS|compilation|
|migx_bench_bert-large-uncased_8_128|PASS|compilation|
|model--bart-base-booksum--KamilAin|PASS|compilation|
|model--bart-base-cnn--ainize|PASS|compilation|
|model--bart-base-few-shot-k-1024-finetuned-squad-seed-2--anas-awadalla|PASS|compilation|
|model--bart-base-few-shot-k-1024-finetuned-squad-seed-4--anas-awadalla|PASS|compilation|
|model--bart-base-few-shot-k-128-finetuned-squad-seed-2--anas-awadalla|PASS|compilation|
|model--bart-base-few-shot-k-128-finetuned-squad-seed-4--anas-awadalla|PASS|compilation|
|model--bart-base-few-shot-k-16-finetuned-squad-seed-0--anas-awadalla|PASS|compilation|
|model--bart-base-few-shot-k-16-finetuned-squad-seed-2--anas-awadalla|PASS|compilation|
|model--bart-base-few-shot-k-16-finetuned-squad-seed-4--anas-awadalla|PASS|compilation|
|model--bert-large-uncased-whole-word-masking-finetuned-squad-finetuned-squad--badokorach|PASS|compiled_inference|
|model--bert-large-uncased-whole-word-masking-squad--angelogonzales|PASS|compilation|
|model--bert-large-uncased-whole-word-masking-squad2--deepset|PASS|compilation|
|model--bert-large-uncased_ner_conll2003--Gladiator|PASS|compilation|
|model--bert-medium-pretrained-finetuned-squad--anas-awadalla|PASS|compilation|
|model--bert-medium-squad2-distilled--deepset|PASS|compilation|
|model--bert-mini-finetuned-squad--anas-awadalla|PASS|compilation|
|model--bert-qa-en--srcocotero|PASS|compilation|
|model--biobert-base-cased-v1.2-bc2gm-ner--chintagunta85|PASS|compilation|
|model--lsg-bart-base-4096-booksum--ccdv|PASS|compilation|
|model--ltgbert-qa--amroadel1|PASS|compilation|
|model--m2m100_418M-finetuned-kde4-en-to-pt_BR--danhsf|PASS|compilation|
|tf_efficientnet_l2.ns_jft_in1k|Numerics|compilation|
|tf_efficientnet_l2.ns_jft_in1k_475|Numerics|compilation|
|tf_efficientnetv2_b3.in1k_vaiq|PASS|compilation|
|tf_efficientnetv2_b3.in21k_ft_in1k_train_vaiq|PASS|compilation|
|tf_efficientnetv2_b3.in21k_ft_in1k_vaiq|PASS|compilation|
|tf_efficientnetv2_l.in1k|PASS|compilation|
|tf_efficientnetv2_l.in21k_ft_in1k|PASS|compilation|
|tf_efficientnetv2_m.in1k|Numerics|compilation|
|tf_efficientnetv2_m.in21k_ft_in1k|Numerics|compilation|
|tf_inception_v3_vaiq|PASS|compilation|
|tf_mixnet_l.in1k|Numerics|compilation|
|tf_mixnet_m.in1k|Numerics|compilation|
|tf_mobilenetv3_large_minimal_100.in1k_vaiq|PASS|compilation|
|tf_mobilenetv3_small_075.in1k_vaiq|PASS|compilation|
|tf_mobilenetv3_small_100.in1k_vaiq|Numerics|compilation|
|tf_mobilenetv3_small_minimal_100.in1k_vaiq|PASS|compilation|
|tinynet_a.in1k_vaiq|Numerics|compilation|
|tinynet_d.in1k_vaiq|Numerics|compilation|
|tv_densenet121_vaiq|PASS|compilation|
|tv_resnet101_vaiq|PASS|compilation|
|tv_resnet152_vaiq|PASS|compilation|
|tv_resnet34_vaiq|PASS|compilation|
|tv_resnet50_vaiq|PASS|compilation|
|tv_resnext50_32x4d_vaiq|PASS|compilation|
|vgg11_bn_vaiq|PASS|compilation|
|vgg11_vaiq|PASS|compilation|
|vgg13_bn_vaiq|PASS|compilation|
|vgg13_vaiq|PASS|compilation|
|vgg16_bn_vaiq|PASS|compilation|
|vgg16_vaiq|PASS|compilation|
|vgg19_bn_vaiq|PASS|compilation|
|vgg19_vaiq|PASS|compilation|
|wide_resnet101_2_vaiq|PASS|compilation|
|wide_resnet50_2_test_vaiq|PASS|compilation|
|wide_resnet50_2_vaiq|PASS|compilation|
|xception41_vaiq|PASS|compilation|
|xception41p_vaiq|PASS|compilation|
|xception65_vaiq|PASS|compilation|
|xception65p_vaiq|PASS|compilation|
|xception71_vaiq|Numerics|compilation|
|xception_vaiq|PASS|compilation|

## No Progressions Found

