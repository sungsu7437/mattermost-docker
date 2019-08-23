Fork of mattermost-prod-app with AWS S3 for file storage support

forked from https://github.com/mattermost/mattermost-docker

If you use AWS S3 for file storage. You should configure it with following environment variables :
* `MM_DRIVER_NAME` : amazons3
* `MM_AMAZON_S3_BUCKET` : AWS s3 bucket name
* `MM_AMAZON_S3_REGION` : AWS region
* `MM_AMAZON_S3_ACCESS_KEY_ID` : AWS access key id
* `MM_AMAZON_S3_SECRET_ACCESS_KEY` : AWS secret access key
