# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|106.9966|109.2027|2.2061|2.06%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|108.3312|110.2992|1.968|1.82%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|458.2663|461.063|2.7968|0.61%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|60.0962|59.754|-0.3421|-0.57%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|61.4061|61.5021|0.096|0.16%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|240.8885|241.5692|0.6807|0.28%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|35.617|33.9886|-1.6283|-4.57%|
|migraphx_agentmodel__AgentModel|Numerics|within tol|2.178|2.1662|-0.0118|-0.54%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.402|18.8855|-0.5165|-2.66%|
|migraphx_cadene__dpn92i1|PASS|within tol|5.0366|5.0892|0.0526|1.05%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|29.2359|29.2181|-0.0178|-0.06%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|6.5973|6.613|0.0157|0.24%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|29.9669|29.803|-0.1639|-0.55%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.1167|7.0822|-0.0345|-0.48%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|26.4311|27.4498|1.0187|3.85%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|4.8247|4.7275|-0.0972|-2.02%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|46.3026|43.6103|-2.6923|-5.81%|
|migraphx_models__whisper-tiny-encoder|Numerics|progression|48.5011|46.0756|-2.4254|-5.0%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|19.031|18.6358|-0.3952|-2.08%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|8.2104|8.3571|0.1466|1.79%|
|migraphx_torchvision__densenet121i32|PASS|within tol|18.1035|18.1152|0.0117|0.06%|
|migraphx_torchvision__inceptioni1|PASS|within tol|4.9123|4.8886|-0.0237|-0.48%|
|migraphx_torchvision__inceptioni32|PASS|within tol|28.11|27.9651|-0.1449|-0.52%|
|migraphx_torchvision__resnet50i1|PASS|within tol|3.5736|3.5536|-0.02|-0.56%|
|migraphx_torchvision__resnet50i64|PASS|within tol|20.7298|20.5909|-0.1389|-0.67%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|32.2106|32.2621|0.0515|0.16%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|53.4772|53.336|-0.1412|-0.26%|
|migx_bench_bert-large-uncased_16_384|PASS|within tol|70.8668|69.7634|-1.1034|-1.56%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.1063|12.243|0.1367|1.13%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.4914|12.4383|-0.0531|-0.42%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.332|19.2602|-0.0718|-0.37%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.8593|13.0848|0.2254|1.75%|
|migx_bench_bert-large-uncased_2_256|PASS|regression|13.7821|23.5943|9.8121|71.19%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|20.6222|20.8726|0.2504|1.21%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|66.0849|65.9678|-0.1171|-0.18%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|97.6741|97.8964|0.2223|0.23%|
|migx_bench_bert-large-uncased_32_384|PASS|within tol|137.4404|137.8711|0.4306|0.31%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|14.436|14.4688|0.0329|0.23%|
|migx_bench_bert-large-uncased_4_256|Numerics|within tol|16.7463|16.4846|-0.2618|-1.56%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|25.1369|25.0458|-0.0911|-0.36%|
|migx_bench_bert-large-uncased_8_128|PASS|progression|32.8056|19.0482|-13.7573|-41.94%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|26.695|26.5329|-0.1622|-0.61%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|38.9152|39.1381|0.2229|0.57%|

## 11 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|maxvit_large_tf_224.in1k|PASS|Numerics|
|migx_bench_bert-large-uncased_4_256|PASS|Numerics|
|model--bart-base-few-shot-k-16-finetuned-squad-seed-4--anas-awadalla|PASS|Numerics|
|model--bert-base-uncased-few-shot-k-64-finetuned-squad-seed-4--anas-awadalla|PASS|Numerics|
|model--bert-finetuned-ner--Laure996|PASS|Numerics|
|model--finetuning-sentiment-model-3000-samples--geniusguy777|PASS|Numerics|
|model--marian-finetuned-kde4-cs2sv--ksaml|PASS|Numerics|
|model--marian-finetuned-kde4-en-to-fr--Abelll|PASS|Numerics|
|model--roberta-base-few-shot-k-128-finetuned-squad-seed-10--anas-awadalla|PASS|Numerics|
|regnety_320.seer|PASS|Numerics|
|tf_efficientnet_l2.ns_jft_in1k_475|PASS|Numerics|

