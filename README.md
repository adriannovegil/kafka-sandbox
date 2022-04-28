# Apache Kafka Sandbox

Get up and running a sandbox with Apache Kafka and ZooKeeper using Docker and Docker Compose

## Fast Run

Clone this repo and execute the following command:

```
make up
```

or, if you prefer

```
docker-compose up
```

## Services

The following services will be started. Some of them are accessible via web:

| Component           | Description                                              | Port                               |
| ------------------- | -------------------------------------------------------- | ---------------------------------- |
| `kfk-1`             | [Apache Kafka node 1](https://solr.apache.org/)          | [`20092`](http://localhost:20092/) |
| `kfk-2`             | [Apache Kafka node 2](https://solr.apache.org/)          | [`30092`](http://localhost:30092/) |
| `kfk-3`             | [Apache Kafka node 3](https://solr.apache.org/)          | [`40092`](http://localhost:40092/) |
| `zk-1`              | [ZooKeeper node 1](https://zookeeper.apache.org/)        | [`13181`](http://localhost:13181/) |
| `zk-2`              | [ZooKeeper node 2](https://zookeeper.apache.org/)        | [`23181`](http://localhost:23181/) |
| `zk-3`              | [ZooKeeper node 3](https://zookeeper.apache.org/)        | [`33181`](http://localhost:33181/) |

## Contributing

For a complete guide to contributing to the project, see the [Contribution Guide](CONTRIBUTING.md).

We welcome contributions of any kind including documentation, organization, tutorials, blog posts, bug reports, issues, feature requests, feature implementations, pull requests, answering questions on the forum, helping to manage issues, etc.

The project community and maintainers are very active and helpful, and the project benefits greatly from this activity.

### Reporting Issues

If you believe you have found a defect in the project or its documentation, use the repository issue tracker to report the problem to the project maintainers.

If you're not sure if it's a bug or not, start by asking in the discussion forum. When reporting the issue, please provide the version.

### Submitting Patches

The project welcomes all contributors and contributions regardless of skill or experience level.

If you are interested in helping with the project, we will help you with your contribution.

We want to create the best possible tool for our development teams and the best contribution experience for our developers, we have a set of guidelines which ensure that all contributions are acceptable.

The guidelines are not intended as a filter or barrier to participation. If you are unfamiliar with the contribution process, the team will help you and teach you how to bring your contribution in accordance with the guidelines.

For a complete guide to contributing, see the [Contribution Guide](CONTRIBUTING.md).

## Code of Conduct

See the [code-of-conduct.md](./code-of-conduct.md) file

## License

See the [LICENSE](./LICENSE) file
