---
description: "Automatically generated file. DO NOT MODIFY"
---

```php

<?php

// THIS SNIPPET IS A PREVIEW FOR THE KIOTA BASED SDK. NON-PRODUCTION USE ONLY
$graphServiceClient = new GraphServiceClient($tokenRequestContext, $scopes);

$requestConfiguration = new ServicePrincipalRequestBuilderGetRequestConfiguration();
$queryParameters = ServicePrincipalRequestBuilderGetRequestConfiguration::createQueryParameters();
$queryParameters->select = ["customSecurityAttributes"];
$requestConfiguration->queryParameters = $queryParameters;


$result = $graphServiceClient->servicePrincipals()->byServicePrincipalId('servicePrincipal-id')->get($requestConfiguration);


```