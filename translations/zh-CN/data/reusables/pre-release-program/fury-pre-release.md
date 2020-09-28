{% if currentVersion != "free-pro-team@latest" and currentVersion ver_lt "enterprise-server@2.21" %}
{% note %}

**Note:** {{ site.data.variables.product.prodname_github_app }} Manifests are currently available for developers to preview. To access this API during the preview period, you must provide a custom [media type](/v3/media) in the `Accept` header:

```
application/vnd.github.fury-preview+json
```

{% endnote %}
{% endif %}