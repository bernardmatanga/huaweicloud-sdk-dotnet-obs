Version 3.19.7
New Features:


Documentation & Demo:


Resolved Issues:
1. Fixed the null pointer issue of the API for downloading an object in asynchronous mode (ObsClient.EndGetObject).

-----------------------------------------------------------------------------------

Version 3.1.3
New Features:


Documentation & Demo:


Resolved Issues:
1. Modified ObsClient.PutObject to prevent upload issues when the Chunk mode is not supported by the server.

-----------------------------------------------------------------------------------

Version 3.1.2

New Features:
1. FunctionGraph configuration and query are supported in the bucket event notification APIs: ObsClient.SetBucketNotification and ObsClient.GetBucketNotification.

Documentation & Demo:
1. Added the description about FunctionGraph configuration to the event notification section in the Developer Guide.
	

Resolved Issues:
1. Fixed the issue that the bucket creation API ObsClient.CreateBucket returns incorrect error information due to protocol negotiation.
2. Rectified the error in the sample code BucketOperationsSample.cs.

