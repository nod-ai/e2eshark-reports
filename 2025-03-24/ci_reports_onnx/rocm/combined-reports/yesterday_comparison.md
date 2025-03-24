# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|115.4644|117.2693|1.8049|1.56%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|116.3287|116.4475|0.1189|0.1%|
|migraphx_ORT__bert_large_uncased_1|PASS|progression|773.2034|523.4457|-249.7577|-32.3%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|69.4178|68.1661|-1.2517|-1.8%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|progression|66.9322|63.5595|-3.3727|-5.04%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|329.3035|331.7657|2.4622|0.75%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|33.8792|34.834|0.9547|2.82%|
|migraphx_agentmodel__AgentModel|Numerics|regression|1.5536|1.7838|0.2303|14.82%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.3637|19.7626|0.3989|2.06%|
|migraphx_cadene__dpn92i1|PASS|within tol|5.0592|5.0452|-0.014|-0.28%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|29.2689|29.7778|0.5089|1.74%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|5.9194|5.8986|-0.0208|-0.35%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|29.5886|29.8243|0.2357|0.8%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.1668|7.3677|0.2009|2.8%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|28.0655|26.776|-1.2895|-4.59%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|4.8152|4.7766|-0.0386|-0.8%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|38.3082|39.9726|1.6644|4.34%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|46.3327|48.382|2.0493|4.42%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|17.9767|17.2018|-0.775|-4.31%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|8.1037|6.0581|-2.0457|-25.24%|
|migraphx_torchvision__densenet121i32|PASS|within tol|17.8623|17.8482|-0.0141|-0.08%|
|migraphx_torchvision__inceptioni1|PASS|progression|7.204|4.869|-2.335|-32.41%|
|migraphx_torchvision__inceptioni32|PASS|within tol|27.9652|28.1792|0.214|0.77%|
|migraphx_torchvision__resnet50i1|PASS|progression|4.6945|3.1898|-1.5047|-32.05%|
|migraphx_torchvision__resnet50i64|PASS|within tol|20.5197|20.7608|0.2411|1.17%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|26.9057|27.5105|0.6048|2.25%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|38.5985|39.4089|0.8104|2.1%|
|migx_bench_bert-large-uncased_16_384|PASS|within tol|58.5457|59.4938|0.9482|1.62%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.0593|11.9466|-0.1127|-0.93%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.5977|12.4612|-0.1365|-1.08%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.408|19.4164|0.0084|0.04%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.5882|12.548|-0.0403|-0.32%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|19.5792|19.5009|-0.0783|-0.4%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|20.3661|20.5468|0.1807|0.89%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|37.193|37.8733|0.6803|1.83%|
|migx_bench_bert-large-uncased_32_256|PASS|progression|129.163|79.943|-49.22|-38.11%|
|migx_bench_bert-large-uncased_32_384|PASS|within tol|120.3554|121.8958|1.5403|1.28%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|19.5676|19.4973|-0.0703|-0.36%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|20.4934|20.9746|0.4812|2.35%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|24.0793|24.8369|0.7576|3.15%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.8792|21.0774|0.1982|0.95%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|27.3896|28.1358|0.7462|2.72%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|34.9883|35.6541|0.6658|1.9%|

## No Regressions Found

## 30 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|maxvit_base_tf_512.in21k_ft_in1k|Numerics|PASS|
|model--BERT_summary--Shobhank-iiitdwd|Numerics|PASS|
|model--Jasmine-350M--UBC-NLP|Numerics|PASS|
|model--MEDIA_NLU-flaubert_oral_mixed--vpelloin|Numerics|PASS|
|model--bart-base-few-shot-k-128-finetuned-squad-seed-4--anas-awadalla|Numerics|PASS|
|model--bart-base-few-shot-k-512-finetuned-squad-seed-4--anas-awadalla|Numerics|PASS|
|model--bart-large-cnn-samsum--philschmid|Numerics|PASS|
|model--bart-large-finetuned-squadv1--valhalla|Numerics|PASS|
|model--bert-base-uncased-few-shot-k-128-finetuned-squad-seed-2--anas-awadalla|Numerics|PASS|
|model--bert-finetuned-ner--azuresonance|Numerics|PASS|
|model--bert-finetuned-ner--chandrasutrisnotjhong|Numerics|PASS|
|model--bert-finetuned-ner--yinxiaoz|Numerics|PASS|
|model--bert-finetuned-squad--Lexie79|Numerics|PASS|
|model--bert-finetuned-squad--lewtun|Numerics|PASS|
|model--bert-finetuned-squad--rghosh8|Numerics|PASS|
|model--bert-finetuned-squad--spasis|Numerics|PASS|
|model--bert-finetuned-squad--tmgondal|Numerics|PASS|
|model--bert-qa-en--srcocotero|Numerics|PASS|
|model--biobert-base-cased-v1.2_ncbi_disease-softmax-labelall-ner--jordyvl|Numerics|PASS|
|model--deberta-v3-base-squad2--deepset|Numerics|PASS|
|model--deberta-v3-large-squad2--deepset|Numerics|PASS|
|model--distilbert-base-cased-finetuned-conll03-english--elastic|Numerics|PASS|
|model--finetuned_gpt2-medium_sst2_negation0.0_pretrainedFalse--yuhuizhang|Numerics|PASS|
|model--finetuned_gpt2-medium_sst2_negation0.2_pretrainedFalse--yuhuizhang|Numerics|PASS|
|model--finetuning-sentiment-model-3000-samples--rh-jayson|Numerics|PASS|
|model--m2m100_418M-finetuned-kde4-en-to-pt_BR--danhsf|Numerics|PASS|
|model--xlm-roberta-base-kyrgyzNER--the-cramer-project|Numerics|PASS|
|tf_efficientnet_l2.ns_jft_in1k_475|Numerics|PASS|
|vit_relpos_base_patch16_clsgap_224.sw_in1k|Numerics|PASS|
|xcit_large_24_p8_224_dist|Numerics|PASS|

