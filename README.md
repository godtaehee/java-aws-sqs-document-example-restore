# java-aws-sqs-document-example-restore

AWS doesn't update their [offical docs](https://docs.aws.amazon.com/AWSSimpleQueueService/latest/SQSDeveloperGuide/sqs-throughput-horizontal-scaling-and-batching.html) about SQS SDK Example.

MessageGroupId is necessary when we send a message to SQS. [You can refer message Group Id on Github docs link](https://github.com/awsdocs/amazon-sqs-developer-guide/blob/main/doc_source/using-messagegroupid-property.md)

But In above doc's example, there is no groupId which is builded in sendMessageRequest Object.

So I refer to many reference and I fix it.

The following links are my reference to help fix this issue.

### Reference

[Managing Amazon SQS Queues in Java](https://www.baeldung.com/aws-queues-java)
[AWS S3 with Java](https://www.baeldung.com/aws-s3-java)
[AWS SQS FIFO Queue: The queue should either have ContentBasedDeduplication enabled or MessageDeduplicationId provided explicitly?](https://stackoverflow.com/questions/62655047/aws-sqs-fifo-queue-the-queue-should-either-have-contentbaseddeduplication-enabl)

