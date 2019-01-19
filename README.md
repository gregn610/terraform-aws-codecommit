<!-- This file was automatically generated by the `build-harness`. Make all changes to `README.yaml` and run `make readme` to rebuild this file. -->
[![README Header][readme_header_img]][readme_header_link]

[![Slalom][logo]](https://slalom.com)

This modules creates a repo with direct updates to the master denied. Its has been a common DevOps process pattern to use the mainline model or trunk-based development <https://paulhammant.com/2013/04/05/what-is-trunk-based-development/,> however it is with experience that the optimal pattern is of short lived single activity feature branches, YMMV.
It's has been a common DevOps process pattern to use the mainline model 
or trunk-based development 
https://paulhammant.com/2013/04/05/what-is-trunk-based-development/, however 
it is with experience that the optimal pattern is of short lived single 
activity feature branches, YMMV.


![terraform-aws-codecommit](docs/slalom-logo.png)
Terraform module to provision an AWS [`Codecommit`](https://aws.amazon.com/codecommit/) CI/CD system.


---

To use this repo the expected behaviour is to branch when starting a new piece of work, for example.
[<img align="right" title="Share via Email" src="https://docs.cloudposse.com/images/ionicons/ios-email-outline-2.0.1-16x16-999999.svg"/>][share_email]
[<img align="right" title="Share on Google+" src="https://docs.cloudposse.com/images/ionicons/social-googleplus-outline-2.0.1-16x16-999999.svg" />][share_googleplus]
[<img align="right" title="Share on Facebook" src="https://docs.cloudposse.com/images/ionicons/social-facebook-outline-2.0.1-16x16-999999.svg" />][share_facebook]
[<img align="right" title="Share on Reddit" src="https://docs.cloudposse.com/images/ionicons/social-reddit-outline-2.0.1-16x16-999999.svg" />][share_reddit]
[<img align="right" title="Share on LinkedIn" src="https://docs.cloudposse.com/images/ionicons/social-linkedin-outline-2.0.1-16x16-999999.svg" />][share_linkedin]
[<img align="right" title="Share on Twitter" src="https://docs.cloudposse.com/images/ionicons/social-twitter-outline-2.0.1-16x16-999999.svg" />][share_twitter]
for example.
```cli
`git pull`
[![Terraform Open Source Modules](https://docs.cloudposse.com/images/terraform-open-source-modules.svg)][terraform_modules]

`git branch -b feature/JGW-121-Remove-Project-Managers`
```
It's 100% Open Source and licensed under the [APACHE2](LICENSE).

Push to your feature branch.
```cli
`git push -u origin feature/JGW-121-Remove-Project-Managers`
```



We literally have [*hundreds of terraform modules*][terraform_modules] that are Open Source and well-maintained. Check them out! 







## Details

Creates a group called developer to which the policy is attached.

```hcl
module "codecommit" {
  source     = "git::https://github.com/jameswoolfenden/terraform-aws-codecommit.git?ref=master"
}
```






## Makefile Targets
```
Available targets:

  help                                Help screen
  help/all                            Display help for all targets
  help/short                          This help short screen
  lint:
                              Lint terraform code

```
| --------------- | ----------- | :----: | :-----: | :------: |
| default_branch  | -           | string |    -    |   yes    |
| organization    | -           | string |    -    |   yes    |
| developer_group | An existing Iam Group to attach the policy permissions to | string | - | yes |
| repository_name | -           | string |    -    |   yes    |
| --------------- | ----------- |
## Finally

## Share the Love 

Like this project? Please give it a ★ on [our GitHub](https://github.com/jameswoolfenden/terraform-aws-codecommit)! (it helps us **a lot**) 

Are you using this project or any of our other projects? Consider [leaving a testimonial][testimonial]. =)
```cli

## Related Projects

Check out these related projects.

`git config --global credential.helper '!aws codecommit credential-helper $@'`

`git config --global credential.UseHttpPath true`
```

## Help

**Got a question?**

And for SSH look at: <https://docs.aws.amazon.com/codecommit/latest/userguide/setting-up-ssh-unixes.html>

[![README Commercial Support][readme_commercial_support_img]][readme_commercial_support_link]

## Commercial Support

Work directly with our team of DevOps experts via email, slack, and video conferencing. 
```cli
We provide [*commercial support*][commercial_support] for all of our [Open Source][github] projects. As a *Dedicated Support* customer, you have access to our team of subject matter experts at a fraction of the cost of a full-time engineer. 
`publickey=$(<~/.ssh/codecommit.pub)`
[![E-Mail](https://img.shields.io/badge/email-hello@cloudposse.com-blue.svg)][email]

- **Questions.** We'll use a Shared Slack channel between your team and ours.
- **Troubleshooting.** We'll help you triage why things aren't working.
- **Code Reviews.** We'll review your Pull Requests and provide constructive feedback.
- **Bug Fixes.** We'll rapidly work to fix any bugs in our projects.
- **Build New Terraform Modules.** We'll [develop original modules][module_development] to provision infrastructure.
- **Cloud Architecture.** We'll assist with your cloud strategy and design.
- **Implementation.** We'll provide hands-on support to implement our reference architectures. 
`user=$(aws iam get-user --query 'User.UserName' --output text)`
```

## On Windows
## Terraform Module Development
```powershell
Are you interested in custom Terraform module development? Submit your inquiry using [our form][module_development] today and we'll get back to you ASAP.
`$publickey=get-content ~/.ssh/codecommit.pub`

## Slack Community
`$user=aws iam get-user --query 'User.UserName'`
Join our [Open Source Community][slack] on Slack. It's **FREE** for everyone! Our "SweetOps" community is where you get to talk with others who share a similar vision for how to rollout and manage infrastructure. This is the best place to talk shop, ask questions, solicit feedback, and work together as a community to build totally *sweet* infrastructure.
```
## Newsletter

Signup for [our newsletter][newsletter] that covers everything on our technology radar.  Receive updates on what we're up to on GitHub as well as awesome new projects we discover. 
```cli
`aws iam upload-ssh-public-key --user-name $user --ssh-public-key-body $publickey`

### Bug Reports & Feature Requests

Please use the [issue tracker](https://github.com/jameswoolfenden/terraform-aws-codecommit/issues) to report any bugs or file feature requests.

`SSHPublicKeyId=$(aws iam list-ssh-public-keys --user-name $user --query 'SSHPublicKeys[*].SSHPublicKeyId' --output text)`

In general, PRs are welcome. We follow the typical "fork-and-pull" Git workflow.

 1. **Fork** the repo on GitHub
 2. **Clone** the project to your own machine
 3. **Commit** changes to your own branch
 4. **Push** your work back up to your fork
 5. Submit a **Pull Request** so that we can review your changes

`$SSHPublicKeyId=(aws iam list-ssh-public-keys --user-name $user --query 'SSHPublicKeys[*].SSHPublicKeyId')|convertfrom-json`
```
## Copyright

Copyright © 2017-2019 [Cloud Posse, LLC](https://cpco.io/copyright)

$gitconfigupdate=@"
Host git-codecommit.*.amazonaws.com
## License 
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0) 
See [LICENSE](LICENSE) for full details.
    Licensed to the Apache Software Foundation (ASF) under one
    or more contributor license agreements.  See the NOTICE file
    distributed with this work for additional information
    regarding copyright ownership.  The ASF licenses this file
    to you under the Apache License, Version 2.0 (the
    "License"); you may not use this file except in compliance
    with the License.  You may obtain a copy of the License at
Add-content ~/.ssh/config \$gitconfigupdate

    Unless required by applicable law or agreed to in writing,
    software distributed under the License is distributed on an
    "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
    KIND, either express or implied.  See the License for the
    specific language governing permissions and limitations
    under the License.
## linux
```bash
cat << EOF > ~/.ssh/config Host git-codecommit.*.amazonaws.com User $SSHPublicKeyId IdentityFile ~/.ssh/codecommit EOF

## Trademarks
ssh-add codecommit
All other trademarks referenced herein are the property of their respective owners.
```
## About

`ssh git-codecommit.us-east-2.amazonaws.com`
```
[![Cloud Posse][logo]][website]
### Saml Auth?
[SAML](codecommitSAML.md)
We offer [paid support][commercial_support] on all of our projects.  
## Inputs
Check out [our other projects][github], [follow us on twitter][twitter], [apply for a job][jobs], or [hire us][hire] to help with your cloud strategy and implementation.
| Name | Description | Type | Default | Required |
|------|-------------|:----:|:-----:|:-----:|
| default_branch | The name of the default repository branch | string | `master` | no |
### Contributors
| repository_name | The name of your GIT repository | string | - | yes |
|  [![James Woolfenden][jameswoolfenden_avatar]][jameswoolfenden_homepage]<br/>[James Woolfenden][jameswoolfenden_homepage] |
|---|
## Outputs
  [jameswoolfenden_homepage]: https://github.com/jameswoolfenden
  [jameswoolfenden_avatar]: https://github.com/jameswoolfenden.png?size=150
| Name | Description |
|------|-------------|
| clone_url_https |  |
[![README Footer][readme_footer_img]][readme_footer_link]
[![Beacon][beacon]][website]
| clone_url_ssh |  |
  [logo]: https://cloudposse.com/logo-300x69.svg
  [docs]: https://cpco.io/docs
  [website]: https://cpco.io/homepage
  [github]: https://cpco.io/github
  [jobs]: https://cpco.io/jobs
  [hire]: https://cpco.io/hire
  [slack]: https://cpco.io/slack
  [linkedin]: https://cpco.io/linkedin
  [twitter]: https://cpco.io/twitter
  [testimonial]: https://cpco.io/leave-testimonial
  [newsletter]: https://cpco.io/newsletter
  [email]: https://cpco.io/email
  [commercial_support]: https://cpco.io/commercial-support
  [we_love_open_source]: https://cpco.io/we-love-open-source
  [module_development]: https://cpco.io/module-development
  [terraform_modules]: https://cpco.io/terraform-modules
  [readme_header_img]: https://cloudposse.com/readme/header/img?repo=jameswoolfenden/terraform-aws-codecommit
  [readme_header_link]: https://cloudposse.com/readme/header/link?repo=jameswoolfenden/terraform-aws-codecommit
  [readme_footer_img]: https://cloudposse.com/readme/footer/img?repo=jameswoolfenden/terraform-aws-codecommit
  [readme_footer_link]: https://cloudposse.com/readme/footer/link?repo=jameswoolfenden/terraform-aws-codecommit
  [readme_commercial_support_img]: https://cloudposse.com/readme/commercial-support/img?repo=jameswoolfenden/terraform-aws-codecommit
  [readme_commercial_support_link]: https://cloudposse.com/readme/commercial-support/link?repo=jameswoolfenden/terraform-aws-codecommit
  [share_twitter]: https://twitter.com/intent/tweet/?text=terraform-aws-codecommit&url=https://github.com/jameswoolfenden/terraform-aws-codecommit
  [share_linkedin]: https://www.linkedin.com/shareArticle?mini=true&title=terraform-aws-codecommit&url=https://github.com/jameswoolfenden/terraform-aws-codecommit
  [share_reddit]: https://reddit.com/submit/?url=https://github.com/jameswoolfenden/terraform-aws-codecommit
  [share_facebook]: https://facebook.com/sharer/sharer.php?u=https://github.com/jameswoolfenden/terraform-aws-codecommit
  [share_googleplus]: https://plus.google.com/share?url=https://github.com/jameswoolfenden/terraform-aws-codecommit
  [share_email]: mailto:?subject=terraform-aws-codecommit&body=https://github.com/jameswoolfenden/terraform-aws-codecommit
  [beacon]: https://ga-beacon.cloudposse.com/UA-76589703-4/jameswoolfenden/terraform-aws-codecommit?pixel&cs=github&cm=readme&an=terraform-aws-codecommit
