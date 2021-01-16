# Simple Matterport sample
https://matterport.github.io/showcase-sdk/sdkbundle_tutorials_setup.html

## Setup

1. Download sdk files

```
curl https://static.matterport.com/showcase-sdk/bundle/3.1.16.9-17-gacf9fb85e/showcase-bundle.zip -o bundle.zip
unzip bundle.zip -d ./bundle
```

2. set up application key
  - open index.html
  - Fill sdk key

```
19L: <script>
20L: const sdkKey = '[Put SDK Key]'
21L: 
```

3. run server

e.g.

```
python -m http.server 8001  # then open http://localhost:8001
```
