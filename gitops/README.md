# create app


argocd app create apps --repo https://github.com/davidbeijinho/home-infra.git --path gitops --dest-server https://kubernetes.default.svc --dest-namespace default