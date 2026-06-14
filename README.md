# AI State Scanner

Static analyzer for insecure deserialization vulnerabilities in AI agent codebases.

**Finds:** `pickle.loads`, `eval()` on Redis values, dynamic imports with user input, unsafe `json.loads(object_hook)`, and more.

## Quick Start

```bash
git clone https://github.com/YOUR_USERNAME/ai-state-scanner.git
cd ai-state-scanner
pip install -r requirements.txt
export GITHUB_TOKEN="ghp_your_token_here"
python static_analyzer.py
