# advanced-chatbot-framework

A modular GPT-2-based chatbot system designed for building, training, and deploying intelligent conversational agents. It supports fine-tuning on custom datasets, interactive chat via the command line, and text generation. This framework is ideal for research, prototyping, and extensions into production-ready AI assistants.

---

## Project Structure

```
.
├── buildmodel.py        # Builds and trains the GPT-2 model
├── chatter.py           # Command-line interface for chatting with the trained model
├── generate.py          # Generates text using the trained GPT-2 model
├── gpt-2.py             # Core GPT-2 model setup and architecture
```

---

## Features

- Fine-tunes GPT-2 on any custom text dataset  
- Command-line chatbot interface for interactive conversations  
- Modular design separating training, inference, and interaction  
- Supports clean text generation with contextual flow  

---

## Requirements

- Python 3.8+  
- `transformers`  
- `torch` or `tensorflow` (backend choice)  
- `numpy`  
- `tqdm`  
- `argparse`  

Install dependencies:

```bash
pip install transformers torch numpy tqdm argparse
```

---

## Dataset

Training data must be provided as a plain `.txt` file, with each line representing one sample. Reference the dataset path using the `--data_path` argument when running training scripts.

---

## Author

**Sri Kalyan Reddy Akiti**  
Data Science and Artificial Intelligence  
