FROM matrixdotorg/synapse:latest

RUN apt-get update -yqq && apt-get install git -yqq && apt-get clean -yqq
RUN pip install --no-deps git+https://github.com/devture/matrix-synapse-shared-secret-auth