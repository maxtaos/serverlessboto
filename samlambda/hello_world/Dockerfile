FROM public.ecr.aws/lambda/python:3.6

COPY lambdapy.py requirements.txt ./

RUN python3.6 -m pip install -r requirements.txt -t .

# Command can be overwritten by providing a different command in the template directly.
CMD ["lambdapy.handler"]
