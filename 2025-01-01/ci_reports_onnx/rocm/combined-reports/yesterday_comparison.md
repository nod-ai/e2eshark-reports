# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|progression|112.0068|99.8141|-12.1927|-10.89%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|99.2046|99.8945|0.6899|0.7%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|501.0277|502.3136|1.286|0.26%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|53.1468|53.4911|0.3443|0.65%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|61.206|61.3001|0.0941|0.15%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|290.4201|290.8684|0.4483|0.15%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|30.6643|31.2296|0.5653|1.84%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.2405|19.2911|0.0506|0.26%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|148.7806|148.3337|-0.4469|-0.3%|
|migraphx_cadene__resnext101_64x4di1|Numerics|within tol|114.3033|114.2806|-0.0227|-0.02%|
|migraphx_cadene__resnext101_64x4di16|Numerics|within tol|363.9565|363.7482|-0.2083|-0.06%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.5596|7.2739|-0.2857|-3.78%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|29.1474|23.9595|-5.188|-17.8%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|34.0421|32.8717|-1.1704|-3.44%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|143.0302|141.9793|-1.0509|-0.73%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|15.7221|16.072|0.35|2.23%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|6.4789|6.7665|0.2876|4.44%|
|migraphx_torchvision__densenet121i32|Numerics|within tol|76.3734|75.3901|-0.9833|-1.29%|
|migraphx_torchvision__inceptioni1|PASS|within tol|39.7514|39.6879|-0.0635|-0.16%|
|migraphx_torchvision__inceptioni32|PASS|progression|121.8651|98.7859|-23.0792|-18.94%|
|migraphx_torchvision__resnet50i1|Numerics|within tol|11.3235|11.3501|0.0267|0.24%|
|migraphx_torchvision__resnet50i64|Numerics|within tol|189.8239|188.9706|-0.8533|-0.45%|
|migx_bench_bert-large-uncased_16_128|PASS|progression|339.502|35.3666|-304.1355|-89.58%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|58.4146|58.399|-0.0156|-0.03%|
|migx_bench_bert-large-uncased_16_384|Numerics|progression|218.4441|79.2487|-139.1954|-63.72%|
|migx_bench_bert-large-uncased_1_128|PASS|progression|36.695|13.0357|-23.6593|-64.48%|
|migx_bench_bert-large-uncased_1_256|PASS|progression|40.047|13.3308|-26.7162|-66.71%|
|migx_bench_bert-large-uncased_1_384|PASS|progression|30.4523|19.4766|-10.9757|-36.04%|
|migx_bench_bert-large-uncased_2_128|PASS|progression|15.7401|12.6578|-3.0823|-19.58%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|13.2494|13.2017|-0.0477|-0.36%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|21.6974|21.7054|0.008|0.04%|
|migx_bench_bert-large-uncased_32_128|PASS|progression|142.0646|70.8152|-71.2494|-50.15%|
|migx_bench_bert-large-uncased_32_256|PASS|progression|239.1404|113.2891|-125.8513|-52.63%|
|migx_bench_bert-large-uncased_32_384|Numerics|progression|1203.7946|157.0388|-1046.7558|-86.95%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|29.6461|29.6982|0.0521|0.18%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|43.4493|43.4124|-0.0369|-0.08%|

## One Regression Found:

|model name|old_status|new_status|
|---|---|---|
|levit_192.fb_dist_in1k|Numerics|compilation|

