# OpencodeClient::Command

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **name** | **String** |  |  |
| **description** | **String** |  | [optional] |
| **agent** | **String** |  | [optional] |
| **model** | **String** |  | [optional] |
| **mcp** | **Boolean** |  | [optional] |
| **template** | [**CommandTemplate**](CommandTemplate.md) |  |  |
| **subtask** | **Boolean** |  | [optional] |
| **hints** | **Array&lt;String&gt;** |  |  |

## Example

```ruby
require 'opencode-client'

instance = OpencodeClient::Command.new(
  name: null,
  description: null,
  agent: null,
  model: null,
  mcp: null,
  template: null,
  subtask: null,
  hints: null
)
```

