# http-sogou.com-path
开放{% data reusables.package_registry.authenticate-packages-github-token %}

### Authenticating with a personal access token

{% data reusables.package_registry.required-scopes %}

You can authenticate to {% data variables.product.prodname_registry %} with Apache Maven by editing your *~/.m2/settings.xml* file to include your personal access token. Create a new *~/.m2/settings.xml* file if one doesn't exist.

In the `servers` tag, add a child `server` tag with an `id`, replacing *USERNAME* with your {% data variables.product.prodname_dotcom
