helm repo add elastic https://helm.elastic.co
helm repo update
helm pull elastic/eck-stack --untar
helm pull elastic/eck-operator --untar