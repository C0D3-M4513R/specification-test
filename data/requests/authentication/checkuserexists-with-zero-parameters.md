# checkUserExists with zero parameters

## Request
`get https://vrchat.com/api/1/auth/exists`

| Header | Value |
| ------ | ----- |
| user-agent | `specification-test/@<unstable> https://github.com/vrchatapi/specification-test/issues/new` |
| cookie | `auth=<redacted>; twoFactorAuth=<redacted>` |


## Response
`400 Bad Request`

| Header | Value |
| ------ | ----- |
| access-control-allow-credentials | `true` |
| cache-control | `private, no-cache` |
| connection | `keep-alive` |
| content-length | `86` |
| content-type | `application/json; charset=utf-8` |
| pragma | `no-cache` |
| server | `cloudflare` |
| vary | `Origin, Accept-Encoding` |
| x-frame-options | `deny` |
| x-vrc-api-group | `blue` |
| x-vrc-api-server | `prod-api-blue-food-rgm` |
| x-vrc-api-version | `master-build-2024-07-20-dionysus-v-flipslice` |

```jsonc
{
  "error": {
    "message": "\"username, email, or displayName required\"",
    "status_code": 400
  }
}
```
