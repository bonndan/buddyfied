FROM williamyeh/ansible:alpine3-onbuild

COPY playbook.yml /

ENV HOST $HOST
ENV SUDO_PASSWORD $SUDO_PASSWORD

CMD ansible-playbook -vvv -i $HOST, playbook.yml
