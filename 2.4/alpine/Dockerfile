FROM eclecticiq/ansible:2.4

RUN apk --no-cache --update add --virtual .deps \
  gcc \
  linux-headers \
  musl-dev \
  python2-dev \
  && pip install molecule \
  && apk del .deps
