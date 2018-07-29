# ListAliases<a name="ct-listaliases"></a>

The following example shows a log file generated by calling `ListAliases`\.

```
{
    "Records": [
    {
        "eventVersion": "1.02",
        "userIdentity": {
            "type": "IAMUser",
            "principalId": "EX_PRINCIPAL_ID",
            "arn": "arn:aws:iam::123456789012:user/Alice",
            "accountId": "123456789012",
            "accessKeyId": "EXAMPLE_KEY_ID",
            "userName": "Alice"
        },
        "eventTime": "2014-11-04T00:51:45Z",
        "eventSource": "kms.amazonaws.com",
        "eventName": "ListAliases",
        "awsRegion": "us-east-1",
        "sourceIPAddress": "192.0.2.0",
        "userAgent": "AWS Internal",
        "requestParameters": {
            "limit": 5,
            "marker": "eyJiIjoiYWxpYXMvZTU0Y2MxOTMtYTMwNC00YzEwLTliZWItYTJjZjA3NjA2OTJhIiwiYSI6ImFsaWFzL2U1NGNjMTkzLWEzMDQtNGMxMC05YmViLWEyY2YwNzYwNjkyYSJ9"
        },
        "responseElements": null,
        "requestID": "bfe6c190-63bc-11e4-bc2b-4198b6150d5c",
        "eventID": "a27dda7b-76f1-4ac3-8b40-42dfba77bcd6",
        "readOnly": true,
        "resources": [],
        "eventType": "AwsApiCall",
        "recipientAccountId": "123456789012"
    }
  ]
}
```