## 87 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|convnext_xlarge.fb_in22k_ft_in1k|compiled_inference|PASS|
|convnext_xlarge.fb_in22k_ft_in1k_384|compilation|PASS|
|convnextv2_atto.fcmae|compilation|PASS|
|convnextv2_atto.fcmae_ft_in1k|compilation|PASS|
|convnextv2_base.fcmae|compilation|PASS|
|convnextv2_base.fcmae_ft_in1k|compilation|PASS|
|convnextv2_base.fcmae_ft_in22k_in1k|compilation|PASS|
|convnextv2_base.fcmae_ft_in22k_in1k_384|compilation|PASS|
|convnextv2_femto.fcmae|compilation|PASS|
|convnextv2_femto.fcmae_ft_in1k|compilation|PASS|
|convnextv2_large.fcmae|compilation|PASS|
|convnextv2_large.fcmae_ft_in1k|compilation|PASS|
|crossvit_tiny_240|compilation|PASS|
|gluon_xception65|Numerics|PASS|
|maxvit_base_tf_224.in1k|compilation|Numerics|
|maxvit_base_tf_384.in1k|compilation|PASS|
|maxvit_base_tf_384.in21k_ft_in1k|compilation|PASS|
|maxvit_base_tf_512.in1k|compilation|PASS|
|maxvit_base_tf_512.in21k_ft_in1k|compilation|PASS|
|maxvit_large_tf_224.in1k|compilation|Numerics|
|migraphx_cadene__dpn92i1|compilation|Numerics|
|migx_bench_bert-large-uncased_4_128|compilation|PASS|
|migx_bench_bert-large-uncased_4_256|compilation|PASS|
|migx_bench_bert-large-uncased_4_384|compilation|PASS|
|migx_bench_bert-large-uncased_8_128|compilation|PASS|
|model--bart-base-booksum--KamilAin|compilation|PASS|
|model--bart-base-cnn--ainize|compilation|PASS|
|model--bart-base-few-shot-k-1024-finetuned-squad-seed-2--anas-awadalla|compilation|PASS|
|model--bart-base-few-shot-k-1024-finetuned-squad-seed-4--anas-awadalla|compilation|PASS|
|model--bart-base-few-shot-k-128-finetuned-squad-seed-2--anas-awadalla|compilation|PASS|
|model--bart-base-few-shot-k-128-finetuned-squad-seed-4--anas-awadalla|compilation|PASS|
|model--bart-base-few-shot-k-16-finetuned-squad-seed-0--anas-awadalla|compilation|PASS|
|model--bart-base-few-shot-k-16-finetuned-squad-seed-2--anas-awadalla|compilation|PASS|
|model--bart-base-few-shot-k-16-finetuned-squad-seed-4--anas-awadalla|compilation|PASS|
|model--bert-large-uncased-whole-word-masking-finetuned-squad-finetuned-squad--badokorach|compiled_inference|PASS|
|model--bert-large-uncased-whole-word-masking-squad--angelogonzales|compilation|PASS|
|model--bert-large-uncased-whole-word-masking-squad2--deepset|compilation|PASS|
|model--bert-large-uncased_ner_conll2003--Gladiator|compilation|PASS|
|model--bert-medium-pretrained-finetuned-squad--anas-awadalla|compilation|PASS|
|model--bert-medium-squad2-distilled--deepset|compilation|PASS|
|model--bert-mini-finetuned-squad--anas-awadalla|compilation|PASS|
|model--bert-qa-en--srcocotero|compilation|PASS|
|model--biobert-base-cased-v1.2-bc2gm-ner--chintagunta85|compilation|PASS|
|model--lsg-bart-base-4096-booksum--ccdv|compilation|PASS|
|model--ltgbert-qa--amroadel1|compilation|PASS|
|model--m2m100_418M-finetuned-kde4-en-to-pt_BR--danhsf|compilation|PASS|
|tf_efficientnet_l2.ns_jft_in1k|compilation|Numerics|
|tf_efficientnet_l2.ns_jft_in1k_475|compilation|Numerics|
|tf_efficientnetv2_b3.in1k_vaiq|compilation|PASS|
|tf_efficientnetv2_b3.in21k_ft_in1k_train_vaiq|compilation|PASS|
|tf_efficientnetv2_b3.in21k_ft_in1k_vaiq|compilation|PASS|
|tf_efficientnetv2_l.in1k|compilation|PASS|
|tf_efficientnetv2_l.in21k_ft_in1k|compilation|PASS|
|tf_efficientnetv2_m.in1k|compilation|Numerics|
|tf_efficientnetv2_m.in21k_ft_in1k|compilation|Numerics|
|tf_inception_v3_vaiq|compilation|PASS|
|tf_mixnet_l.in1k|compilation|Numerics|
|tf_mixnet_m.in1k|compilation|Numerics|
|tf_mobilenetv3_large_minimal_100.in1k_vaiq|compilation|PASS|
|tf_mobilenetv3_small_075.in1k_vaiq|compilation|PASS|
|tf_mobilenetv3_small_100.in1k_vaiq|compilation|Numerics|
|tf_mobilenetv3_small_minimal_100.in1k_vaiq|compilation|PASS|
|tinynet_a.in1k_vaiq|compilation|Numerics|
|tinynet_d.in1k_vaiq|compilation|Numerics|
|tv_densenet121_vaiq|compilation|PASS|
|tv_resnet101_vaiq|compilation|PASS|
|tv_resnet152_vaiq|compilation|PASS|
|tv_resnet34_vaiq|compilation|PASS|
|tv_resnet50_vaiq|compilation|PASS|
|tv_resnext50_32x4d_vaiq|compilation|PASS|
|vgg11_bn_vaiq|compilation|PASS|
|vgg11_vaiq|compilation|PASS|
|vgg13_bn_vaiq|compilation|PASS|
|vgg13_vaiq|compilation|PASS|
|vgg16_bn_vaiq|compilation|PASS|
|vgg16_vaiq|compilation|PASS|
|vgg19_bn_vaiq|compilation|PASS|
|vgg19_vaiq|compilation|PASS|
|wide_resnet101_2_vaiq|compilation|PASS|
|wide_resnet50_2_test_vaiq|compilation|PASS|
|wide_resnet50_2_vaiq|compilation|PASS|
|xception41_vaiq|compilation|PASS|
|xception41p_vaiq|compilation|PASS|
|xception65_vaiq|compilation|PASS|
|xception65p_vaiq|compilation|PASS|
|xception71_vaiq|compilation|Numerics|
|xception_vaiq|compilation|PASS|

