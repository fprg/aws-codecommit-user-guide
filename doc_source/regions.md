# Regions and Git Connection Endpoints for AWS CodeCommit<a name="regions"></a>

Each AWS CodeCommit repository is associated with an AWS region\. AWS CodeCommit offers regional endpoints to make your requests to the service\. In addition, AWS CodeCommit provides Git connection endpoints for both SSH and HTTPS protocols in every region where AWS CodeCommit is available\. 

All the examples in this guide use the same endpoint URL for Git in US East \(Ohio\): `git-codecommit.us-east-2.amazonaws.com`\. However, when you use Git and configure your connections, make sure you choose the Git connection endpoint that matches the region that hosts your AWS CodeCommit repository\. For example, if you want to make a connection to a repository in US East \(N\. Virginia\), use the endpoint URL of `git-codecommit.us-east-1.amazonaws.com`\. This is also true for API calls\. When you make connections to an AWS CodeCommit repository with the AWS CLI or the SDKs, make sure you use the correct regional endpoint for the repository\.


+ [Supported Regions for AWS CodeCommit](#regions-acc)
+ [Git Connection Endpoints](#regions-git)
+ [Server Fingerprints for AWS CodeCommit](#regions-fingerprints)

## Supported Regions for AWS CodeCommit<a name="regions-acc"></a>

You can create and use AWS CodeCommit repositories in the following AWS regions:

+ US East \(Ohio\) 

+ US East \(N\. Virginia\)

+ US West \(Oregon\)

+ EU \(Ireland\)

+ Asia Pacific \(Tokyo\)

+ Asia Pacific \(Singapore\)

+ Asia Pacific \(Sydney\)

+ EU \(Frankfurt\)

+ Asia Pacific \(Seoul\)

+ South America \(São Paulo\)

+ US West \(N\. California\)

+ EU \(London\)

+ Asia Pacific \(Mumbai\)

+ Canada \(Central\)

For more information about regional endpoints for AWS CLI, service, and API calls to AWS CodeCommit, see [AWS Regions and Endpoints](http://docs.aws.amazon.com/general/latest/gr/rande.html#codecommit_region)\.

## Git Connection Endpoints<a name="regions-git"></a>

Use the following URLs when you configure Git connections to AWS CodeCommit repositories:


**Git connection endpoints for AWS CodeCommit**  

| Region Name | Region | Endpoint URL | Protocol | 
| --- | --- | --- | --- | 
| US East \(Ohio\) | us\-east\-2 | https://git\-codecommit\.us\-east\-2\.amazonaws\.com | HTTPS | 
| US East \(Ohio\) | us\-east\-2 | ssh://git\-codecommit\.us\-east\-2\.amazonaws\.com | SSH | 
| US East \(N\. Virginia\) | us\-east\-1 | https://git\-codecommit\.us\-east\-1\.amazonaws\.com | HTTPS | 
| US East \(N\. Virginia\) | us\-east\-1 | ssh://git\-codecommit\.us\-east\-1\.amazonaws\.com | SSH | 
| US West \(Oregon\) | us\-west\-2 | https://git\-codecommit\.us\-west\-2\.amazonaws\.com | HTTPS | 
| US West \(Oregon\) | us\-west\-2 | ssh://git\-codecommit\.us\-west\-2\.amazonaws\.com | SSH | 
| EU \(Ireland\) | eu\-west\-1 | https://git\-codecommit\.eu\-west\-1\.amazonaws\.com | HTTPS | 
| EU \(Ireland\) | eu\-west\-1 | ssh://git\-codecommit\.eu\-west\-1\.amazonaws\.com | SSH | 
| Asia Pacific \(Tokyo\) | ap\-northeast\-1 | https://git\-codecommit\.ap\-northeast\-1\.amazonaws\.com | HTTPS | 
| Asia Pacific \(Tokyo\) | ap\-northeast\-1 | ssh://git\-codecommit\.ap\-northeast\-1\.amazonaws\.com  | SSH | 
| Asia Pacific \(Singapore\) | ap\-southeast\-1 | https://git\-codecommit\.ap\-southeast\-1\.amazonaws\.com | HTTPS | 
| Asia Pacific \(Singapore\) | ap\-southeast\-1 | ssh://git\-codecommit\.ap\-southeast\-1\.amazonaws\.com  | SSH | 
| Asia Pacific \(Sydney\) | ap\-southeast\-2 | https://git\-codecommit\.ap\-southeast\-2\.amazonaws\.com | HTTPS | 
| Asia Pacific \(Sydney\) | ap\-southeast\-2 | ssh://git\-codecommit\.ap\-southeast\-2\.amazonaws\.com  | SSH | 
| EU \(Frankfurt\) | eu\-central\-1 | https://git\-codecommit\.eu\-central\-1\.amazonaws\.com | HTTPS | 
| EU \(Frankfurt\) | eu\-central\-1 | ssh://git\-codecommit\.eu\-central\-1\.amazonaws\.com  | SSH | 
| Asia Pacific \(Seoul\) | ap\-northeast\-2 | https://git\-codecommit\.ap\-northeast\-2\.amazonaws\.com | HTTPS | 
| Asia Pacific \(Seoul\) | ap\-northeast\-2 | ssh://git\-codecommit\.ap\-northeast\-2\.amazonaws\.com  | SSH | 
| South America \(São Paulo\) | sa\-east\-1 | https://git\-codecommit\.sa\-east\-1\.amazonaws\.com | HTTPS | 
| South America \(São Paulo\) | sa\-east\-1 | ssh://git\-codecommit\.sa\-east\-1\.amazonaws\.com  | SSH | 
| US West \(N\. California\) | us\-west\-1 | https://git\-codecommit\.us\-west\-1\.amazonaws\.com | HTTPS | 
| US West \(N\. California\) | us\-west\-1 | ssh://git\-codecommit\.us\-west\-1\.amazonaws\.com  | SSH | 
| EU \(London\) | eu\-west\-2 | https://git\-codecommit\.eu\-west\-2\.amazonaws\.com | HTTPS | 
| EU \(London\) | eu\-west\-2 | ssh://git\-codecommit\.eu\-west\-2\.amazonaws\.com  | SSH | 
| Asia Pacific \(Mumbai\) | ap\-south\-1 | https://git\-codecommit\.ap\-south\-1\.amazonaws\.com | HTTPS | 
| Asia Pacific \(Mumbai\) | ap\-south\-1 | ssh://git\-codecommit\.ap\-south\-1\.amazonaws\.com | SSH | 
| Canada \(Central\) | ca\-central\-1 | https://git\-codecommit\.ca\-central\-1\.amazonaws\.com | HTTPS | 
| Canada \(Central\) | ca\-central\-1 | ssh://git\-codecommit\.ca\-central\-1\.amazonaws\.com | SSH | 

## Server Fingerprints for AWS CodeCommit<a name="regions-fingerprints"></a>

The following table lists the public fingerprints for Git connection endpoints in AWS CodeCommit\. These server fingerprints are displayed as part of the verification process for adding an endpoint to your known hosts file\.


**Public fingerprints for AWS CodeCommit**  

| Server | Cryptographic hash type | Fingerprint | 
| --- | --- | --- | 
| git\-codecommit\.us\-east\-2\.amazonaws\.com | MD5 | a9:6d:03:ed:08:42:21:be:06:e1:e0:2a:d1:75:31:5e | 
| git\-codecommit\.us\-east\-2\.amazonaws\.com | SHA256 | 3lBlW2g5xn/NA2Ck6dyeJIrQOWvn7n8UEs56fG6ZIzQ | 
| git\-codecommit\.us\-east\-1\.amazonaws\.com | MD5 | a6:9c:7d:bc:35:f5:d4:5f:8b:ba:6f:c8:bc:d4:83:84 | 
| git\-codecommit\.us\-east\-1\.amazonaws\.com | SHA256 | eLMY1j0DKA4uvDZcl/KgtIayZANwX6t8\+8isPtotBoY | 
| git\-codecommit\.us\-west\-2\.amazonaws\.com | MD5 | a8:68:53:e3:99:ac:6e:d7:04:7e:f7:92:95:77:a9:77 | 
| git\-codecommit\.us\-west\-2\.amazonaws\.com | SHA256 | 0pJx9SQpkbPUAHwy58UVIq0IHcyo1fwCpOOuVgcAWPo | 
| git\-codecommit\.eu\-west\-1\.amazonaws\.com | MD5 | 93:42:36:ea:22:1f:f1:0f:20:02:4a:79:ff:ea:12:1d | 
| git\-codecommit\.eu\-west\-1\.amazonaws\.com | SHA256 | tKjRkOL8dmJyTmSbeSdN1S8F/f0iql3RlvqgTOP1UyQ | 
| git\-codecommit\.ap\-northeast\-1\.amazonaws\.com | MD5 | 8e:a3:f0:80:98:48:1c:5c:6f:59:db:a7:8f:6e:c6:cb | 
| git\-codecommit\.ap\-northeast\-1\.amazonaws\.com | SHA256 | Xk/WeYD/K/bnBybzhiuu4dWpBJtXPf7E30jHU7se4Ow | 
| git\-codecommit\.ap\-southeast\-1\.amazonaws\.com | MD5 | 65:e5:27:c3:09:68:0d:8e:b7:6d:94:25:80:3e:93:cf | 
| git\-codecommit\.ap\-southeast\-1\.amazonaws\.com | SHA256 | ZIsVa7OVzxrTIf\+Rk4UbhPv6Es22mSB3uTBojfPXIno | 
| git\-codecommit\.ap\-southeast\-2\.amazonaws\.com | MD5 | 7b:d2:c1:24:e6:91:a5:7b:fa:c1:0c:35:95:87:da:a0 | 
| git\-codecommit\.ap\-southeast\-2\.amazonaws\.com | SHA256 | nYp\+gHas80HY3DqbP4yanCDFhqDVjseefVbHEXqH2Ec | 
| git\-codecommit\.eu\-central\-1\.amazonaws\.com | MD5 | 74:5a:e8:02:fc:b2:9c:06:10:b4:78:84:65:94:22:2d | 
| git\-codecommit\.eu\-central\-1\.amazonaws\.com | SHA256 | MwGrkiEki8QkkBtlAgXbYt0hoZYBnZF62VY5RzGJEUY | 
| git\-codecommit\.ap\-northeast\-2\.amazonaws\.com | MD5 | 9f:68:48:9b:5f:fc:96:69:39:45:58:87:95:b3:69:ed | 
| git\-codecommit\.ap\-northeast\-2\.amazonaws\.com | SHA256 | eegAPQrWY9YsYo9ZHIKOmxetfXBHzAZd8Eya53Qcwko | 
| git\-codecommit\.sa\-east\-1\.amazonaws\.com | MD5 | 74:99:9d:ff:2b:ef:63:c6:4b:b4:6a:7f:62:c5:4b:51 | 
| git\-codecommit\.sa\-east\-1\.amazonaws\.com | SHA256 | kW\+VKB0jpRaG/ZbXkgbtMQbKgEDK7JnISV3SVoyCmzU | 
| git\-codecommit\.us\-west\-1\.amazonaws\.com | MD5 | 3b:76:18:83:13:2c:f8:eb:e9:a3:d0:51:10:32:e7:d1 | 
| git\-codecommit\.us\-west\-1\.amazonaws\.com | SHA256 | gzauWTWXDK2u5KuMMi5vbKTmfyerdIwgSbzYBODLpzg | 
| git\-codecommit\.eu\-west\-2\.amazonaws\.com | MD5 | a5:65:a6:b1:84:02:b1:95:43:f9:0e:de:dd:ed:61:d3 | 
| git\-codecommit\.eu\-west\-2\.amazonaws\.com | SHA256 | r0Rwz5k/IHp/QyrRnfiM9j02D5UEqMbtFNTuDG2hNbs | 
| git\-codecommit\.ap\-south\-1\.amazonaws\.com | MD5 | da:41:1e:07:3b:9e:76:a0:c5:1e:64:88:03:69:86:21 | 
| git\-codecommit\.ap\-south\-1\.amazonaws\.com | SHA256 | hUKwnTj7\+Xpx4Kddb6p45j4RazIJ4IhAMD8k29itOfE | 
| git\-codecommit\.ca\-central\-1\.amazonaws\.com | MD5 | 9f:7c:a2:2f:8c:b5:74:fd:ab:b7:e1:fd:af:46:ed:23 | 
| git\-codecommit\.ca\-central\-1\.amazonaws\.com | SHA256 | Qz5puafQdANVprLlj6r0Qyh4lCNsF6ob61dGcPtFS7w | 