# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|regression|86.2343|96.2866|10.0523|11.66%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|89.3641|86.4308|-2.9333|-3.28%|
|migraphx_ORT__bert_large_uncased_1|PASS|progression|288.0662|263.9483|-24.1179|-8.37%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|30.4536|30.9787|0.5251|1.72%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|progression|99.9059|84.3414|-15.5646|-15.58%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|regression|252.4035|273.3154|20.912|8.29%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|progression|307.7231|39.0856|-268.6375|-87.3%|
|migraphx_bert__bert-large-uncased|PASS|within tol|369.7435|379.7152|9.9717|2.7%|
|migraphx_cadene__dpn92i1|PASS|regression|168.0101|454.8058|286.7957|170.7%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5356.6548|5318.007|-38.6478|-0.72%|
|migraphx_cadene__resnext101_64x4di1|PASS|regression|324.0579|849.9344|525.8765|162.28%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|5214.1125|5156.7324|-57.3801|-1.1%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|380.0678|384.7207|4.6529|1.22%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|416.043|428.174|12.131|2.92%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|92.0426|94.192|2.1493|2.34%|
|migraphx_models__whisper-tiny-decoder|PASS|regression|31.5853|33.3037|1.7184|5.44%|
|migraphx_models__whisper-tiny-encoder|Numerics|progression|511.4263|181.5707|-329.8557|-64.5%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|84.1417|86.5604|2.4187|2.87%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|47.3789|40.0687|-7.3101|-15.43%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1589.2855|1571.5187|-17.7668|-1.12%|
|migraphx_torchvision__inceptioni1|PASS|within tol|191.204|192.9003|1.6963|0.89%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5390.8876|5312.7664|-78.1212|-1.45%|
|migraphx_torchvision__resnet50i1|PASS|within tol|85.2113|85.7098|0.4985|0.59%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5014.8474|5058.103|43.2555|0.86%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2673.5434|2580.4051|-93.1384|-3.48%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4196.1467|4368.0059|171.8592|4.1%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5823.0431|5893.0757|70.0326|1.2%|
|migx_bench_bert-large-uncased_1_128|PASS|regression|165.6155|185.9102|20.2947|12.25%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|273.2465|265.2713|-7.9753|-2.92%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|375.6087|389.5034|13.8947|3.7%|
|migx_bench_bert-large-uncased_2_128|PASS|regression|388.1502|408.0383|19.8881|5.12%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|586.9483|589.0963|2.148|0.37%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|864.6249|829.2859|-35.339|-4.09%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5003.4327|5114.7534|111.3207|2.22%|
|migx_bench_bert-large-uncased_32_256|PASS|progression|8635.0167|8151.1843|-483.8325|-5.6%|
|migx_bench_bert-large-uncased_32_384|Numerics|progression|11778.2794|11072.831|-705.4484|-5.99%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|713.194|723.87|10.676|1.5%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|1081.8913|1098.5098|16.6185|1.54%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1551.9377|1518.7978|-33.1398|-2.14%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|1308.2743|1283.7773|-24.4971|-1.87%|
|migx_bench_bert-large-uncased_8_256|PASS|progression|2241.8476|2062.4219|-179.4257|-8.0%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|2884.1955|2869.7207|-14.4748|-0.5%|

## No Regressions Found

## No Progressions Found

