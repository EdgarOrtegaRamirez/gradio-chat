---
title: Gradio Chat
emoji: 💬
colorFrom: yellow
colorTo: purple
sdk: gradio
app_file: app.py
pinned: false
---

# Gradio Chat

An example chatbot using [Gradio](https://gradio.app), [`huggingface_hub`](https://huggingface.co/docs/huggingface_hub/v0.22.2/en/index), and the [Hugging Face Inference API](https://huggingface.co/docs/api-inference/index).

## Setup

Install asdf

```bash
brew install asdf
```

Install Python

```bash
asdf plugin-add python
asdf install python
```

Install Poetry

```bash
curl -sSL https://install.python-poetry.org | python3 -
```

Install Dependencies

```bash
poetry install
```

## Run

```bash
poetry run python app.py
```

