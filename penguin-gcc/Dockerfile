FROM mathersm/linux-common

RUN apt-get update \
 && apt-get install -y \
      g++-8 \
 && rm -rf /var/lib/apt/lists/* \
 && git clone git://github.com/mathersm/Penguin.git /opt/Penguin


ENV CXX=g++-8 \
    PENGUIN_ROOT=/opt/Penguin \
    LD_LIBRARY_PATH=$LD_LIBRARY_PATH:$PENGUIN_ROOT/lib

WORKDIR $PENGUIN_ROOT


