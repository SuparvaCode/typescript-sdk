---
'@modelcontextprotocol/server': patch
---

Set `Allow: POST` header on 405 Method Not Allowed responses in the stateless HTTP fallback handler per RFC 9110 §15.5.6.
