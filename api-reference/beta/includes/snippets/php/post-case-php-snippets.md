---
description: "Automatically generated file. DO NOT MODIFY"
---

```php

<?php

// THIS SNIPPET IS A PREVIEW FOR THE KIOTA BASED SDK. NON-PRODUCTION USE ONLY
$graphServiceClient = new GraphServiceClient($tokenRequestContext, $scopes);

$requestBody = new EscapedCase();
$requestBody->setDisplayName('My Case 1');



$result = $graphServiceClient->compliance()->ediscovery()->cases()->post($requestBody);


```