## keel-deployment

Installing or upgrade with helm
```bash
helm upgrade --install keel keel/keel --values keel/values.yaml -n pintu
```

## Access Public Keel Dashboard
```
host    : http://34.101.146.58:9300/
username: pintu
password: jaringan
```

## Flow CI/CD
![pintu_test drawio](https://user-images.githubusercontent.com/67618475/173169443-d8fcab5b-3c52-4f0a-a683-0795e94c2bdd.png)

## References
  - https://keel.sh/docs/#deploying-with-helm
  - https://github.com/keel-hq/keel
  - https://keel.sh/docs/#dockerhub-webhooks
