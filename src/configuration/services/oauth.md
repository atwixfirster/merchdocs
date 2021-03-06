---
title: OAuth
---

Stores > Settings > [Configuration]({{ site.baseurl }}{% link stores/configuration.md %}) > [Services]({{ site.baseurl }}{% link configuration/services.md %}) >  OAuth

## Access Token Expiration

![]({{ site.baseurl }}{% link images/images/config-services-oauth-access-token-expiration.png %}){: .zoom}
_Access Token Expiration_

|Field|[Scope]({{ site.baseurl }}{% link configuration/scope.md %})|Description|
|--- |--- |--- |
|Customer Token Lifetime (hours)|Global|Determines the length of time in hours before a customer API token expires. The customer token never expires if field is empty. Default value: 1|
|Admin Token Lifetime (hours)|Global|Determines the length of time in hours before an admin API token expires. The admin token never expires if the field is empty. Default value: 4|

## Cleanup Settings

![]({{ site.baseurl }}{% link images/images/config-services-oauth-cleanup-settings.png %}){: .zoom}
[_Cleanup Settings_]({{ site.baseurl }}{% link system/integrations.md %})

|Field|[Scope]({{ site.baseurl }}{% link configuration/scope.md %})|Description|
|--- |--- |--- |
|Cleanup Probability|Global|Specifies the number of OAuth requests before cleanup is launched. Do not enter 0 to disable cleanup.|
|Enable WSDL Cache|Global|Determines the age of entries in minutes, before they are cleaned.|

## Consumer Settings

![]({{ site.baseurl }}{% link images/images/config-services-oauth-consumer-settings.png %}){: .zoom}
[_Consumer Settings_]({{ site.baseurl }}{% link system/integrations.md %})

|Field|[Scope]({{ site.baseurl }}{% link configuration/scope.md %})|Description|
|--- |--- |--- |
|OAuth consumer credentials HTTP Post timeout|Global|Specifies the number of seconds it takes for the system to timeout when customers post their credentials.|
|OAuth consumer credentials HTTP Post maxredirects|Global|Specifies the maximum number of redirects that can take place which are related to a posting of consumer credentials.|
|Expiration Period|Global|Determines the number of seconds before an unused key/secret expires after the OAuth token exchange begins.|
