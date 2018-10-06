# Workshop materials

This document: https://kubernetes.grahovac.pro

Elena Grahovac

- hello@grahovac.pro
- https://twitter.com/webdeva
- https://github.com/rumyantseva

## Agenda

- Morning coffee & Registration  - 9:30 - 10:00
- Introduction & Preparation     - 10:00 - 11:00
- Coffee break                   - 11:00 - 11:15
- Writing Go from scratch        - 11:15 - 12:15
- Lunch (Provided at the venue)  - 12:15 - 13:00
- Getting ready for production   - 13:00 - 14:45
- Coffee Break                   - 14:45 - 15:00
- Ship it!                       - 15:00 - 16:45
- Q&A + Optional topics          - 16:45 - 17:30

## Checklist

- Go: https://golang.org/dl/
- IDE or editor to write code
- Docker CE: https://www.docker.com/community-edition#/download
- If Windows: Cygwin - https://cygwin.com/install.html
- GitHub Account: https://github.com
- Git client

## Cleanup notes

- The cluster will be available for a couple of weeks.
- On October, 20th the cluster and all the data will be deleted.
- If you want us to delete your data earlier, please let us know.

## Additional slides
- http://gowayfest.grahovac.pro

## Example service

https://github.com/rumyantseva/go-sofia

## Check your Kubernetes-readines

Follow the instruction: https://ui.k8s.community

```
USER=your_github_user
kubectl run hello-app --image=gcr.io/google-samples/hello-app:1.0 --port=8080 -n ${USER}
kubectl expose deployment hello-app -n ${USER}
```
