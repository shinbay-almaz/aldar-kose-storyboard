# Setup
## 1. Environment 
```
python3 -m venv venv
source venv/bin/activate
```

## 2. Install Dependencies
```
pip install -r requirements.txt
```

## 3. Setup OpenAI API key
```
cp .env .env.example
```
Update `OPENAI_API_KEY` to your api key.

# Inference

## 1. Run

Open `llm-based-storyboard-generator.ipynb` and run all cells sequentially.

## 2. Input

Provide: 
- A short story (prompt) (2-4 sentences)
- Output folder name.
An interactive cell allows text input and automatic image saving

## 3. Output

Each image is saved as:
```
scene_1.png, scene_2.png, ...
```
Optionally displayed in a grid inside Jupyter.
