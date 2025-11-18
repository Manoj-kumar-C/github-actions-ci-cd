```

repo-root/
├─ api/              # FastAPI app
│  ├─ app/
│  ├─ Dockerfile     # dev Dockerfile (or Dockerfile.dev)
│  ├─ Dockerfile.prod
│  └─ requirements.txt
├─ web/              # Next.js app
│  ├─ package.json
│  ├─ Dockerfile     # dev
│  └─ Dockerfile.prod
├─ .github/
│  └─ workflows/
│     ├─ fastapi-ci-cd.yml
│     └─ nextjs-ci-cd.yml
└─ .dockerignore


```