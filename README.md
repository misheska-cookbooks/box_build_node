# box_build_node

Wrapper cookbook that generates boxcutter build nodes

## Usage

On a macOS machine, provision with the following, using the recipe for
the specific build node.

````
chef exec berks vendor
chef-client --local-mode --log_level error --override-runlist "box_build_node::<node_recipe>" --config-option cookbook_path="$(pwd)/berks-cookbooks"
```

## Recipes
***default***

winry - winry build machine
