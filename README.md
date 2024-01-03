# backstage-template-scaffolder-gitlab-runner

this is a scaffolder template for generating kubernetes gitlab runner custom resources using backstage

## quickstart
1. fork this repo
2. adapt default values such as target clusters and gitlab instance
3. use the catalog-import function to add the component to your backstage (link to the template.yaml file!)

## troubleshooting
if you get `not allowed` errors while importing the template, make sure your `app-config.yaml` allows templates:

```yaml
catalog:
  (...)
  rules:
    - allow:
        (...)
        - Template
```
