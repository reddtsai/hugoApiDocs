# hugoApiDocs

Create api docs using HUGO

## Demo Site

[ApiDocs](https://reddtsai.github.io/hugoApiDocs/)

## Quick start

### Step 1 Install Hugo

macOS

```bash
brew hugo
hugo version
```

Windows

```bash
choco install hugo -confirm
hugo version
```

### Step 2 Create a new site

```bash
hugo new site quickstart
```

### Step 3 Add a theme

Add docuapi theme

```bash
git init
git submodule add https://github.com/bep/docuapi.git themes/docuapi
echo 'theme = "docuapi"' >> config.toml
```

### Step 4 Add some content

```bash
hugo new posts/main.md
```

### Step 5 Deploy Hugo as a GitHub pages

See reference
[Host on GitHub](https://gohugo.io/hosting-and-deployment/hosting-on-github/)
