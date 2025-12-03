FROM ghcr.io/ansible/community-ansible-dev-tools:v25.8.3@sha256:aa1ebb0cd5af73d77abc4e5f143769d5152c2355de3e10cf399367078e9afd32

RUN curl -LO "https://dl.k8s.io/release/$(curl -L -s https://dl.k8s.io/release/stable.txt)/bin/linux/amd64/kubectl" && mv ./kubectl /usr/local/bin/kubectl && chmod +x /usr/local/bin/kubectl


