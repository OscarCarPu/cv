# cv

Static personal CV/portfolio page for Oscar Carballo Puebla, served via nginx.
Extracted from the `gv-web` landing page (`/`) into its own standalone site.

## Run

```sh
docker compose up -d
```

Serves at [http://localhost:8090](http://localhost:8090).

## Structure

- `public/` — static site (`index.html`, `style.css`, `perfil.jpeg`, `CV.pdf`, `favicon.ico`)
- `docker-compose.yml` + `nginx.conf` — nginx container serving `public/` on port 8090
