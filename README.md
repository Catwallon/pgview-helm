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

#### Configuration:

`env.PGVIEW_DB_HOST` _(localhost)_  
`env.PGVIEW_DB_PORT` _(5432)_  
`env.PGVIEW_DB_USER`  
`env.PGVIEW_DB_PASSWORD`
