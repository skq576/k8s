From python:3.7
# Run pip install --user pygame
# Run mkdir -p /run/aliens/src
# COPY src /run/aliens/src
# CMD ["python3", "/run/aliens/src/alien_invasion.py"]
ADD src/my_script.py /
RUN pip install pystrich
CMD [ "python3", "./my_script.py" ]