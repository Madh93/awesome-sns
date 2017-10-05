# Awesome Sns [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of useful SNS topics, tools, and articles


## Contents

- [AWS Owned Topics](#aws-owned-topics)
    - [Pricing Topics](#pricing-topics)
    - [AMI Topics](#ami-topics)
    - [Dataset Topics](#dataset-topics)
- [Community Topics](#community-topics)
- [SNS Tools](#sns-tools)
- [SNS Articles](#sns-articles)


## AWS Owned Topics

These are topics owned and updated by AWS.

### General Topics

| Name | Topic | Example |
| ---- | ----- | ------- |
|[IP Ranges](http://docs.aws.amazon.com/general/latest/gr/aws-ip-ranges.html)| `arn:aws:sns:us-east-1:806199016981:AmazonIpSpaceChanged`| |
| [Price Change SNS](http://docs.aws.amazon.com/awsaccountbilling/latest/aboutv2/price-notification.html)| `arn:aws:sns:us-east-1:278350005181:price-list-api`| |
| [Daily Aggregated Price Change SNS](http://docs.aws.amazon.com/awsaccountbilling/latest/aboutv2/price-notification.html)| `arn:aws:sns:us-east-1:278350005181:daily-aggregated-price-list-api`| ||

### AMI Topics
| Name | Topic | Example |
| ---- | ----- | ------- |
|[Amazon Linux AMI Updates](https://aws.amazon.com/amazon-linux-ami/) | `arn:aws:sns:us-east-1:137112412989:amazon-linux-ami-updates` ||
|[EC2 Windows AMI Updates](http://docs.aws.amazon.com/AWSEC2/latest/WindowsGuide/windows-ami-version-history.html)| `arn:aws:sns:us-east-1:801119661308:ec2-windows-ami-update`||
|[EC2 Windows AMI Deletes](http://docs.aws.amazon.com/AWSEC2/latest/WindowsGuide/windows-ami-version-history.html)| `arn:aws:sns:us-east-1:801119661308:ec2-windows-ami-private`||
|[ECS Optimized AMI Updates](http://docs.aws.amazon.com/AmazonECS/latest/developerguide/ECS-AMI-SubscribeTopic.html)| `arn:aws:sns:us-east-1:177427601217:ecs-optimized-amazon-ami-update`|||

### Dataset Topics
| Name | Topic | Example |
| ---- | ----- | ------- |
| [GDELT](https://aws.amazon.com/public-datasets/gdelt/) | `arn:aws:sns:us-east-1:928094251383:gdelt-csv`| [S3 Event](http://docs.aws.amazon.com/AmazonS3/latest/dev/notification-content-structure.html) |
| [HIRLAM Weather Model](https://aws.amazon.com/public-datasets/fmi-hirlam/) | <ul><li>`arn:aws:sns:eu-west-1:916174725480:new-fmi-opendata-rcrhirlam-surface-grib`</li><li>`arn:aws:sns:eu-west-1:916174725480:new-fmi-opendata-rcrhirlam-pressure-grib`</li></ul>| [S3 Event](http://docs.aws.amazon.com/AmazonS3/latest/dev/notification-content-structure.html) |
| [NEXRAD](https://aws.amazon.com/public-datasets/nexrad/) | <ul><li>`arn:aws:sns:us-east-1:684042711724:NewNEXRADLevel2Object`</li><li>`arn:aws:sns:us-east-1:811054952067:NewNEXRADLevel2Archive`</li></ul>| [S3 Event](http://docs.aws.amazon.com/AmazonS3/latest/dev/notification-content-structure.html) |
| [MODIS](https://aws.amazon.com/public-datasets/modis/) | `arn:aws:sns:us-west-2:552188055668:New_MODIS_Scene` | [S3 Event](http://docs.aws.amazon.com/AmazonS3/latest/dev/notification-content-structure.html) |
| [Open Street Map](https://aws.amazon.com/public-datasets/osm/) | `arn:aws:sns:us-east-1:800218804198:New_File` | [S3 Event](http://docs.aws.amazon.com/AmazonS3/latest/dev/notification-content-structure.html) |
| [GOES-R Series](https://aws.amazon.com/public-datasets/goes/) | `arn:aws:sns:us-east-1:123901341784:NewGOES16Object`| [S3 Event](http://docs.aws.amazon.com/AmazonS3/latest/dev/notification-content-structure.html) |
|[Sentinel-2](https://aws.amazon.com/public-datasets/sentinel-2/)| `arn:aws:sns:eu-west-1:214830741341:NewSentinel2Product` | [S3 Event](http://docs.aws.amazon.com/AmazonS3/latest/dev/notification-content-structure.html) |
| [Landsat](https://aws.amazon.com/public-datasets/landsat/)|`arn:aws:sns:us-west-2:274514004127:NewSceneHTML`|[S3 Event](http://docs.aws.amazon.com/AmazonS3/latest/dev/notification-content-structure.html) |

## Community Topics

| Name | Topic | Example |
| ---- | ----- | ------- |
| [ADD SOMETHING](https://github.com/ranman/awesome-sns/edit/master/README.md) | | ||


## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.


## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, Randall Hunt has waived all copyright and
related or neighboring rights to this work.
