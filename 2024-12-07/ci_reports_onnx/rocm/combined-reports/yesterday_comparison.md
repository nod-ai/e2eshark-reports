# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|progression|116.1942|110.3341|-5.8601|-5.04%|
|migraphx_ORT__bert_base_uncased_1|PASS|progression|115.3453|109.0289|-6.3164|-5.48%|
|migraphx_ORT__bert_large_uncased_1|PASS|regression|369.7436|527.2729|157.5293|42.61%|
|migraphx_ORT__distilgpt2_1|PASS|progression|62.9727|58.6337|-4.339|-6.89%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|progression|74.1122|63.7554|-10.3568|-13.97%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|283.2192|276.6352|-6.5839|-2.32%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|progression|40.0109|35.9816|-4.0293|-10.07%|
|migraphx_bert__bert-large-uncased|PASS|within tol|20.0571|20.0839|0.0267|0.13%|
|migraphx_bert__bertsquad-12|PASS|within tol|17.6647|18.4575|0.7928|4.49%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|163.0739|163.7872|0.7133|0.44%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|188.8375|188.8254|-0.012|-0.01%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.7277|7.8489|0.1212|1.57%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|45.0452|44.5105|-0.5347|-1.19%|
|migraphx_mlperf__resnet50_v1|Numerics|within tol|6.587|6.427|-0.16|-2.43%|
|migraphx_models__whisper-tiny-decoder|PASS|regression|31.5313|47.606|16.0747|50.98%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|53.3706|54.7838|1.4132|2.65%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|23.9516|23.2362|-0.7154|-2.99%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|13.3453|15.4767|2.1314|15.97%|
|migraphx_torchvision__densenet121i32|PASS|within tol|73.6333|73.9526|0.3193|0.43%|
|migraphx_torchvision__inceptioni1|PASS|within tol|19.4288|19.3929|-0.0358|-0.18%|
|migraphx_torchvision__inceptioni32|PASS|within tol|140.8481|140.8008|-0.0473|-0.03%|
|migraphx_torchvision__resnet50i64|PASS|within tol|170.3914|170.4804|0.089|0.05%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|35.6536|35.7067|0.0531|0.15%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|61.2431|61.5185|0.2754|0.45%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|77.921|77.9095|-0.0115|-0.01%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|13.5819|13.4577|-0.1242|-0.91%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|13.787|13.8701|0.0831|0.6%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|20.0516|20.0308|-0.0208|-0.1%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|13.3937|13.9848|0.5911|4.41%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|14.1336|14.1306|-0.003|-0.02%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|22.1021|22.1188|0.0168|0.08%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|73.741|73.8425|0.1015|0.14%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|110.7953|111.2732|0.4779|0.43%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|154.524|154.5601|0.0361|0.02%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|15.1215|15.287|0.1655|1.09%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|18.169|18.1033|-0.0657|-0.36%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|27.7197|27.9034|0.1837|0.66%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|21.028|21.0232|-0.0048|-0.02%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|29.5391|29.6121|0.073|0.25%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|43.5331|43.7379|0.2049|0.47%|

## 19 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|migraphx_mlperf__resnet50_v1|PASS|Numerics|
|model--Bartlarge--Shubham09|PASS|Numerics|
|model--M-TurQA-convbert-base-turkish-cased-finetuned-toqad-aug--meetyildiz|PASS|Numerics|
|model--TinyStories-1M--roneneldan|PASS|Numerics|
|model--TinyStories-3M--roneneldan|PASS|Numerics|
|model--TinyStories-8M--roneneldan|PASS|Numerics|
|model--gemma-tiny-random--yujiepan|PASS|Numerics|
|model--ia-detection-tiny-random-gptj--arincon|PASS|Numerics|
|model--my_awesome_gptj_model--anandshende|PASS|Numerics|
|model--qa_tquad_convbert-base-turkish--Izzet|PASS|Numerics|
|model--qa_ytu_convbert-base-turkish--Izzet|PASS|Numerics|
|model--really-tiny-falcon-testing--fxmarty|PASS|Numerics|
|model--tiny-gpt2--taufeeque|PASS|Numerics|
|model--tiny-gpt2-magicprompt--pszemraj|PASS|Numerics|
|model--tiny-random-ConvBertForQuestionAnswering--hf-tiny-model-private|PASS|Numerics|
|model--tiny-random-FalconForCausalLM--illuin|PASS|Numerics|
|model--tiny-random-GPTJForQuestionAnswering--hf-tiny-model-private|PASS|Numerics|
|model--tiny-random-llama--IlyasMoutawwakil|PASS|Numerics|
|model--tiny-testing-falcon-alibi--fxmarty|PASS|Numerics|

## 6 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|resnet50_gn_test_vaiq|compiled_inference|Numerics|
|resnet50_gn_vaiq|compiled_inference|PASS|
|resnetv2_152x2_bit.goog_teacher_in21k_ft_in1k_vaiq|compiled_inference|Numerics|
|resnetv2_50d_gn.ah_in1k_train_vaiq|compiled_inference|PASS|
|resnetv2_50d_gn.ah_in1k_vaiq|compiled_inference|Numerics|
|resnetv2_50x1_bit.goog_distilled_in1k_vaiq|compiled_inference|PASS|

