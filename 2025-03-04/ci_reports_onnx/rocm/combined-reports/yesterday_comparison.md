# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|106.3412|107.2191|0.878|0.83%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|108.5294|106.543|-1.9864|-1.83%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|457.2176|457.6476|0.43|0.09%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|60.403|58.6032|-1.7998|-2.98%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|61.2937|61.1748|-0.1189|-0.19%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|240.4375|239.5177|-0.9198|-0.38%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|34.958|34.2955|-0.6624|-1.89%|
|migraphx_agentmodel__AgentModel|Numerics|within tol|2.0115|2.0046|-0.0069|-0.34%|
|migraphx_bert__bert-large-uncased|PASS|within tol|18.9101|18.9522|0.0422|0.22%|
|migraphx_cadene__dpn92i1|PASS|progression|5.435|5.0725|-0.3625|-6.67%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|29.2072|29.7329|0.5257|1.8%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|6.2557|6.258|0.0023|0.04%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|29.7693|29.7587|-0.0106|-0.04%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|progression|7.6859|7.0909|-0.5949|-7.74%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|27.0855|26.6342|-0.4513|-1.67%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|4.7717|4.7906|0.0188|0.4%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|43.5737|43.5367|-0.037|-0.08%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|46.5827|45.7986|-0.7841|-1.68%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|17.666|17.274|-0.392|-2.22%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|7.5044|7.8449|0.3405|4.54%|
|migraphx_torchvision__densenet121i32|PASS|within tol|18.051|18.0266|-0.0244|-0.13%|
|migraphx_torchvision__inceptioni1|PASS|within tol|4.9243|4.944|0.0197|0.4%|
|migraphx_torchvision__inceptioni32|PASS|within tol|28.0599|27.9793|-0.0806|-0.29%|
|migraphx_torchvision__resnet50i1|PASS|within tol|3.5795|3.5754|-0.0041|-0.11%|
|migraphx_torchvision__resnet50i64|PASS|within tol|20.6039|20.6119|0.008|0.04%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|32.2984|32.2543|-0.0441|-0.14%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|53.4221|53.2897|-0.1324|-0.25%|
|migx_bench_bert-large-uncased_16_384|PASS|within tol|70.1065|70.0767|-0.0298|-0.04%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.0654|12.2432|0.1779|1.47%|
|migx_bench_bert-large-uncased_1_256|Numerics|within tol|12.3686|12.4259|0.0573|0.46%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.2252|19.3283|0.1031|0.54%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.94|12.8376|-0.1024|-0.79%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|13.3962|13.4938|0.0976|0.73%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|20.7797|20.7778|-0.0019|-0.01%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|65.9812|66.0076|0.0263|0.04%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|98.113|98.1514|0.0384|0.04%|
|migx_bench_bert-large-uncased_32_384|PASS|within tol|138.6301|138.6255|-0.0046|-0.0%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|14.4791|14.5978|0.1187|0.82%|
|migx_bench_bert-large-uncased_4_256|PASS|regression|16.5174|17.6628|1.1454|6.93%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|25.125|24.9928|-0.1322|-0.53%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|18.9481|18.0697|-0.8784|-4.64%|
|migx_bench_bert-large-uncased_8_256|PASS|regression|26.5864|60.7455|34.1591|128.48%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|38.8997|38.8518|-0.0479|-0.12%|

## 16 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|convnext_small.in12k_ft_in1k_384|PASS|Numerics|
|convnextv2_base.fcmae_ft_in1k|PASS|Numerics|
|deit3_large_patch16_384.fb_in1k|PASS|Numerics|
|migx_bench_bert-large-uncased_1_256|PASS|Numerics|
|model--bart-base-few-shot-k-128-finetuned-squad-seed-4--anas-awadalla|PASS|Numerics|
|model--bert-base-NER--dslim|PASS|Numerics|
|model--bert-base-cased-ner-conll2003--kamalkraj|PASS|Numerics|
|model--bert-base-uncased-few-shot-k-1024-finetuned-squad-seed-0--anas-awadalla|PASS|Numerics|
|model--biobert-base-cased-v1.2_ncbi_disease-softmax-labelall-ner--jordyvl|PASS|Numerics|
|model--distilbart-xsum-1-1--sshleifer|PASS|Numerics|
|model--distilbert-base-uncased-finetuned-squad--huggingliang|PASS|Numerics|
|model--marian-finetuned-kde4-en-to-fr--ncduy|PASS|Numerics|
|regnety_640.seer_ft_in1k_vaiq|PASS|Numerics|
|resnest269e|PASS|Numerics|
|vgg16_vaiq|PASS|Numerics|
|xcit_medium_24_p16_384_dist|PASS|Numerics|

## 7 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|deit3_large_patch16_224.fb_in22k_ft_in1k|Numerics|PASS|
|model--XLMRobertaLongForQuestionAnswering-base-squad2-512-4096--sadaqabdo|Numerics|PASS|
|model--bert-finetuned-ner--fancyerii|Numerics|PASS|
|model--lsg-bart-base-4096-booksum--ccdv|Numerics|PASS|
|model--marian-finetuned-kde4-en-to-fr--Thinkcru|Numerics|PASS|
|model--marian-finetuned-kde4-en-to-fr--luhui|Numerics|PASS|
|model--opt-350m--facebook|Numerics|PASS|

