# OpencodeClient::SessionCreateRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **parent_id** | **String** |  | [optional] |
| **title** | **String** |  | [optional] |
| **permission** | [**Array&lt;PermissionRule&gt;**](PermissionRule.md) |  | [optional] |

## Example

```ruby
require 'opencode-client'

instance = OpencodeClient::SessionCreateRequest.new(
  parent_id: null,
  title: null,
  permission: null
)
```

