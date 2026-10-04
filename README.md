# transport-ai
AI-powered transport disruption information and passenger assistance prototype for IntelliCon26.

# Transport AI - IntelliCon26 Prototype
from fastapi import FastAPI

app = FastAPI()

@app.get("/")
def read_root():
    return {"message": "Transport AI Disruption Platform API running"}
