# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|progression|801.5506|48.2553|-753.2953|-93.98%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|progression|2436.3986|62.0346|-2374.3641|-97.45%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|progression|7094.7893|167.3617|-6927.4276|-97.64%|
|migraphx_cadene__dpn92i1|PASS|progression|463.8861|68.7704|-395.1157|-85.18%|
|migraphx_cadene__inceptionv4i16|PASS|progression|28024.6677|4832.8532|-23191.8145|-82.76%|
|migraphx_cadene__resnext101_64x4di1|PASS|progression|1009.7442|133.513|-876.2312|-86.78%|
|migraphx_cadene__resnext101_64x4di16|PASS|progression|6385.4546|2324.0207|-4061.4339|-63.6%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|progression|5784.2009|182.6701|-5601.5308|-96.84%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|8237.9007|244.8754|-7993.0253|-97.03%|
|migraphx_mlperf__resnet50_v1|PASS|progression|163.9665|28.7621|-135.2043|-82.46%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|263.8879|22.2007|-241.6872|-91.59%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|72.414|43.8919|-28.5221|-39.39%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|26.8739|25.8125|-1.0614|-3.95%|
|migraphx_torchvision__inceptioni1|PASS|progression|614.4001|143.1703|-471.2297|-76.7%|
|migraphx_torchvision__inceptioni32|PASS|progression|23101.6265|4350.0689|-18751.5576|-81.17%|
|migraphx_torchvision__resnet50i1|PASS|progression|259.6859|26.9246|-232.7614|-89.63%|
|migraphx_torchvision__resnet50i64|PASS|progression|10339.7821|1211.0934|-9128.6887|-88.29%|

## 45 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|DenseNet201_vaiq_int8|PASS|Numerics|
|hrnet_w18_small_v2_vaiq|PASS|compilation|
|hrnet_w18_small_vaiq|PASS|compilation|
|hrnet_w18_vaiq|PASS|compilation|
|hrnet_w30_vaiq|PASS|compilation|
|hrnet_w32_vaiq|PASS|compilation|
|hrnet_w40_vaiq|PASS|compilation|
|hrnet_w44_vaiq|PASS|compilation|
|hrnet_w48_vaiq|PASS|compilation|
|hrnet_w64_vaiq|PASS|compilation|
|migraphx_ORT__bert_base_uncased_1|PASS|compiled_inference|
|migraphx_ORT__bert_large_uncased_1|PASS|compiled_inference|
|migraphx_bert__bertsquad-12|Numerics|compilation|
|migraphx_mlperf__bert_large_mlperf|PASS|Numerics|
|model--Electra-Large-SQUADV2--titanbot|Numerics|compiled_inference|
|model--electra-large-synqa--mbartolo|Numerics|compiled_inference|
|model--mobilebert-squadv2--aware-ai|Numerics|compiled_inference|
|model--mobilebert-uncased-finetuned-squadv2--mrm8488|Numerics|compiled_inference|
|model--mobilebert_cola--Alireza1044|Numerics|compiled_inference|
|model--mobilebert_mnli--Alireza1044|Numerics|compiled_inference|
|model--mobilebert_mrpc--Alireza1044|Numerics|compiled_inference|
|model--mobilebert_rte--Alireza1044|Numerics|compiled_inference|
|model--mobilebert_sst2--Alireza1044|Numerics|compiled_inference|
|model--my_awesome_gptj_model--anandshende|Numerics|compiled_inference|
|model--roberta-l-squadv1.1--vuiseng9|Numerics|compiled_inference|
|model--roberta-large-bne-sqac--PlanTL-GOB-ES|Numerics|compiled_inference|
|model--roberta-large-few-shot-k-1024-finetuned-squad-seed-2--anas-awadalla|Numerics|compiled_inference|
|model--roberta-large-few-shot-k-1024-finetuned-squad-seed-4--anas-awadalla|Numerics|compiled_inference|
|model--roberta-large-few-shot-k-128-finetuned-squad-seed-4--anas-awadalla|Numerics|compiled_inference|
|model--roberta-large-few-shot-k-16-finetuned-squad-seed-0--anas-awadalla|Numerics|compiled_inference|
|model--roberta-large-few-shot-k-16-finetuned-squad-seed-2--anas-awadalla|Numerics|compiled_inference|
|model--roberta-large-few-shot-k-64-finetuned-squad-seed-4--anas-awadalla|Numerics|compiled_inference|
|model--roberta-large-finetuned-ner--romainlhardy|Numerics|compiled_inference|
|model--roberta-large-ner-english--Jean-Baptiste|Numerics|compiled_inference|
|model--roberta-large-synqa--mbartolo|Numerics|compiled_inference|
|model--roberta-large-synqa-ext--mbartolo|Numerics|compiled_inference|
|model--roberta-large-tweetner7-all--tner|Numerics|compiled_inference|
|model--roberta-large_ner_conll2003--Gladiator|Numerics|compiled_inference|
|model--roberta-med-small_shared-finetuned-bbc_xsum-summarization--mrm8488|PASS|compiled_inference|
|model--roberta_large-filtered_simple-chunk-conll2003_0907_v1--mariolinml|Numerics|compiled_inference|
|model--roberta_large-ner-conll2003_0818_v0--mariolinml|Numerics|compiled_inference|
|model--roberta_large-unbalanced_simple-ner-conll2003_0908_v0--mariolinml|Numerics|compiled_inference|
|model--tiny-random-GPTJForQuestionAnswering--hf-tiny-model-private|Numerics|compiled_inference|
|model--tiny-random-gptj-for-sequence-classification--ydshieh|Numerics|compiled_inference|
|resnet50_gn_vaiq|PASS|Numerics|

