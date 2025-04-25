# Basic FastAPI Server

## Setup

1. Create a virtual environment:
   
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```

2. Install dependencies:
   
   ```bash
   pip install -r requirements.txt
   ```

3. Run the server:
   
   ```bash
   uvicorn main:app --reload
   ```

Visit http://localhost:8000 to see the Hello World response.
