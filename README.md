# kube-tp1

## Pod Nginx

### Héberger un premier Pod Nginx

Créer un fichier nginx-pod.yaml
Appliquer les config du fichier :
```
kubectl apply -f nginx-pod.yaml
```
Vérifier que le pod a été créer :
```
kubectl get pods
```

### A l’aide de la commande kubectl port-forward et d’un navigateur accéder à la page par défaut de votre pod Nginx



##  Connexion entre plusieurs Pods

### A l’image du TP 1 sur Docker (question 7 et 8), héberger un Pod phpmyadmin et mysql, cette fois-ci en utilisant kind

### Créer un service associé au Pod mysql

### Connecter phpmyadmin avec le Service mysql et vérifier que vous pouvez administrer cette base de données

### Avec la commande kubectl-port forward, vérifier que phpmyadmin arrive à contacter et administrer votre base de données mysql

### Ajouter un Ingress pour accéder à phpmyadmin sans utiliser la commande kubectl port-forward
