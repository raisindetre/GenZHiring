
# GenZ Hiring
ATS Scorer based on Large Language Models (LLM).

### Requirements
* A valid [OpenAI API](https://platform.openai.com/) key.
* A valid [SerpAI API](https://serpapi.com/) key (returns Google search results).

### Compatability
On OSX Silicon, requirements do not build for Py 3.12 (no built wheels for some libs). Py 3.11 is tested and functioning. The code uses old OpenAI endpoints so requires `openai==0.28` to run.

### Configuration
Copy `.env.example` to `.env` and add your OPENAI and SERPAI keys, save then run:`python3 ./main.py`.

Once the app is loaded, open the app host address in your browser - by default `http://127.0.0.1:5000/`.

https://github.com/FarhaanJamal/GenZHiring/assets/95125546/20745b50-eee0-4849-8e69-e5748fb778e7

![genz1](https://github.com/FarhaanJamal/GenZHiring/assets/95125546/1bd3da8b-60c0-40c5-bfec-66c9651b966d)
![genz2](https://github.com/FarhaanJamal/GenZHiring/assets/95125546/5024a0bb-fb5f-46de-9946-a3147f69f7aa)
![genz3](https://github.com/FarhaanJamal/GenZHiring/assets/95125546/53f0dbf7-e6eb-42cf-8cec-f3131c6200d7)
![genz4](https://github.com/FarhaanJamal/GenZHiring/assets/95125546/0ede5a40-b872-459c-8bee-163b95799cec)
