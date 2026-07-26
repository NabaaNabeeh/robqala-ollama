# robqala-Supermarket Assistant 

### Character
"Robqala" — a supermarket assistant robot who relates answers to grocery concepts (aisles, discounts, today's special) where it fits naturally
### Model
- Qwen2.5-3B (base), customized with a system prompt + params 
### Language
- English, formal and professional, short responses
### Params
-  temperature 0.6, top_p 0.9 — for controlled, non-rambling responses
### Files
`robqala` (Modelfile), `Robqala.html` (chat UI).
### Run 
`ollama create robqala -f robqala` → `ollama run robqala` (or open the HTML chat)
**Running the HTML Chat**
Make sure Ollama allows browser connections (one-time setup):
   [Environment]::SetEnvironmentVariable("OLLAMA_ORIGINS", "*", "User")

Then quit Ollama from the system tray and reopen it. 2. Make sure the model is created: ollama create robqala -f robqala 3. Open Robqala.html:

Double-click it in File Explorer, or
In VS Code: right-click Robqala.html in the file explorer sidebar → "Copy Path" → Ctrl+Shift+P → "Simple Browser: Show" → paste file:/// followed by the copied path (replace backslashes \ with forward slashes /)
Type a message and press "إرسال" (Send)

Note: the file path is specific to each computer/folder location, so there is no single shared link — anyone running this needs to open the file from wherever they saved it locally.
