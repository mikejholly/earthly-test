VERSION 0.7

PROJECT earthly-technologies/earthly-test

FROM alpine

foo:
  RUN echo "HELLO WORLD!"

pipeline-1:
  PIPELINE
  TRIGGER push main
  BUILD +foo
