FROM python:3.9-alpine

# Install iproute2 to get the 'ip' command
RUN apk add --no-cache iproute2

WORKDIR /home/data

COPY data/IF.txt /home/data/
COPY data/AlwaysRememberUsThisWay.txt /home/data/
COPY scripts.py /home/data/

CMD ["python", "/home/data/scripts.py"]
