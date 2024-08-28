# Coiled Login GitHub Action

This GitHub Action logs you in to [Coiled](https://coiled.io) by adding a step to your workflow.

```yaml
  - name: Coiled Login
    uses: coiled/login-action@v1
    with:
      token: ${{ secrets.COILED_API_TOKEN }}
```

Later steps in your workflow can then use the Coiled CLI or Python API to create and manage Dask clusters.
