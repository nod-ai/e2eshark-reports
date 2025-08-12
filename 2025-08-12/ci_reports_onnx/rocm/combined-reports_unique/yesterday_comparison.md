# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|120.5838|116.2805|-4.3033|-3.57%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|118.0341|116.2801|-1.754|-1.49%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|71.7639|70.562|-1.202|-1.67%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|74.7921|75.1433|0.3511|0.47%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|301.0006|300.4348|-0.5658|-0.19%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|45.8405|43.6517|-2.1888|-4.77%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.1133|19.1111|-0.0021|-0.01%|
|migraphx_cadene__dpn92i1|PASS|regression|13.2159|14.9004|1.6845|12.75%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|22.0435|22.362|0.3185|1.44%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|6.6869|6.7288|0.0419|0.63%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.2429|7.5379|0.295|4.07%|
|migraphx_mlperf__bert_large_mlperf|PASS|progression|42.2437|29.0618|-13.1819|-31.2%|
|migraphx_mlperf__resnet50_v1|Numerics|within tol|15.0864|14.7237|-0.3627|-2.4%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|54.3824|45.8449|-8.5375|-15.7%|
|migraphx_models__whisper-tiny-encoder|Numerics|progression|131.3295|112.3389|-18.9905|-14.46%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|17.7065|17.4634|-0.2431|-1.37%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|11.5143|10.1519|-1.3623|-11.83%|
|migraphx_torchvision__densenet121i32|PASS|progression|17.3822|14.9587|-2.4234|-13.94%|
|migraphx_torchvision__inceptioni1|PASS|within tol|4.0686|4.0237|-0.0449|-1.1%|
|migraphx_torchvision__resnet50i1|PASS|regression|2.1765|3.223|1.0464|48.08%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|25.7527|25.8917|0.139|0.54%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|37.9376|37.4655|-0.4721|-1.24%|
|migx_bench_bert-large-uncased_16_384|PASS|within tol|56.2298|55.6736|-0.5563|-0.99%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.5943|12.6054|0.0111|0.09%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.9015|13.1588|0.2573|1.99%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.2193|19.2988|0.0795|0.41%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|13.3663|13.003|-0.3633|-2.72%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|19.2596|19.2088|-0.0508|-0.26%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|19.6128|19.6135|0.0007|0.0%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|36.05|35.8455|-0.2044|-0.57%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|69.3559|68.6902|-0.6657|-0.96%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|109.8054|108.6648|-1.1406|-1.04%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|19.6112|20.2769|0.6657|3.39%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|20.1132|20.0631|-0.0501|-0.25%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|23.2379|23.2566|0.0188|0.08%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.4409|20.1219|-0.319|-1.56%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|26.3262|26.2024|-0.1237|-0.47%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|32.4624|32.2372|-0.2251|-0.69%|

## 7 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|eva_large_patch14_196.in22k_ft_in1k|PASS|Numerics|
|mixer_b16_224.goog_in21k_ft_in1k|PASS|Numerics|
|model--biobert-base-cased-v1.2-bc2gm-ner--chintagunta85|PASS|Numerics|
|model--bsc-bio-ehr-es-cantemist--PlanTL-GOB-ES|PASS|Numerics|
|model--microsoft_deberta-large_squad--Palak|PASS|compiled_inference|
|vit_large_patch16_384.augreg_in21k_ft_in1k|PASS|Numerics|
|vit_relpos_medium_patch16_224.sw_in1k|PASS|Numerics|

## 2 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|deberta_Opset17_transformers|Numerics|PASS|
|migx_bench_bert-large-uncased_32_256|Numerics|PASS|

