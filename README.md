# box_build_node

TODO: Enter the cookbook description here.

## Usage

TODO: Describe how to use the cookbook.

## Recipes
***default***

TODO: Describe each recipe.

## Attributes
***default***

TODO: Describe attributes.

## Resources
***my_resource***

TODO: Describe resource

### Examples

- TODO: Describe resource example

```ruby
my_resource 'name' do
  property1 'value1'
end
```

=========

Actions:

| Action  | Description  |
|---------|--------------|
| action1 | Do something |

Properties:

| Property  | Default        | Description          |
|-----------|----------------|----------------------|
| property1 | `'some_value'` | Do something         |
| action    | `:create`      | Action(s) to perform |

## Install locally

````
chef exec berks vendor
chef-client --local-mode --log_level error --override-runlist "box_build_node" --config-option cookbook_path="$(pwd)/berks-cookbooks"
```

## License & Authors
- Author: Mischa Taylor <mischa@misheska.com>

Copyright:: 2017, Mischa Taylor

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
