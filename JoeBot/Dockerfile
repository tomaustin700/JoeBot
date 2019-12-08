FROM tensorflow/tensorflow:1.15.0-py3
EXPOSE 5000
ADD ChatBot.py /
ADD intents.json /

RUN pip install numpy
RUN pip install tflearn
RUN pip install nltk
RUN pip install flask

CMD ["python", "./ChatBot.py"]
