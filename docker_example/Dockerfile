FROM langflowai/langflow:latest

RUN pip install html2text tld

CMD ["python", "-m", "langflow", "run", "--host", "0.0.0.0", "--port", "7860"]
