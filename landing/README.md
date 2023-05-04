# demo.foo landing

## Docker Version 🐳

Use Docker Hub:

```bash
# Pull the image from Docker Hub:
docker pull ulisesgascon/demo-foo-landing:latest

# Run container:
docker run -p 80:80 ulisesgascon/demo-foo-landing:latest
```

To build and run the container locally:

```bash
# Clone Repo:
git clone https://github.com/demofoo/landing.git

# Change to repo's cloned directory:
cd demo-foo-landing

# Build Image locally:
docker build --no-cache -t ulisesgascon/demo-foo-landing:latest .

# Run container:
docker run -p 80:80  ulisesgascon/demo-foo-landing:latest
```

## Development

### Install

```bash
npm i
```

### Start the server

```bash
npm run dev
```
