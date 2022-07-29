# Push to helm repo

## Usage

```yaml
    - name: push to helm repo
      uses: emqx/push-helm-action@v1
      with:
        charts_dir: "/opt/emqx/deploy/charts/emqx"
        version: "5.0.0"
        aws_access_key_id: ${{ secrets.aws_access_key_id }}
        aws_secret_access_key: ${{ secrets.aws_secret_access_key }}
        aws_region: ${{ secrets.aws_region }}
        aws_bucket_name: ${{ secrets.aws_bucket_name }}
```
