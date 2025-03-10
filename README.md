# OpenVINO_POC
This repo contains POC works including generalized AI pipelines and function features for scaling which are based on OpenVINO API and OpenVINO GenAI API. There includes new model /pipeline enabling samples; fork of OpenVINO empowered and integrated 3rd part tools.

## Project 1: RAG serving pipeline based on OpenVINO GenAI
The OpenVINO GenAI Server(OGS) is a client-server based pipeline framework for generative AI and multimodal models. It demostrates the pure C++ RAG samples of LLM & retrival with vectorDB. The repo also provides the sample of image search with CLIP model and vectorDB.

repo link: [https://github.com/sammysun0711/openvino.genai/tree/rag_sample/samples/cpp/rag_sample](https://github.com/sammysun0711/openvino.genai/tree/rag_sample/samples/cpp/rag_sample)
<details>
<summary><b>Why use OpenVINO GenAI Server (OGS)? </b></summary>
<li>Most <b>light-weighted</b> serving solution without docker container;</li> 
<li>Pure <b>C++ interface</b> for edge/client application deployment;</li>
<li>Pure OpenVINO backend with <b>minimum package size</b>;</li>
<li><b>Cross Hardware platform</b> deployment among Intel CPU/iGPU/dGPU/NPU;</li>
  
  ![OpenVINO GenAI Server Architecture](https://github.com/user-attachments/assets/faa394cf-4a03-48db-990e-0a44102b787d "OpenVINO GenAI Server Architecture")
</details>

## Project 2: AI Speech
This projects contains OV enabled ASR and TTS models, the C++ pipeline ready to be direct scaling. And customized modification for effective tuning in application.
* [MeloTTS OV cpp pipeline](https://github.com/apinge/MeloTTS.cpp) | [blog](https://blog.openvino.ai/blog-posts/optimizing-melotts-for-aipc-deployment-with-openvino-a-lightweight-tts-solution)
* [SenseVoice](https://github.com/apinge/SenseVoice.OpenVINO)


