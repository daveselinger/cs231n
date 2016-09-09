FROM jupyter/scipy-notebook

RUN cd ~ && \
 wget http://vision.stanford.edu/teaching/cs231n/winter1516_assignment1.zip && \
 unzip ~/winter1516_assignment1.zip && \
 mv ~/assignment1/* ~/work/ && \
 ls ~/work/ && \
 ls ~/work/cs231n/ && \
 ls ~/work/cs231n/datasets && \
 cd ~/work/cs231n/datasets && \
 ./get_datasets.sh && \
 echo "You should tag this build and then can start it by using 'docker run -p 8888:8888 BUILD_TAG'"

