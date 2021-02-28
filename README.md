# Generating Rap song Lyrics like Eminem Using GPT2

### I have built a custom model for it using data from Kaggle 

Creating a new finetuned model using data lyrics from leading hip-hop stars

### My model can be accessed at: gagan3012/rap-writer

```
from transformers import AutoTokenizer, AutoModelWithLMHead

tokenizer = AutoTokenizer.from_pretrained("gagan3012/rap-writer")

model = AutoModelWithLMHead.from_pretrained("gagan3012/rap-writer")
```
