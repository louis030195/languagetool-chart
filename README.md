# languagetool-chart

**⚠️Work in progress⚠️.**


```bash
helm repo add louis030195 https://louis030195.github.io/languagetool-chart
helm repo update
helm install languagetool languagetool-chart -n languagetool --create-namespace
```

```bash
SENTENCE="Das Spielzeug ist in 7 Größen und Formen auf 7 verschiedene Karottengrößen zugeschnitten.z"
curl --data "language=auto&text=$SENTENCE" https://foo-bar.com/v2/check
```