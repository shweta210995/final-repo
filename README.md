bucket name :shweta-amilkanthwar
topic name is: shwetaA1 
cloudhub url for mule app is http://awssuite1.us-e2.cloudhub.io/notification  
Note:upload sample,txt file to bucket .Uploaded sample.txt file here also
logs of cloudhub:

14:01:20.757     11/17/2019     Worker-0     [MuleRuntime].cpuLight.03: [awssuite1].awssuiteFlow.CPU_LITE @3457a3a9     INFO
event:a048c160-0914-11ea-83be-0aba0b7ef78a {
  "Type" : "Notification",
  "MessageId" : "4e7aef49-b8f1-5b12-94dc-b902bf649706",
  "TopicArn" : "arn:aws:sns:us-east-2:211556697089:shwetaA1",
  "Subject" : "Amazon S3 Notification",
  "Message" : "{\"Records\":[{\"eventVersion\":\"2.1\",\"eventSource\":\"aws:s3\",\"awsRegion\":\"us-east-2\",\"eventTime\":\"2019-11-17T08:31:17.850Z\",\"eventName\":\"ObjectCreated:Put\",\"userIdentity\":{\"principalId\":\"A39VLY7V75TPJC\"},\"requestParameters\":{\"sourceIPAddress\":\"114.143.158.78\"},\"responseElements\":{\"x-amz-request-id\":\"088A2AA31107D041\",\"x-amz-id-2\":\"1AzmWnyhbgpikah1HFW8Jn2GcacP6smW3NatSPuix50enTMCvZClkpnG6pzyEjZSAZKurPtq/1o=\"},\"s3\":{\"s3SchemaVersion\":\"1.0\",\"configurationId\":\"shweta test\",\"bucket\":{\"name\":\"shweta-amilkanthwar\",\"ownerIdentity\":{\"principalId\":\"A39VLY7V75TPJC\"},\"arn\":\"arn:aws:s3:::shweta-amilkanthwar\"},\"object\":{\"key\":\"sample.txt\",\"size\":35473,\"eTag\":\"0542bf472647d0bd7734520e35c84801\",\"sequencer\":\"005DD10555CCAC790F\"}}}]}",
  "Timestamp" : "2019-11-17T08:31:17.908Z",
  "SignatureVersion" : "1",
  "Signature" : "bVkWF/KaF9lJw+xTOgDIm7lgdiDZ13FhKkw/4Kz/f6sDo9/g20IQ8O17FoJmiUvuQN/QMaey+eGQv0Vnd6NPqlMLqRbdAwXyl0hBr/uJoUCVreIH4GRQD/+6L/WvokA31npm+pMdcsS6I59VWyN2E+PosIWQFeaor+SBSLZHY6PQ+djFh6GzXRxfx58CAKOI2gfFzGCiRK63J2N4Yo7+AS5eew+h92nJ/pM3lHDttbdmX2/kLjIbvpZ2phFfGifFnZ3f5hoVF8ZYLPHH8SDl28omVa/OerMzASVf387zigwA5ugSxOWh0DEuLWCNQQRbnVwNhlT4Trd2Q8EkWFM8Kw==",
  "SigningCertURL" : "https://sns.us-east-2.amazonaws.com/SimpleNotificationService-6aad65c2f9911b05cd53efda11f913f9.pem",
  "UnsubscribeURL" : "https://sns.us-east-2.amazonaws.com/?Action=Unsubscribe&SubscriptionArn=arn:aws:sns:us-east-2:211556697089:shwetaA1:08e713b8-fb77-4876-a5a8-526b022c0035"
}
14:01:20.759     11/17/2019     Worker-0     [MuleRuntime].cpuLight.03: [awssuite1].awssuiteFlow.CPU_LITE @3457a3a9     INFO
event:a048c160-0914-11ea-83be-0aba0b7ef78a message received from aws
14:01:23.285     11/17/2019     Worker-0     [MuleRuntime].io.01: [awssuite1].awssuiteFlow.BLOCKING @ea9499     INFO
event:a048c160-0914-11ea-83be-0aba0b7ef78a content of file is: 'a2o1C000005GoR8QAK',
'a2o1C000005GoR6QAK',
'a2o1C000005GoVNQA0',
'a2o1C000005GoRkQAK',
'a2o1C000005GoUVQA0',
'a2o1C000005GoW7QAK',
'a2o1C000005GoVsQAK',
'a2o1C000005GoXnQAK',
'a2o1C000005GobbQAC',
'a2o1C000005Gob6QAC',
'a2o1C000005GobNQAS',
'a2o1C000005GoZQQA0',
'a2o1C000005GoYrQAK',
'a2o1C000005GoXAQA0',
'a2o1C000005GobOQAS',
'a2o1C000005YUN4QAO',
'a2o1C000005YUOOQA4',
'a2o1C000005YUN7QAO',
'a2o1C000005YUNDQA4',
'a2o1C000005YUNdQAO',
'a2o1C000005YUNEQA4',
'a2o1C000005YUNFQA4',
'a2o1C000005YUNGQA4',
'a2o1C000005YUNHQA4',
'a2o1C000005YUNNQA4',
'a2o1C000005YUNOQA4',
'a2o1C000005YUNPQA4',
'a2o1C000005YUNQQA4',
'a2o1C000005YUNRQA4',
'a2o1C000005YUNXQA4',
'a2o1C000005YUNYQA4',
'a2o1C000005YUMyQAO',
'a2o1C000005YUMzQAO',
'a2o1C000005YUN0QAO',
'a2o1C000005YUN2QAO',
'a2o1C000005YUN3QAO',
'a2o1C000005YUOVQA4',
'a2o1C000005YUOYQA4',
'a2o1C000005YUOZQA4',
'a2o1C000005YUOfQAO',
'a2o1C000005YUOPQA4',
'a2o1C000005YUNhQAO',
'a2o1C000005YUNiQAO',
'a2o1C000005YUNjQAO',
'a2o1C000005YUNkQAO',
'a2o1C000005YUNlQAO',
'a2o1C000005YUNrQAO',
'a2o1C000005YUNsQAO',
'a2o1C000005YUNtQAO',
'a2o1C000005YUNvQAO',
'a2o1C000005YUO1QAO',
'a2o1C000005YUO2QAO',
'a2o1C000005YUO3QAO',
'a2o1C000005YUO4QAO',
'a2o1C000005YUO5QAO',
'a2o1C000005YUOBQA4',
'a2o1C000005YUODQA4',
'a2o1C000005YUNfQAO',
'a2o1C000005YUNgQAO',
'a2o1C000005YUOEQA4',
'a2o1C000005YUOFQA4',
'a2o1C000005YUOLQA4',
'a2o1C000005YUOMQA4',
'a2o1C000005YUONQA4',
'a2o1C000005YUN5QAO',
'a2o1C000005YUPcQAO',
'a2o1C000005YUPkQAO',
'a2o1C000005YUPlQAO',
'a2o1C000005YUPmQAO',
'a2o1C000005YUPsQAO',
'a2o1C000005YUPuQAO',
'a2o1C000005YUPvQAO',
'a2o1C000005YUPwQAO',
'a2o1C000005YUQ2QAO',
'a2o1C000005YUQ4QAO',
'a2o1C000005YUQ5QAO',
'a2o1C000005YUQ6QAO',
'a2o1C000005YUQ7QAO',
'a2o1C000005YUQ8QAO',
'a2o1C000005YUQ9QAO',
'a2o1C000005YUQAQA4',
'a2o1C000005YUQBQA4',
'a2o1C000005YUQHQA4',
'a2o1C000005YUQIQA4',
'a2o1C000005YUQJQA4',
'a2o1C000005YUQKQA4',
'a2o1C000005YUQLQA4',
'a2o1C000005YUQRQA4',
'a2o1C000005YUQSQA4',
'a2o1C000005YUQTQA4',
'a2o1C000005YUQUQA4',
'a2o1C000005YUQVQA4',
'a2o1C000005YUQbQAO',
'a2o1C000005YUQcQAO',
'a2o1C000005YUQdQAO',
'a2o1C000005YUQeQAO',
'a2o1C000005YUQfQAO',
'a2o1C000005YUQlQAO',
'a2o1C000005YUQmQAO',
'a2o1C000005YUQpQAO',
'a2o1C000005YUQvQAO',
'a2o1C000005YUQwQAO',
'a2o1C000005YUQyQAO',
'a2o1C000005YUQzQAO',
'a2o1C000005YUR5QAO',
'a2o1C000005YUR6QAO',
'a2o1C000005YUR7QAO',
'a2o1C000005YUR8QAO',
'a2o1C000005YUR9QAO',
'a2o1C000005YURFQA4',
'a2o1C000005YURGQA4',
'a2o1C000005YURHQA4',
'a2o1C000005YURIQA4',
'a2o1C000005YURJQA4',
'a2o1C000005YURPQA4',
'a2o1C000005YURQQA4',
'a2o1C000005YURRQA4',
'a2o1C000005YURSQA4',
'a2o1C000005YURTQA4',
'a2o1C000005YURZQA4',
'a2o1C000005YURbQAO',
'a2o1C000005YURcQAO',
'a2o1C000005YURdQAO',
'a2o1C000005YURjQAO',
'a2o1C000005YURkQAO',
'a2o1C000005YURlQAO',
'a2o1C000005YURmQAO',
'a2o1C000005YURnQAO',
'a2o1C000005YURtQAO',
'a2o1C000005YUOgQAO',
'a2o1C000005YUOhQAO',
'a2o1C000005YUOiQAO',
'a2o1C000005YUOkQAO',
'a2o1C000005YUOlQAO',
'a2o1C000005YUOmQAO',
'a2o1C000005YUOnQAO',
'a2o1C000005YUOoQAO',
'a2o1C000005YUOuQAO',
'a2o1C000005YUOvQAO',
'a2o1C000005YUOwQAO',
'a2o1C000005YUOxQAO',
'a2o1C000005YUOyQAO',
'a2o1C000005YUP4QAO',
'a2o1C000005YUP5QAO',
'a2o1C000005YUP6QAO',
'a2o1C000005YUP7QAO',
'a2o1C000005YUP8QAO',
'a2o1C000005YUPEQA4',
'a2o1C000005YUPFQA4',
'a2o1C000005YUPGQA4',
'a2o1C000005YUPHQA4',
'a2o1C000005YUPIQA4',
'a2o1C000005YUPOQA4',
'a2o1C000005YUPPQA4',
'a2o1C000005YUPQQA4',
'a2o1C000005YUPRQA4',
'a2o1C000005YUPSQA4',
'a2o1C000005YUPYQA4',
'a2o1C000005YUPaQAO',
'a2o1C000005YUPbQAO',
'a2o1C000005YUUmQAO',
'a2o1C000005YUUsQAO',
'a2o1C000005YUUtQAO',
'a2o1C000005YUUuQAO',
'a2o1C000005YUUvQAO',
'a2o1C000005YUUwQAO',
'a2o1C000005YUV2QAO',
'a2o1C000005YUV3QAO',
'a2o1C000005YUV4QAO',
'a2o1C000005YUV5QAO',
'a2o1C000005YUV6QAO',
'a2o1C000005YUTTQA4',
'a2o1C000005YUTUQA4',
'a2o1C000005YUTSQA4',
'a2o1C000005YUTaQAO',
'a2o1C000005YUTbQAO',
'a2o1C000005YUTcQAO',
'a2o1C000005YUTdQAO',
'a2o1C000005YUTeQAO',
'a2o1C000005YUTkQAO',
'a2o1C000005YUTlQAO',
'a2o1C000005YUTmQAO',
'a2o1C000005YUTnQAO',
'a2o1C000005YUToQAO',
'a2o1C000005YUTuQAO',
'a2o1C000005YUTvQAO',
'a2o1C000005YUTwQAO',
'a2o1C000005YUTxQAO',
'a2o1C000005YUTyQAO',
'a2o1C000005YUU4QAO',
'a2o1C000005YUU5QAO',
'a2o1C000005YUU6QAO',
'a2o1C000005YUU7QAO',
'a2o1C000005YUU8QAO',
'a2o1C000005YUUEQA4',
'a2o1C000005YUUFQA4',
'a2o1C000005YURuQAO',
'a2o1C000005YURvQAO',
'a2o1C000005YURyQAO',
'a2o1C000005YURzQAO',
'a2o1C000005YUS0QAO',
'a2o1C000005YUS1QAO',
'a2o1C000005YUS2QAO',
'a2o1C000005YUS8QAO',
'a2o1C000005YUS9QAO',
'a2o1C000005YUSAQA4',
'a2o1C000005YUSBQA4',
'a2o1C000005YUSCQA4',
'a2o1C000005YUSIQA4',
'a2o1C000005YUSJQA4',
'a2o1C000005YUSKQA4',
'a2o1C000005YUSLQA4',
'a2o1C000005YUSMQA4',
'a2o1C000005YUSSQA4',
'a2o1C000005YUS... [truncated]
