# CocoNexa demo (lightweight)

This version runs without PyTorch, so it starts quickly and uses little memory.
It works in demo mode (colour-based estimate) until best.pt is added.

Build command:  pip install -r requirements.txt
Start command:  streamlit run app.py --server.port $PORT --server.address 0.0.0.0 --server.headless true

To use the real model later:
1. Add ultralytics and opencv-python-headless to requirements.txt (and torch CPU if needed).
2. Copy best.pt into this folder.
3. Redeploy.

SMS (Twilio) is optional. Without it, login codes appear on screen for testing.
