# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|109.2027|106.3412|-2.8615|-2.62%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|110.2992|108.5294|-1.7698|-1.6%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|461.063|457.2176|-3.8454|-0.83%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|59.754|60.403|0.6489|1.09%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|61.5021|61.2937|-0.2084|-0.34%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|241.5692|240.4375|-1.1317|-0.47%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|33.9886|34.958|0.9693|2.85%|
|migraphx_agentmodel__AgentModel|Numerics|progression|2.1662|2.0115|-0.1547|-7.14%|
|migraphx_bert__bert-large-uncased|PASS|within tol|18.8855|18.9101|0.0246|0.13%|
|migraphx_cadene__dpn92i1|PASS|regression|5.0892|5.435|0.3458|6.79%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|29.2181|29.2072|-0.0109|-0.04%|
|migraphx_cadene__resnext101_64x4di1|PASS|progression|6.613|6.2557|-0.3573|-5.4%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|29.803|29.7693|-0.0337|-0.11%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|regression|7.0822|7.6859|0.6036|8.52%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|27.4498|27.0855|-0.3643|-1.33%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|4.7275|4.7717|0.0443|0.94%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|43.6103|43.5737|-0.0366|-0.08%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|46.0756|46.5827|0.5071|1.1%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|18.6358|17.666|-0.9698|-5.2%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|8.3571|7.5044|-0.8527|-10.2%|
|migraphx_torchvision__densenet121i32|PASS|within tol|18.1152|18.051|-0.0643|-0.35%|
|migraphx_torchvision__inceptioni1|PASS|within tol|4.8886|4.9243|0.0358|0.73%|
|migraphx_torchvision__inceptioni32|PASS|within tol|27.9651|28.0599|0.0948|0.34%|
|migraphx_torchvision__resnet50i1|PASS|within tol|3.5536|3.5795|0.0259|0.73%|
|migraphx_torchvision__resnet50i64|PASS|within tol|20.5909|20.6039|0.013|0.06%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|32.2621|32.2984|0.0363|0.11%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|53.336|53.4221|0.0861|0.16%|
|migx_bench_bert-large-uncased_16_384|PASS|within tol|69.7634|70.1065|0.3431|0.49%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.243|12.0654|-0.1777|-1.45%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.4383|12.3686|-0.0697|-0.56%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.2602|19.2252|-0.035|-0.18%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|13.0848|12.94|-0.1447|-1.11%|
|migx_bench_bert-large-uncased_2_256|PASS|progression|23.5943|13.3962|-10.1981|-43.22%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|20.8726|20.7797|-0.0929|-0.45%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|65.9678|65.9812|0.0134|0.02%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|97.8964|98.113|0.2166|0.22%|
|migx_bench_bert-large-uncased_32_384|PASS|within tol|137.8711|138.6301|0.759|0.55%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|14.4688|14.4791|0.0103|0.07%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|16.4846|16.5174|0.0328|0.2%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|25.0458|25.125|0.0792|0.32%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|19.0482|18.9481|-0.1001|-0.53%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|26.5329|26.5864|0.0536|0.2%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|39.1381|38.8997|-0.2384|-0.61%|

## 7 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|deit3_large_patch16_224.fb_in22k_ft_in1k|PASS|Numerics|
|model--XLMRobertaLongForQuestionAnswering-base-squad2-512-4096--sadaqabdo|PASS|Numerics|
|model--bert-finetuned-ner--fancyerii|PASS|Numerics|
|model--lsg-bart-base-4096-booksum--ccdv|PASS|Numerics|
|model--marian-finetuned-kde4-en-to-fr--Thinkcru|PASS|Numerics|
|model--marian-finetuned-kde4-en-to-fr--luhui|PASS|Numerics|
|model--opt-350m--facebook|PASS|Numerics|

## 12 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|maxvit_large_tf_224.in1k|Numerics|PASS|
|migx_bench_bert-large-uncased_4_256|Numerics|PASS|
|model--bart-base-few-shot-k-16-finetuned-squad-seed-4--anas-awadalla|Numerics|PASS|
|model--bert-base-uncased-few-shot-k-64-finetuned-squad-seed-4--anas-awadalla|Numerics|PASS|
|model--bert-finetuned-ner--Laure996|Numerics|PASS|
|model--camembert_squadFR_question_answering_tools_fr--AntoineD|Numerics|PASS|
|model--finetuning-sentiment-model-3000-samples--geniusguy777|Numerics|PASS|
|model--marian-finetuned-kde4-cs2sv--ksaml|Numerics|PASS|
|model--marian-finetuned-kde4-en-to-fr--Abelll|Numerics|PASS|
|model--roberta-base-few-shot-k-128-finetuned-squad-seed-10--anas-awadalla|Numerics|PASS|
|regnety_320.seer|Numerics|PASS|
|tf_efficientnet_l2.ns_jft_in1k_475|Numerics|PASS|

