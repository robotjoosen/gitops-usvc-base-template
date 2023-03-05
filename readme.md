# GitOps Template configured for microservice architecture

# Terminology

| Name        | Kustomize terms | Description                                                                                         |
|-------------|-----------------|-----------------------------------------------------------------------------------------------------|
| Environment | Variant         | An environment contains collection of application with bespoke configuration for a specific cluster |
| Manifest    | Base / Resource | Collection of resources for an application linked together in a kustomization                       |
| Mixin       | Overlay         | A reusable manifest that can be applied to multiple applications                                    |
| Change      | Overlay         | A change is a piece of code that can be promoted across environments                                |
