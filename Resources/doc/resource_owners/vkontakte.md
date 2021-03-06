Step 2x: Setup Vkontakte
========================
First you will have to register your application on Vkontakte. Check out the
documentation for more information: http://vk.com/developers.php.

Next configure a resource owner of type `vkontakte` with appropriate
`client_id`, `client_secret` and `scope`. Refer to the Vkontakte documentation
for the available [scopes](http://vk.com/developers.php?oid=-17680044&p=Application_Access_Rights).

```yaml
# app/config/config.yml

hwi_oauth:
    resource_owners:
        any_name:
            type:                vkontakte
            client_id:           <client_id>
            client_secret:       <client_secret>
```

When you're done. Continue by configuring the security layer or go back to
setup more resource owners.

- [Step 2: Configuring resource owners (Facebook, GitHub, Google, Windows Live and others](../2-configuring_resource_owners.md)
- [Step 3: Configuring the security layer](../3-configuring_the_security_layer.md).
