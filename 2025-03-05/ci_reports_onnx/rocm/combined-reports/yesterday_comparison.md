# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|107.2191|107.631|0.4118|0.38%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|106.543|106.738|0.195|0.18%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|457.6476|457.5128|-0.1348|-0.03%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|58.6032|59.972|1.3688|2.34%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|61.1748|61.1253|-0.0494|-0.08%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|239.5177|241.2926|1.7749|0.74%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|34.2955|34.2669|-0.0286|-0.08%|
|migraphx_agentmodel__AgentModel|Numerics|regression|2.0046|2.145|0.1404|7.0%|
|migraphx_bert__bert-large-uncased|PASS|within tol|18.9522|18.9668|0.0146|0.08%|
|migraphx_cadene__dpn92i1|PASS|within tol|5.0725|5.0482|-0.0243|-0.48%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|29.7329|29.237|-0.4958|-1.67%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|6.258|6.2345|-0.0235|-0.38%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|29.7587|29.7414|-0.0173|-0.06%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.0909|7.0276|-0.0633|-0.89%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|26.6342|26.7699|0.1357|0.51%|
|migraphx_mlperf__resnet50_v1|PASS|regression|4.7906|5.058|0.2674|5.58%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|43.5367|44.3993|0.8626|1.98%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|45.7986|46.3865|0.5879|1.28%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|17.274|16.2004|-1.0736|-6.22%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|7.8449|7.1149|-0.73|-9.31%|
|migraphx_torchvision__densenet121i32|PASS|within tol|18.0266|18.0834|0.0568|0.32%|
|migraphx_torchvision__inceptioni1|PASS|within tol|4.944|4.922|-0.0221|-0.45%|
|migraphx_torchvision__inceptioni32|PASS|within tol|27.9793|28.0209|0.0416|0.15%|
|migraphx_torchvision__resnet50i1|PASS|within tol|3.5754|3.5653|-0.0101|-0.28%|
|migraphx_torchvision__resnet50i64|PASS|within tol|20.6119|20.6315|0.0196|0.1%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|32.2543|32.4628|0.2085|0.65%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|53.2897|53.3028|0.0131|0.02%|
|migx_bench_bert-large-uncased_16_384|PASS|within tol|70.0767|70.2934|0.2166|0.31%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.2432|12.2651|0.0219|0.18%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.4259|12.8087|0.3828|3.08%|
|migx_bench_bert-large-uncased_1_384|PASS|regression|19.3283|45.3848|26.0565|134.81%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.8376|12.815|-0.0226|-0.18%|
|migx_bench_bert-large-uncased_2_256|Numerics|within tol|13.4938|13.4177|-0.076|-0.56%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|20.7778|21.0591|0.2813|1.35%|
|migx_bench_bert-large-uncased_32_128|PASS|progression|66.0076|60.6674|-5.3402|-8.09%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|98.1514|99.5659|1.4144|1.44%|
|migx_bench_bert-large-uncased_32_384|PASS|within tol|138.6255|140.9094|2.284|1.65%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|14.5978|14.4932|-0.1046|-0.72%|
|migx_bench_bert-large-uncased_4_256|PASS|progression|17.6628|16.3726|-1.2902|-7.3%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|24.9928|24.9866|-0.0062|-0.02%|
|migx_bench_bert-large-uncased_8_128|PASS|regression|18.0697|19.1261|1.0564|5.85%|
|migx_bench_bert-large-uncased_8_256|PASS|progression|60.7455|26.8049|-33.9406|-55.87%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|38.8518|39.0981|0.2463|0.63%|

## 13 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|convnext_large_mlp.clip_laion2b_ft_soup_320|PASS|Numerics|
|convnextv2_large.fcmae_ft_in1k|PASS|Numerics|
|maxvit_base_tf_384.in1k|PASS|Numerics|
|migx_bench_bert-large-uncased_2_256|PASS|Numerics|
|model--bart-base-cnn--ainize|PASS|Numerics|
|model--bert-finetuned-ner--Arthuerwang|PASS|Numerics|
|model--bert-finetuned-ner--lddczcn|PASS|Numerics|
|model--distilbert-base-cased-finetuned-ner--swardiantara|PASS|Numerics|
|model--distilbert-base-uncased_mod_squad--damapika|PASS|Numerics|
|model--marian-finetuned-kde4-en-to-fr--Yuch|PASS|Numerics|
|model--roberta-base-finetuned-squad-1--huxxx657|PASS|Numerics|
|regnety_160.sw_in12k|PASS|Numerics|
|xcit_medium_24_p8_384_dist|PASS|Numerics|

## 18 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|convnext_small.in12k_ft_in1k_384|Numerics|PASS|
|convnextv2_base.fcmae_ft_in1k|Numerics|PASS|
|deit3_large_patch16_384.fb_in1k|Numerics|PASS|
|lambda_resnet26t|compilation|PASS|
|lambda_resnet50ts|compilation|PASS|
|migx_bench_bert-large-uncased_1_256|Numerics|PASS|
|model--bart-base-few-shot-k-128-finetuned-squad-seed-4--anas-awadalla|Numerics|PASS|
|model--bert-base-NER--dslim|Numerics|PASS|
|model--bert-base-cased-ner-conll2003--kamalkraj|Numerics|PASS|
|model--bert-base-uncased-few-shot-k-1024-finetuned-squad-seed-0--anas-awadalla|Numerics|PASS|
|model--biobert-base-cased-v1.2_ncbi_disease-softmax-labelall-ner--jordyvl|Numerics|PASS|
|model--distilbart-xsum-1-1--sshleifer|Numerics|PASS|
|model--distilbert-base-uncased-finetuned-squad--huggingliang|Numerics|PASS|
|model--marian-finetuned-kde4-en-to-fr--ncduy|Numerics|PASS|
|regnety_640.seer_ft_in1k_vaiq|Numerics|PASS|
|resnest269e|Numerics|PASS|
|vgg16_vaiq|Numerics|PASS|
|xcit_medium_24_p16_384_dist|Numerics|PASS|

