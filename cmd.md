minikube start --extra-config "apiserver.cors-allowed-origins=["http://boot.dev"]"

kubectl apply -f <yaml file>

kubectl proxy
