# Example plugin for `pathogensurveillance`

This is just a idea of how it could work I made for a presentation.
It does not actually work yet.

The idea is that you could insert this plugin into a qmd document like this:

```
{{ zachary-foster/ps_example_plugin }}
```

or 

```
{{ https://github.com/zachary-foster/ps_example_plugin }}
```

And the code for the plugin would be inserted at this point.
Additionally, the presence of this plugin in the analysis will make `pathogensurveillance` run the steps in the pipeline that produces the files needed by this plugin, as defined in the `.plugin_config.yml` file.