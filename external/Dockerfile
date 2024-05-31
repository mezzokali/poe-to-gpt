FROM python:3.9

WORKDIR /app

COPY . .
RUN pip install -r requirements.txt -i https://pypi.tuna.tsinghua.edu.cn/simple some-package

EXPOSE 5100

CMD [ "python", "api.py" ]
