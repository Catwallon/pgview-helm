## PgView Helm Chart

#### Install

```bash
helm repo add pgview https://catwallon.github.io/pgview-helm
helm repo update
helm install pgview pgview/pgview
```

Or with OCI:

```bash
helm install pgview oci://ghcr.io/catwallon/pgview
```

#### Environment Variables:

`env.PGVIEW_HOST` _(localhost)_  
`env.PGVIEW_PORT` _(5432)_  
`env.PGVIEW_DBNAME` _(postgres)_  
`env.PGVIEW_USER`  
`env.PGVIEW_PASSWORD`  
`env.PGVIEW_URL`  
`env.PGVIEW_LISTEN_PORT` _(8080)_

> Note: If `env.PGVIEW_URL` is set, it will override the other environment variables.
