

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

<img width="1056" height="561" alt="Screenshot 2026-06-06 142336" src="https://github.com/user-attachments/assets/d2e5f5e6-cf5b-4bc0-ba10-33cabc4b7e68" />

<img width="1072" height="557" alt="Screenshot 2026-06-06 142752" src="https://github.com/user-attachments/assets/0e5ec9e2-c99f-4c5a-9084-91b3027a6929" />
