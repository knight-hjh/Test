# README

Official code for "Assessing the GPT Series in Smart Contract Vulnerability Repair: An Empirical Study" which has been submitted to ICSE 2026

## File Information
>__dataset__
>>_dataset0_: The merged and manually reviewed dataset contains 1,290 contracts as well as 1,410 vulnerabilities.

>>_dataset1_: Pre-processed contract vulnerability data and contract data after LLM repair.

>>REDAME.md

>__data_preprocessing.py__: Functions that perform vulnerability contract preprocessing.
>__gpt_query.py__: Only fix a single vulnerability per contract
>__gpt_query_ret_json.py__: Each contract only fixes a single vulnerability and returns it in json format
>__result_processing.py__ : Contract repair based on GPT results
>__utils.py__
>README.md
>config.py
