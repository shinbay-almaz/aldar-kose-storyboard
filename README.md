# Approach 1: LLM-based
## Setup
### 1. Environment 
```
python3 -m venv venv
source venv/bin/activate
```

### 2. Install Dependencies
```
pip install -r requirements.txt
```

### 3. Setup OpenAI API key
```
cp .env .env.example
```
Update `OPENAI_API_KEY` to your api key.

## Inference

### 1. Run

Open `llm-based-storyboard-generator.ipynb` and run all cells sequentially.

### 2. Input

Provide: 
- A short story (prompt) (2-4 sentences)
- Output folder name.
An interactive cell allows text input and automatic image saving

### 3. Output

Each image is saved as:
```
scene_1.png, scene_2.png, ...
```
Optionally displayed in a grid inside Jupyter.

# Approach 2: LORA + IP

## Setup

### Environment
```
python3 -m venv venv
source venv/bin/activate
```

### Setup
install assets from google drive into 1 directory: 

https://drive.google.com/drive/folders/1WE1Iz9ZAq2lkOeEvds-pg_ngbLiKiVf4?usp=sharing

Follow the ipynb to execute commands necessary for setup.

### Output

Output:

6-8 images name frame{index}.jpg

Output is saved into the working folder (not the sd-scripts-folder)

