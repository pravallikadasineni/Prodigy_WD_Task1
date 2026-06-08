

https://github.com/user-attachments/assets/d7f7572f-e8a6-4680-ba86-3b23a06d339e

### My Task Code:
from transformers import pipeline

generator = pipeline(
    "text-generation",
    model="gpt2"
)

prompt = input("Enter Prompt: ")

result = generator(
    prompt,
    max_length=100
)

print(result[0]["generated_text"])
