# YAML getting started (internal only, public preview soon)

# Samples
- [Run scripts](yaml/script.yml)
- [Run powershell scripts](yaml/powershell.yml)
- [Run bash scripts](yaml/bash.yml)
- [Template with matrix](yaml/vsbuild-template.yaml) and [consumer entry file](yaml/vsbuild.yaml) with a phase override.
  - Simplified matrix syntax coming soon - will not have to resort to mustache iterator.
- More samples coming soon. Deserialization [details here](yamldeserialization.md).

# Create a definition
- Set feature flag Build2.Yaml
- Create a definition, save a variable `_yaml_preview` that points to the relative path of your YAML file. E.g. path/to/my/build.yaml
  - UI coming soon.
