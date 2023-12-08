# SFTChatGPT_for_chemtext_mining

## Datasets

Preprocessed data have been placed in corresponding folders:

- ```Paragraph2Comound/```

- ```Paragraph2RXNRole/prod/``` and ```Paragraph2RXNRole/role/```

- ```Paragraph2MOFInfo/```

- ```Paragraph2NMR/```

- ```Paragraph2Action/``` dataset is derived from pistachio dataset, which is available upon request.

## Finetuning-ChatGPT

### Environment (OS: Windows or Linux)

```bash
pip install openai
pip install pandas
```
Note: The fine-tuning code has been slightly different as the version of openai has been updated to v1.0.0+.

Here, we provide the latest code.

Before 2023.11.06, we set model = "gpt-3.5-turbo-0613"

After 2023.11.06, we can set model = "gpt-3.5-turbo-1106" (recommend)

### Implementation

Specific scripts  for each task are in the corresponding folders.

####  Demo of Finetuning-ChatGPT on small data

Here, we gave an example notebook of fine-tuning ChatGPT on 25 Paragraph2NMR data in ```demo/demo_of_fine-tuning_chatgpt_on_paragraph2NMR.ipynb```, including:

 - Preprocessing
 - Training
 - Inferencing
 - Evaluating

## Language Model Baselines

### Environment (Linux)

Codes will be released soon ...

