# Lora-llama2

## [프로젝트 소개]

Model : Llama2-7B-chat-hf

(https://huggingface.co/meta-llama/Llama-2-7b-chat-hf)

Dataset: Ko-Alpaca Dataset (https://huggingface.co/datasets/royboy0416/ko-alpaca?row=4)

Tools: Google Colab

[기대점]

- Peft - Lora를 활용한 Fine-Tuning를 통한 학습 시간 단축
- Llama2 7B 모델과 gradio 를 결합한 챗봇 구현

[개선해야 할 사항 및 문제점]

- Colab의 GPU 한계로 인한 데이터셋 용량 및 학습 시간 소요량 큼
- 데이터셋 전체를 사용하려했으나, GPU 메모리 한계로 극히 일부분만을 사용
- Pre-trained 된 모델을 사용하였으나, 한국어에 대한 성능 문제
