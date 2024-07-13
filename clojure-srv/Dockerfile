FROM clojure

WORKDIR /workspace

RUN apt update && apt install -y git

RUN git clone https://github.com/owainlewis/influx.git download

WORKDIR /workspace/download

# WORKDIR /code

WORKDIR /workspace

COPY bin .

# RUN ghc -O2 --make *.hs -o main -threaded -rtsopts

# CMD ["./main"]
