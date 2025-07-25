# ParrotAcoustic

ParrotAcoustic

```bash
curl -Ls https://astral.sh/uv/install.sh | sh
uv venv
source .venv/bin/activate  # On Windows:  venv\Scripts\activate


uv pip install requests flask
uv pip freeze > requirements.txt
```
s
## Training

```bash
uv run server.py
```

## Inference

```bash
uv run inference.py
```

## Testing

```bash
uv run test.py
```
