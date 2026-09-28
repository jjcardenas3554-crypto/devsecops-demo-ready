# DevSecOps Demo

Traslade el ZIP a VM01 y ejecute:

```bash
unzip devsecops-demo-ready.zip
cd devsecops-demo-ready
npm install
npm run format
npm run lint
npm test
npm start
```

Pruebe: `/`, `/health`, `/api/users`, `/metrics`.

Importante: `npm install` genera `package-lock.json`. Conserve y suba ese archivo a Git antes de usar `npm ci` o construir la imagen Docker.
practica realizada por: Juan Cardenas
