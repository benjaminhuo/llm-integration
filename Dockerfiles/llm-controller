FROM python:3.11.5-slim
RUN set -eux; \
	pip3 install "fschat[controller]"

ENTRYPOINT ["python3","-m","fastchat.serve.controller"]
