# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|progression|90.5208|85.3842|-5.1366|-5.67%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|88.5503|89.591|1.0407|1.18%|
|migraphx_ORT__bert_large_uncased_1|PASS|progression|285.9162|257.4052|-28.511|-9.97%|
|migraphx_ORT__distilgpt2_1|PASS|progression|34.4445|31.2472|-3.1973|-9.28%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|regression|86.8567|98.7786|11.9219|13.73%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|progression|302.6657|248.0021|-54.6635|-18.06%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|regression|40.9478|43.3367|2.3889|5.83%|
|migraphx_bert__bert-large-uncased|PASS|progression|762.6833|390.5077|-372.1755|-48.8%|
|migraphx_bert__bertsquad-12|PASS|within tol|86.7035|86.8825|0.179|0.21%|
|migraphx_cadene__dpn92i1|PASS|within tol|181.0374|178.1699|-2.8675|-1.58%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|6634.3361|6794.1704|159.8343|2.41%|
|migraphx_cadene__resnext101_64x4di1|PASS|progression|543.7047|376.782|-166.9227|-30.7%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|progression|412.1433|390.6549|-21.4884|-5.21%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|434.7994|430.0274|-4.772|-1.1%|
|migraphx_mlperf__resnet50_v1|PASS|regression|96.9481|119.2004|22.2524|22.95%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|32.9723|32.2664|-0.706|-2.14%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|188.8142|182.493|-6.3211|-3.35%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|79.4703|77.5851|-1.8851|-2.37%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|48.7868|44.3579|-4.4289|-9.08%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1335.9883|1307.341|-28.6473|-2.14%|
|migraphx_torchvision__inceptioni1|PASS|regression|217.8568|238.0094|20.1526|9.25%|
|migraphx_torchvision__inceptioni32|PASS|within tol|6790.4379|6677.8886|-112.5493|-1.66%|
|migraphx_torchvision__resnet50i1|PASS|regression|102.1274|121.9718|19.8444|19.43%|
|migraphx_torchvision__resnet50i64|PASS|within tol|6095.6932|6019.9044|-75.7887|-1.24%|
|migx_bench_bert-large-uncased_16_128|PASS|regression|2576.2003|2759.5673|183.3671|7.12%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4151.446|4117.2409|-34.2051|-0.82%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5806.1065|5824.2386|18.1321|0.31%|
|migx_bench_bert-large-uncased_1_128|PASS|regression|160.1658|171.8359|11.6701|7.29%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|266.6018|262.7133|-3.8885|-1.46%|
|migx_bench_bert-large-uncased_1_384|PASS|regression|397.372|447.5602|50.1882|12.63%|
|migx_bench_bert-large-uncased_2_128|PASS|progression|405.5461|374.9969|-30.5492|-7.53%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|587.6715|596.9295|9.258|1.58%|
|migx_bench_bert-large-uncased_2_384|PASS|progression|920.0325|835.907|-84.1255|-9.14%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5241.113|5103.7411|-137.3719|-2.62%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|8129.5684|8176.8404|47.2721|0.58%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|11746.0397|11525.9705|-220.0692|-1.87%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|707.084|721.951|14.867|2.1%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|1133.8213|1119.9822|-13.8391|-1.22%|
|migx_bench_bert-large-uncased_4_384|PASS|regression|1548.8315|1650.3227|101.4911|6.55%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|1489.2101|1540.8992|51.6891|3.47%|
|migx_bench_bert-large-uncased_8_256|PASS|progression|2257.3062|2115.1777|-142.1285|-6.3%|
|migx_bench_bert-large-uncased_8_384|PASS|progression|3303.48|2980.8059|-322.6741|-9.77%|

## No Regressions Found

## No Progressions Found

