# DocuLens
Documentation Interpretability and Code Generation
 
## Quickstart

### Step 1: Clone the Repository
- Start by cloning the repository to your local machine:
```
git clone https://github.com/eipie/DocuLens
```

### Step 2: Setup Conda Environment
- Navigate to the project directory:
```
cd DocuLens
```
- Create a new Conda environment and activate it:
```
conda create --name doculens_env python=3.11
conda activate doculens_env
```

### Step 3: Install Dependencies
- Install the required Python packages using pip:
```
pip install -r requirements.txt
``` 

### Step 4: Configure the Environment
- Create a `.env` file in the project root directory and set the necessary environment variables
```
touch .env
```
- Edit the `.env` file and add the required variables:
```
OPENAI_API_KEY=YOUR_KEY_HERE
```

### Step 5: Start the Project!
- Once you have completed the above steps, you may start the project:
```
python app.py
```
