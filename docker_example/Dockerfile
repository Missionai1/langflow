FROM langflowai/langflow:latest

RUN /app/.venv/bin/python -m ensurepip --upgrade

RUN /app/.venv/bin/python -m pip install html2text tld

ENV PATH="/app/.venv/bin:$PATH"

CMD ["python", "-m", "langflow", "run", "--host", "0.0.0.0", "--port", "7860"]
