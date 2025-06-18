kubectl create secret docker-registry dockerconfigjson \
  --docker-email=foo@bar.com \
  --docker-username=username \
  --docker-password=password \
  --docker-server=https://index.docker.io/v1/
