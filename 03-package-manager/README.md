curl -fsSL -o get_helm.sh https://raw.githubusercontent.com/helm/helm/main/scripts/get-helm-4
chmod 700 get_helm.sh
./get_helm.sh

Then run helm --help, if the user isn't root, it will require root, for ease run `chmod g+x /usr/local/bin/helm