## 38 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|model--Learning-sentiment-analysis-through-imdb-ds--SeNSiTivE|Numerics|PASS|
|model--bert-base-uncased-few-shot-k-64-finetuned-squad-seed-2--anas-awadalla|Numerics|PASS|
|model--bert-finetuned-ner--alwaysgetbetter|Numerics|PASS|
|model--bert-finetuned-ner--amartyobanerjee|Numerics|PASS|
|model--bert-finetuned-ner--bbbbearczx|Numerics|PASS|
|model--bert-finetuned-ner--huggingface-course|Numerics|PASS|
|model--bert-finetuned-ner--jatinshah|Numerics|PASS|
|model--bert-finetuned-ner--jfarmerphd|Numerics|PASS|
|model--bert-finetuned-ner--lddczcn|Numerics|PASS|
|model--bert-finetuned-ner--mldev|Numerics|PASS|
|model--bert-finetuned-ner--phijve|Numerics|PASS|
|model--bert-finetuned-ner--the-bee|Numerics|PASS|
|model--bert-finetuned-squad--Akihiro2|Numerics|PASS|
|model--bert-finetuned-squad--Neulvo|Numerics|PASS|
|model--bert-finetuned-squad--RyanM-R|Numerics|PASS|
|model--bert-finetuned-squad--Shanny|Numerics|PASS|
|model--bert-finetuned-squad--ZoeDuan|Numerics|PASS|
|model--bert-finetuned-squad--andrew234|Numerics|PASS|
|model--bert-finetuned-squad--ihfaudsip|Numerics|PASS|
|model--finetuned_gpt2-medium_sst2_negation0.01--yuhuizhang|Numerics|PASS|
|model--finetuned_gpt2_sst2_negation0.0001_pretrainedTrue--yuhuizhang|Numerics|PASS|
|model--finetuned_gpt2_sst2_negation0.2_pretrainedFalse--yuhuizhang|Numerics|PASS|
|model--finetuned_gpt2_sst2_negation0.8_pretrainedFalse--yuhuizhang|Numerics|PASS|
|model--lsg-bart-base-4096-booksum--ccdv|Numerics|PASS|
|model--m2m100_418M-finetuned-kde4-en-to-pt_BR--danhsf|Numerics|PASS|
|model--marian-finetuned-kde4-en-to-fr--Thinkcru|Numerics|PASS|
|model--marian-finetuned-kde4-en-to-vi--huanvo88|Numerics|PASS|
|model--roberta-base-few-shot-k-128-finetuned-squad-seed-0--anas-awadalla|Numerics|PASS|
|model--roberta-base-few-shot-k-128-finetuned-squad-seed-42--anas-awadalla|Numerics|PASS|
|model--roberta-base-finetuned-squad-1--huxxx657|Numerics|PASS|
|model--roberta-base-squad2-nq--nlpconnect|Numerics|PASS|
|model--roberta-l-squadv1.1--vuiseng9|Numerics|PASS|
|model--roberta-large-few-shot-k-16-finetuned-squad-seed-2--anas-awadalla|Numerics|PASS|
|model--roberta-large_ner_conll2003--Gladiator|Numerics|PASS|
|model--roberta_large-unbalanced_simple-ner-conll2003_0908_v0--mariolinml|Numerics|PASS|
|model--tinyroberta-squad2--deepset|Numerics|PASS|
|vit_base_patch16_clip_384.laion2b_ft_in12k_in1k|Numerics|PASS|
|vit_large_patch14_clip_224.openai|Numerics|PASS|

