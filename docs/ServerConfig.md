# OpencodeClient::ServerConfig

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **port** | **Integer** | Port to listen on | [optional] |
| **hostname** | **String** | Hostname to listen on | [optional] |
| **mdns** | **Boolean** | Enable mDNS service discovery | [optional] |
| **cors** | **Array&lt;String&gt;** | Additional domains to allow for CORS | [optional] |

## Example

```ruby
require 'opencode-client'

instance = OpencodeClient::ServerConfig.new(
  port: null,
  hostname: null,
  mdns: null,
  cors: null
)
```

