FROM crossentpx/keras-py36-streamlit

# copy local files into container
COPY mnistapp.py /tmp/
COPY mnist.h5 /tmp/

ENV PORT 8501

# change directory
WORKDIR /tmp

# run commands
CMD ["streamlit", "run", "mnistapp.py"]
