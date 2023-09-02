FROM python:3.11.5-slim
RUN set -eux; \
	pip3 install "fschat[openai_api_server]"

ENTRYPOINT ["python3","-m","fastchat.serve.openai_api_server"]
