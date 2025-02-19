# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|122.9443|121.0474|-1.897|-1.54%|
|migraphx_ORT__bert_base_uncased_1|PASS|regression|127.6414|134.644|7.0026|5.49%|
|migraphx_ORT__bert_large_uncased_1|PASS|regression|509.3315|550.8144|41.4829|8.14%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|68.8886|71.8091|2.9205|4.24%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|progression|402.3363|65.3546|-336.9817|-83.76%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|267.1329|273.3941|6.2612|2.34%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|regression|41.9841|180.9054|138.9213|330.89%|
|migraphx_agentmodel__AgentModel|Numerics|progression|2.448|2.1414|-0.3065|-12.52%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.1756|19.3168|0.1412|0.74%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.2355|7.4108|0.1752|2.42%|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|32.1273|41.6911|9.5638|29.77%|
|migraphx_mlperf__resnet50_v1|PASS|regression|4.8917|6.2484|1.3568|27.74%|
|migraphx_models__whisper-tiny-decoder|PASS|regression|44.4255|47.9997|3.5742|8.05%|
|migraphx_models__whisper-tiny-encoder|Numerics|progression|64.6327|54.2057|-10.4271|-16.13%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|17.8135|19.3198|1.5063|8.46%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|9.2407|11.3277|2.087|22.59%|
|migraphx_torchvision__inceptioni1|PASS|within tol|5.3246|5.5168|0.1922|3.61%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|31.9689|33.3786|1.4097|4.41%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|53.8549|55.3859|1.531|2.84%|
|migx_bench_bert-large-uncased_16_384|Numerics|regression|70.6108|74.7985|4.1877|5.93%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.538|13.0085|0.4705|3.75%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|13.3039|12.99|-0.3139|-2.36%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|20.3178|20.4174|0.0996|0.49%|
|migx_bench_bert-large-uncased_2_128|Numerics|regression|13.7248|25.8245|12.0997|88.16%|
|migx_bench_bert-large-uncased_2_256|Numerics|regression|13.5119|73.2962|59.7843|442.46%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|21.4241|21.5649|0.1409|0.66%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|66.9351|68.3544|1.4193|2.12%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|100.0564|102.7338|2.6775|2.68%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|140.1746|145.1572|4.9827|3.55%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|15.8082|15.1894|-0.6189|-3.91%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|17.2617|17.7176|0.456|2.64%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|26.5925|27.4955|0.903|3.4%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.2124|19.8128|-0.3997|-1.98%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|27.4136|27.5062|0.0926|0.34%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|40.4135|41.9192|1.5057|3.73%|

## 33 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|flexivit_base.1200ep_in1k|PASS|Numerics|
|maxvit_rmlp_base_rw_384.sw_in12k_ft_in1k|PASS|Numerics|
|maxvit_small_tf_384.in1k|PASS|Numerics|
|migx_bench_bert-large-uncased_2_128|PASS|Numerics|
|migx_bench_bert-large-uncased_2_256|PASS|Numerics|
|model--CodeGen-350M-Multi--xhyi|PASS|Numerics|
|model--bart-base-few-shot-k-64-finetuned-squad-seed-0--anas-awadalla|PASS|Numerics|
|model--bert-base-finetuned-nli--Jihyun22|PASS|Numerics|
|model--bert-base-multilingual-cased-finetuned-squad--JensH|PASS|compiled_inference|
|model--bert-base-multilingual-cased-finetuned-squad-finetuned-squad--JensH|PASS|compiled_inference|
|model--bert-base-uncased-few-shot-k-512-finetuned-squad-seed-0--anas-awadalla|PASS|Numerics|
|model--bert-base-uncased-finetuned-squad_v2--seviladiguzel|PASS|Numerics|
|model--bert-base-uncased-squad2--deepset|PASS|Numerics|
|model--bert-finetuned-ner--AIventurer|PASS|Numerics|
|model--bert-finetuned-ner--abx|PASS|Numerics|
|model--bert-finetuned-ner--alwaysgetbetter|PASS|Numerics|
|model--bert-finetuned-ner--batya66|PASS|Numerics|
|model--distilbert-base-cased-finetuned-conll03-english--elastic|PASS|Numerics|
|model--distilbert-base-uncased-finetuned-squad--FabianWillner|PASS|Numerics|
|model--distilbert-base-uncased-finetuned-squad--huggingliang|PASS|Numerics|
|model--distilroberta-base-ner-conll2003--philschmid|PASS|Numerics|
|model--finetuned-base_base--muhtasham|PASS|Numerics|
|model--finetuned-opt-squad-dataset--choohan|PASS|Numerics|
|model--finetuned-sentiment-analysis-model--federicopascual|PASS|Numerics|
|model--finetuned_distilgpt2_sst2_negation0.01_pretrainedFalse_epochs10--jhaochenz|PASS|Numerics|
|model--finetuned_gpt2-large_sst2_negation0.0001_pretrainedTrue_epochs1--jhaochenz|PASS|Numerics|
|model--lsg-bart-base-4096-booksum--ccdv|PASS|Numerics|
|model--marian-finetuned-kde4-en-to-fr--bishalbaaniya|PASS|Numerics|
|model--marian-finetuned-kde4-en-to-fr--kbalde|PASS|Numerics|
|model--marian-finetuned-kde4-en-to-fr3--Ghost1|PASS|Numerics|
|model--my_xlm-roberta-large-finetuned-conll03--BahAdoR0101|PASS|Numerics|
|regnety_640.seer|PASS|Numerics|
|vit_base_patch16_224.augreg2_in21k_ft_in1k|PASS|Numerics|

## No Progressions Found

