# louis
LLM Token Flow Explorer
from pathlib import Path

# Define file path
output_path = Path("/mnt/data/llm_token_flow_explorer_by_louis_spires.html")

# Read HTML content from updated canvas document
html_content = """
<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <title>LLM Token Flow Explorer – by Louis Spires & ChatGPT</title>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/p5.js/1.4.0/p5.min.js"></script>
  <style>
    body { background: #111; color: white; font-family: sans-serif; margin: 0; padding: 0; }
    #inputContainer { position: absolute; top: 10px; left: 10px; z-index: 10; }
    input[type="text"] { width: 400px; font-size: 16px; padding: 5px; }
    select, button { padding: 6px 12px; font-size: 14px; margin-left: 10px; cursor: pointer; }
    #infoBox {
      position: absolute;
      bottom: 10px;
      left: 10px;
      width: 500px;
      background: rgba(0, 0, 0, 0.75);
      padding: 10px;
      font-size: 13px;
      line-height: 1.4;
      color: #ccc;
      border: 1px solid #333;
    }
  </style>
</head>
<body>
<div id="inputContainer">
  <input type="text" id="textInput" placeholder="Enter a sentence..." />
  <select id="headSelector">
    <option value="position">Head 1 – Positional</option>
    <option value="syntax">Head 2 – Syntactic</option>
    <option value="semantic">Head 3 – Semantic</option>
  </select>
  <button onclick="processInput()">Visualize</button>
</div>
<div id="infoBox">
  <strong>LLM Token Flow Explorer</strong><br>
  Created by <em>Louis Spires & ChatGPT</em><br>
  This tool simulates how Large Language Models (LLMs) attend to words when processing language. Type a sentence, choose an attention head, and see how each token relates to others.<br><br>
  <strong>Heads:</strong><br>
  <u>Positional</u> – closer tokens get more attention<br>
  <u>Syntactic</u> – nouns and verbs relate strongly<br>
  <u>Semantic</u> – varied relationships like adjectives → nouns<br><br>
  Hover over a line to see attention weight. The last token is used to generate a simulated prediction.
</div>
<script>
// ... existing JavaScript remains unchanged
</script>
</body>
</html>
"""

# Write content to the HTML file
output_path.write_text(html_content)
output_path.name
Result
'llm_token_flow_explorer_by_louis_spires.html'![llm_token_flow_preview](https://github.com/user-attachments/assets/30578a31-d8ad-47be-a439-3cbd5b3def48)
![llm_token_flow_preview](https://github.com/user-attachments/assets/e15ecddd-c81f-4d1e-9436-901e43b724a1)
![83c9c00e-bef9-425f-8382-95141eb31bd1](https://github.com/user-attachments/assets/c4cbde99-b754-476e-85a6-14807f513938)
