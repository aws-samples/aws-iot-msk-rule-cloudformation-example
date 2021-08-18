## Integrating AWS IoT Core rules with Amazon Managed Streaming for Apache Kafka (MSK)

This repository include sample CloudFormation templates demonstrating AWS IoT Core rule action integration with Amazon MSK.

For sake of completness, the root stack creates all required resources, such as: Amazon Virtual Private Cloud (Amazon VPC), Amazon MSK cluster, AWS IoT Core rule, AWS Secrets Manager, AWS Identity and Access Management (IAM).

To create all resources use the root.yaml template. It is possible to use each template seperatly, giving your existing resources as input to the relevant template.

This example can be used as a starting point for production grade solution deployment.

## Security

See [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) for more information.

## License

This library is licensed under the MIT-0 License. See the LICENSE file.

