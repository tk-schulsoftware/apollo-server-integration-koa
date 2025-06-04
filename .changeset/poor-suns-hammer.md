---
'@as-integrations/koa': major
---

Upgrade to koa v3 use @koa/bodyparser and node 18 as a minimum
Since koa v3 only supports node >= 18, we do it too.
Making it compatible with koa-bodyparser and @koa/bodyparser (which is the more up-to-date version)

Adding the call to next() as in https://github.com/apollo-server-integrations/apollo-server-integration-koa/pull/232