## 159 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|migraphx_torchvision__densenet121i32|compilation|PASS|
|model--BART--Shubham09|compilation|Numerics|
|model--Bartlarge--Shubham09|compiled_inference|Numerics|
|model--CodeGen-350M-Multi--xhyi|preprocessing|compiled_inference|
|model--Microllama_Char_200k_step--Corianas|compiled_inference|PASS|
|model--TinyMistral-248M-v2-cleaner--M4-ai|compiled_inference|PASS|
|model--TinyStories-2Layers-33M--roneneldan|compiled_inference|PASS|
|model--TinyStories-8M--roneneldan|compiled_inference|PASS|
|model--Translation--shed-e|compiled_inference|PASS|
|model--bart-CaPE-xsum--praf-choub|compiled_inference|Numerics|
|model--bart-base-booksum--KamilAin|compiled_inference|PASS|
|model--bart-base-cnn--ainize|compiled_inference|PASS|
|model--bart-base-few-shot-k-1024-finetuned-squad-seed-2--anas-awadalla|compiled_inference|PASS|
|model--bart-base-few-shot-k-1024-finetuned-squad-seed-4--anas-awadalla|compiled_inference|PASS|
|model--bart-base-few-shot-k-128-finetuned-squad-seed-2--anas-awadalla|compiled_inference|PASS|
|model--bart-base-few-shot-k-128-finetuned-squad-seed-4--anas-awadalla|compiled_inference|PASS|
|model--bart-base-few-shot-k-16-finetuned-squad-seed-0--anas-awadalla|compiled_inference|PASS|
|model--bart-base-few-shot-k-16-finetuned-squad-seed-2--anas-awadalla|compiled_inference|PASS|
|model--bart-base-few-shot-k-16-finetuned-squad-seed-4--anas-awadalla|compiled_inference|PASS|
|model--bart-base-few-shot-k-256-finetuned-squad-seed-0--anas-awadalla|compiled_inference|PASS|
|model--bart-base-few-shot-k-256-finetuned-squad-seed-4--anas-awadalla|compiled_inference|PASS|
|model--bart-base-few-shot-k-32-finetuned-squad-seed-4--anas-awadalla|compiled_inference|PASS|
|model--bart-base-few-shot-k-512-finetuned-squad-seed-0--anas-awadalla|compiled_inference|PASS|
|model--bart-base-few-shot-k-512-finetuned-squad-seed-4--anas-awadalla|compiled_inference|PASS|
|model--bart-base-few-shot-k-64-finetuned-squad-seed-0--anas-awadalla|compiled_inference|PASS|
|model--bart-base-few-shot-k-64-finetuned-squad-seed-2--anas-awadalla|compiled_inference|PASS|
|model--bart-base-finetuned-squad--huxxx657|compiled_inference|PASS|
|model--bart-base-samsum--philschmid|compiled_inference|PASS|
|model--bart-base-squad2--sjrhuschlee|compiled_inference|PASS|
|model--bart-base-xsum--harouzie|compiled_inference|PASS|
|model--bart-base-xsum--morenolq|compiled_inference|PASS|
|model--bart-german--Shahm|compiled_inference|PASS|
|model--bart-large-cnn--facebook|compiled_inference|PASS|
|model--bart-large-cnn-samsum--philschmid|compiled_inference|Numerics|
|model--bart-large-finetuned-squadv1--valhalla|compiled_inference|PASS|
|model--bart-large-xsum--facebook|compiled_inference|PASS|
|model--bart-mofe-rl-xsum--praf-choub|compiled_inference|PASS|
|model--bart_lfqa_sqaud--Shubham09|compiled_inference|PASS|
|model--codegen-350M-mono--Salesforce|preprocessing|compiled_inference|
|model--codegen-350M-mono-4bit-qlora--iamtarun|preprocessing|Numerics|
|model--deberta-italian-question-answering--osiria|preprocessing|PASS|
|model--deberta-v3-base-qa-en--LLukas22|preprocessing|PASS|
|model--deberta-v3-base-squad2--deepset|preprocessing|PASS|
|model--deberta-v3-base-squad2--navteca|preprocessing|PASS|
|model--deberta-v3-base__sst2__all-train--SetFit|preprocessing|PASS|
|model--deberta-v3-large-squad2--deepset|preprocessing|PASS|
|model--deberta-v3-large-squad2--sjrhuschlee|preprocessing|PASS|
|model--deberta-v3-xsmall-squad2--nlpconnect|preprocessing|PASS|
|model--deberta_squadnewsqa--sophiebottani|preprocessing|PASS|
|model--distilbart-cnn-12-3--sshleifer|compiled_inference|PASS|
|model--distilbart-cnn-12-6-samsum--philschmid|compiled_inference|PASS|
|model--distilbart-cnn-6-6--sshleifer|compiled_inference|PASS|
|model--distilbart-xsum-1-1--sshleifer|compiled_inference|PASS|
|model--distilbart-xsum-12-1--sshleifer|compiled_inference|PASS|
|model--distilbart-xsum-12-3--sshleifer|compiled_inference|PASS|
|model--distilbart-xsum-12-6--sshleifer|compiled_inference|PASS|
|model--distilbart-xsum-6-6--sshleifer|compiled_inference|PASS|
|model--distilbart-xsum-9-6--sshleifer|compiled_inference|PASS|
|model--finetuned-opt-squad-dataset--choohan|compiled_inference|Numerics|
|model--finetuned-opt-squad-dataset-2--choohan|compiled_inference|Numerics|
|model--finetuned-opt-squad-dataset-3--choohan|compiled_inference|Numerics|
|model--finetuning-sentiment-model-3000-samples--DravenTay|compiled_inference|Numerics|
|model--gemma-tiny-random--yujiepan|compiled_inference|PASS|
|model--llama-160m--JackFram|compiled_inference|PASS|
|model--llama-wikitext--manu|compiled_inference|PASS|
|model--lsg-bart-base-4096-booksum--ccdv|compiled_inference|PASS|
|model--marian-finetuned-kde4-cs2sv--ksaml|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-fr--RajkNakka|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-ar--anibahug|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-es--tmobaggins|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-es--zainnaved|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--Abelll|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--Alesteba|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--DarioLopes|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--Dewa|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--Eitanli|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--Fredvv|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--Leisa|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--Mikey8943|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--Molka11|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--Najeen|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--Neulvo|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--Student3342|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--Thinkcru|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--Yuch|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--aaraki|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--amartyobanerjee|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--aneeshmb02|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--anjankumar|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--apatidar0|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--bishalbaaniya|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--chandrasutrisnotjhong|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--clboetticher|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--coreyabs-db|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--evincent18|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--feeeper|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--jatinshah|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--jfarmerphd|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--kbalde|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--kosec39|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--lewtun|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--libalabala|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--lsimon|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--luhui|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--mbateman|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--miesnerjacob|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--mrp|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--mxalmeida|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--ncduy|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--ornil1|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--raisin2402|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--rootacess|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--sgugger|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--sofa566|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--sungchun71|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--thucdangvan020999|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--tmatup|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--ttri-pruiu|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--vsrinivas|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr-2--Siqi|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr3--Ghost1|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-hi--vsrinivas|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-ja--Hoax0930|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-vi--VanHoan|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-vi--huanvo88|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-vi--huynguyen208|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-zh--DrY|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-zh--chenyanjin|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-zh--luoyixin|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-zh_TW--peterhsu|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-zh_TW-accelerate--peterhsu|compiled_inference|PASS|
|model--mdeberta-v3-base-squad2--sjrhuschlee|preprocessing|PASS|
|model--microsoft-deberta-v3-large_ner_conll2003--Gladiator|preprocessing|PASS|
|model--microsoft_deberta-base_squad--Palak|preprocessing|PASS|
|model--microsoft_deberta-large_squad--Palak|preprocessing|PASS|
|model--neo-125m-wills-loss-function-by-tr--Jellywibble|compiled_inference|PASS|
|model--opt-125m-finetuned-squad-assignment--Isente|compilation|Numerics|
|model--opt-350m--facebook|compiled_inference|Numerics|
|model--opt-350m-wikitext2--lnair|compiled_inference|Numerics|
|model--opt-finetuned-squad-dataset--choohan|compiled_inference|Numerics|
|model--outputs--ankitkupadhyay|preprocessing|PASS|
|model--ov-opt-350m-8bit-85pc-sparse-kv-cache--vuiseng9|compiled_inference|Numerics|
|model--ov-opt-350m-8bit-kv-cache--vuiseng9|compiled_inference|Numerics|
|model--ov-opt-350m-fp32-kv-cache--vuiseng9|compiled_inference|Numerics|
|model--pythia-410mn-ntoxic--skrishna|compiled_inference|PASS|
|model--pythia-70-m-finetuned--selinerdem|compiled_inference|PASS|
|model--pythia-70m-toxicity-model--skrishna|compiled_inference|PASS|
|model--really-tiny-falcon-testing--fxmarty|compiled_inference|PASS|
|model--reward-model-deberta-v3-large-v2--OpenAssistant|preprocessing|PASS|
|model--s2t-medium-librispeech-asr--facebook|compiled_inference|PASS|
|model--smol_llama-220M-GQA--BEE-spoke-data|compiled_inference|PASS|
|model--smol_llama-81M-tied--BEE-spoke-data|compiled_inference|PASS|
|model--tiny-gpt2--taufeeque|compiled_inference|Numerics|
|model--tiny-gpt2-magicprompt--pszemraj|compiled_inference|Numerics|
|model--tiny-random-FalconForCausalLM--illuin|compiled_inference|PASS|
|model--tiny-random-llama--IlyasMoutawwakil|compiled_inference|PASS|
|model--tiny-testing-falcon-alibi--fxmarty|compiled_inference|PASS|
|model--unisumm_3--vishw2703|compiled_inference|PASS|
|resnetv2_50x1_bit.goog_distilled_in1k_vaiq|Numerics|PASS|

