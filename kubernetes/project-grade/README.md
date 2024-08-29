# Useful Commands
### - kubectl apply -f grade-submission-portal-pod.yaml
### - kubectl describe pod grade-submission-portal
### - kubectl logs grade-submission-portal
### - kubectl logs grade-submission-portal -f
### - kubectl port-forward grade-submission-portal 8080:5001
### - kubectl logs -f grade-submission-portal -c grade-submission-portal
### - kubectl logs -f grade-submission-portal -c grade-submission-portal-health-checker
### - k run -h | less
### - k delete pods,services --all -n grade-submission
### - k apply -f . -n grade-submission
### - k get deployments -n grade-submission
### - kubectl rollout undo deployment/grade-submission-api -n grade-submission  (rollback the deployment)