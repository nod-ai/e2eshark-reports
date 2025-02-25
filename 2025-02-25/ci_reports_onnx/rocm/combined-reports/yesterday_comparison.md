# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|progression|119.1593|106.9361|-12.2232|-10.26%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|108.584|107.9591|-0.6249|-0.58%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|464.206|458.7627|-5.4433|-1.17%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|59.3619|59.4951|0.1332|0.22%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|61.2884|61.7969|0.5086|0.83%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|240.009|240.7266|0.7177|0.3%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|35.3545|35.6908|0.3362|0.95%|
|migraphx_agentmodel__AgentModel|Numerics|within tol|1.7219|1.7201|-0.0019|-0.11%|
|migraphx_bert__bert-large-uncased|PASS|within tol|18.9317|19.5617|0.6299|3.33%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.0204|7.0784|0.058|0.83%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|31.3692|28.3782|-2.991|-9.53%|
|migraphx_mlperf__resnet50_v1|PASS|regression|4.8272|5.0961|0.2689|5.57%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|44.3811|43.8178|-0.5633|-1.27%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|45.7584|46.492|0.7336|1.6%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|17.3311|18.2084|0.8773|5.06%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|9.6754|6.0105|-3.6649|-37.88%|
|migraphx_torchvision__inceptioni1|PASS|within tol|4.9087|4.8999|-0.0087|-0.18%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|32.2987|32.3466|0.048|0.15%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|53.5123|53.5609|0.0486|0.09%|
|migx_bench_bert-large-uncased_16_384|PASS|within tol|70.3283|69.0177|-1.3106|-1.86%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.0656|12.1167|0.0511|0.42%|
|migx_bench_bert-large-uncased_1_256|Numerics|regression|12.4153|43.1761|30.7607|247.76%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.2507|19.2727|0.0221|0.11%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.8689|12.8005|-0.0684|-0.53%|
|migx_bench_bert-large-uncased_2_256|PASS|regression|13.5278|295.4942|281.9664|2084.35%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|20.7159|20.8686|0.1527|0.74%|
|migx_bench_bert-large-uncased_32_128|PASS|regression|66.0798|237.7795|171.6997|259.84%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|99.01|98.0254|-0.9846|-0.99%|
|migx_bench_bert-large-uncased_32_384|PASS|within tol|138.8489|138.1536|-0.6953|-0.5%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|14.5552|14.4131|-0.1421|-0.98%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|16.3802|16.5652|0.185|1.13%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|24.9511|25.1823|0.2311|0.93%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|18.8773|19.1242|0.2469|1.31%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|26.678|26.9861|0.3081|1.15%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|38.9209|39.0936|0.1727|0.44%|

## 37 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|deit3_large_patch16_224.fb_in22k_ft_in1k|PASS|Numerics|
|dm_nfnet_f3.dm_in1k|PASS|Numerics|
|flexivit_base.1200ep_in1k|PASS|Numerics|
|flexivit_base.300ep_in1k|PASS|Numerics|
|flexivit_large.600ep_in1k|PASS|Numerics|
|focalnet_base_lrf.ms_in1k|PASS|Numerics|
|gcvit_base|PASS|Numerics|
|maxxvit_rmlp_small_rw_256.sw_in1k|PASS|Numerics|
|migx_bench_bert-large-uncased_1_256|PASS|Numerics|
|mixer_b16_224.goog_in21k_ft_in1k|PASS|Numerics|
|model--NLP_DEEP_2--Bictole|PASS|Numerics|
|model--SENATOR-Scaled--RANG012|PASS|Numerics|
|model--TinyStories-2Layers-33M--roneneldan|PASS|Numerics|
|model--Translation--shed-e|PASS|Numerics|
|model--bart-base-cnn--ainize|PASS|Numerics|
|model--bart-base-few-shot-k-1024-finetuned-squad-seed-2--anas-awadalla|PASS|Numerics|
|model--bart-base-few-shot-k-128-finetuned-squad-seed-2--anas-awadalla|PASS|Numerics|
|model--bart-base-few-shot-k-128-finetuned-squad-seed-4--anas-awadalla|PASS|Numerics|
|model--bart-base-few-shot-k-32-finetuned-squad-seed-4--anas-awadalla|PASS|Numerics|
|model--bart-base-finetuned-squad--huxxx657|PASS|Numerics|
|model--bert-base-uncased-few-shot-k-256-finetuned-squad-seed-10--anas-awadalla|PASS|Numerics|
|model--bert-finetuned-squad--yaozeguo|PASS|Numerics|
|model--bert-l-squadv1.1-sl256--vuiseng9|PASS|Numerics|
|model--bert-large-uncased-whole-word-masking-squad2--deepset|PASS|Numerics|
|model--bert-medium-squad2-distilled--deepset|PASS|Numerics|
|model--distilbert-base-uncased-finetuned-squad--BillZou|PASS|Numerics|
|model--distilbert-base-uncased-finetuned-squad--aaraki|PASS|Numerics|
|model--distilbert-base-uncased-finetuned-squad--laampt|PASS|Numerics|
|model--distilbert-base-uncased-finetuned-squad-colab--Adrian|PASS|Numerics|
|model--hebert-finetuned-hebrew-squad--tdklab|PASS|Numerics|
|model--hebrew_poetry-gpt_neo-small--Norod78|PASS|Numerics|
|model--manifestoberta-xlm-roberta-56policy-topics-sentence-2023-1-1--manifesto-project|PASS|Numerics|
|model--marian-finetuned-kde4-en-to-es--tmobaggins|PASS|Numerics|
|model--marian-finetuned-kde4-en-to-fr--Thinkcru|PASS|Numerics|
|model--medium-mlm-imdb-target-imdb--muhtasham|PASS|Numerics|
|tf_efficientnet_b6.ns_jft_in1k|PASS|Numerics|
|twins_svt_large|PASS|Numerics|

## 7 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|VGG19_vaiq|Numerics|PASS|
|flexivit_base.600ep_in1k|Numerics|PASS|
|migx_bench_bert-large-uncased_16_384|Numerics|PASS|
|model--GPyT--Sentdex|Numerics|PASS|
|model--PT_GPTNEO125_ATG--xhyi|Numerics|PASS|
|model--bert-finetuned-squad--shash2409|Numerics|PASS|
|model--ibert-roberta-base-finetuned-mrpc--VitaliiVrublevskyi|Numerics|PASS|

