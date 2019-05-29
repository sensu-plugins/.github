# Security Policy

## Supported Versions

We support all versions of [non EOL rubies](https://docs.sensu.io/plugins/1.0/faq/#what-is-the-policy-on-supporting-end-of-life-eol-ruby-versions) and other respective languages. That being said we typically only roll forward on the latest major release version unless there is something truly horrifying. For information on [how we version](https://github.com/sensu-plugins/community/blob/master/HOW_WE_VERSION.md)

## Reporting a Vulnerability

Not all issues are equal and we understand that; currently we do not have a public program beyond github issues and pull requests. If you feel the issue is sensitive enough that it requires private disclosure please get in touch with Ben Abrams via [email](mailto:me@benabrams.it) or contact him through his [website](https://benabrams.it/contact/). There is no guarantee you will recieve any bounty and is currently at the discretion of the maintainers and the community. We would evcentually like to pay for bounties 

Things to consider before submitting an issue:
- Does this require private disclosure due to high impact and low effort to exploit?
- Has this been reported on the specific plugin repo or the [community repo](https://github.com/sensu-plugins/community/issues)?
- Does it relate to an existing CVE? Does this require a new CVE?
- Does this affect all plugins or a single plugin? If all plugins please raise the issue on the [community](https://github.com/sensu-plugins/community)
- How does this impact a user? Development only dependencies for example will have lower impact as they will not be called during the runtime of the process

Material to review prior to submitting:
- [Pull Request Process](https://github.com/sensu-plugins/community/blob/master/PULL_REQUEST_PROCESS.md)
- [How we communicate change](https://github.com/sensu-plugins/community/blob/master/HOW_WE_CHANGELOG.md) and [how we version](https://github.com/sensu-plugins/community/blob/master/HOW_WE_VERSION.md)


Thank you for all your hard work to make the world more secure!
