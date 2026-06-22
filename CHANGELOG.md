# Changelog

## [9.0.0](https://github.com/bradms98/terraform-modules/compare/v8.20.1...v9.0.0) (2026-06-22)


### ⚠ BREAKING CHANGES

* **dhcp_options_set:** multi-VPC support, netbios, and output fix ([#199](https://github.com/bradms98/terraform-modules/issues/199))
* flow logs and tgw attachment were not working properly
    - Fixed tgw attachments from creating multiple attachments
    - Updated the `flow_logs` module to create multiple flow logs based on the inputs as lists
    - Updated the `flow_logs` module ID variables to be plural
* 

### bugfix

* fix flow logs and tgw attachment ([#94](https://github.com/bradms98/terraform-modules/issues/94)) ([b73470d](https://github.com/bradms98/terraform-modules/commit/b73470dabdfdd48ed5d47aac074fc1e1887731ac))


### Features

* add AWS Budgets budget module (DEVSECOPS-30) ([#223](https://github.com/bradms98/terraform-modules/issues/223)) ([21c9663](https://github.com/bradms98/terraform-modules/commit/21c96630dfb1ab98cb87dd43521ceba05c852b4a))
* add AWS Config organization module (DEVSECOPS-32) ([#225](https://github.com/bradms98/terraform-modules/issues/225)) ([bd9036d](https://github.com/bradms98/terraform-modules/commit/bd9036daad8b391e4a3865f844e0e798e4802d14))
* add CloudWatch logging to transfer_family module ([#186](https://github.com/bradms98/terraform-modules/issues/186)) ([430b86c](https://github.com/bradms98/terraform-modules/commit/430b86c4761d113a1af9efd9845aa4a580a64c94))
* Add deletion protection support for CloudWatch log groups in flow_logs module ([#180](https://github.com/bradms98/terraform-modules/issues/180)) ([a6c5a0c](https://github.com/bradms98/terraform-modules/commit/a6c5a0cf57fb15c80b81f0b92a1c7359014adcaf))
* add ECR module ([#143](https://github.com/bradms98/terraform-modules/issues/143)) ([2926be0](https://github.com/bradms98/terraform-modules/commit/2926be06808bbbae77f89170b3a5dd7a31eb7049))
* add iam/access_analyzer module (DEVSECOPS-36) ([#224](https://github.com/bradms98/terraform-modules/issues/224)) ([390ab6d](https://github.com/bradms98/terraform-modules/commit/390ab6d476a39df2f14a778431cae0884ab1eb94))
* add invisible unicode character CI check ([#239](https://github.com/bradms98/terraform-modules/issues/239)) ([e93177c](https://github.com/bradms98/terraform-modules/commit/e93177c5f82da827b6c9518f55d11e4d76db1969))
* add s3/access_log_bucket module (DEVSECOPS-37) ([#222](https://github.com/bradms98/terraform-modules/issues/222)) ([edac0a6](https://github.com/bradms98/terraform-modules/commit/edac0a650c955c0104e05fdb66052db21acdbacb))
* add Zscaler ZPA App Connector vendor module ([#208](https://github.com/bradms98/terraform-modules/issues/208)) ([c0215ab](https://github.com/bradms98/terraform-modules/commit/c0215ab0ffcf414146971b7f887b4af232886d8e))
* added bucket_ownership controls to s3 bucket ([#130](https://github.com/bradms98/terraform-modules/issues/130)) ([e5c0889](https://github.com/bradms98/terraform-modules/commit/e5c0889f415d2d0c8e7f82c6159a66a54c411e97))
* added cloudfront example to readme.md ([#79](https://github.com/bradms98/terraform-modules/issues/79)) ([109532b](https://github.com/bradms98/terraform-modules/commit/109532b197175344491d54669c780529c3d8babd))
* added ecr vpc endpoints ([#146](https://github.com/bradms98/terraform-modules/issues/146)) ([7932fff](https://github.com/bradms98/terraform-modules/commit/7932fff0254d1e7cbd33577f3fb9b8b9bd338e92))
* adopt OpenTofu as default tool, retain Terraform support ([#240](https://github.com/bradms98/terraform-modules/issues/240)) ([eb1f726](https://github.com/bradms98/terraform-modules/commit/eb1f726da9539bf3db33d4a028cacb06ac22095e))
* **athena/workgroup:** add new Athena workgroup module ([#194](https://github.com/bradms98/terraform-modules/issues/194)) ([73ce7e3](https://github.com/bradms98/terraform-modules/commit/73ce7e3db3ec65498c42d4166e853d2eeb418022))
* **automation:** Oz-powered issue → spec → implementation pipeline ([#207](https://github.com/bradms98/terraform-modules/issues/207)) ([99a0351](https://github.com/bradms98/terraform-modules/commit/99a035105388f2ded5957fb1a4cc2b21d34f854d))
* AWS Amplify - SNS Build Notifications via EventBridge ([#124](https://github.com/bradms98/terraform-modules/issues/124)) ([9919c8f](https://github.com/bradms98/terraform-modules/commit/9919c8f8e80e30959284a1b95d91b6fb96becb63))
* AWS Backups organization management ([#133](https://github.com/bradms98/terraform-modules/issues/133)) ([7c21357](https://github.com/bradms98/terraform-modules/commit/7c213577246490415e54d3abe1cfde3506160d35))
* **cloud_wan:** new AWS Cloud WAN module suite for tunnel-less SD-WAN connectivity ([#100](https://github.com/bradms98/terraform-modules/issues/100)) ([eac5dec](https://github.com/bradms98/terraform-modules/commit/eac5dec9091f3781057045b2f0bf2af0b5b21820))
* cloudformation stack module ([#151](https://github.com/bradms98/terraform-modules/issues/151)) ([39f669d](https://github.com/bradms98/terraform-modules/commit/39f669dd711b8e885a5c7a381cb83da4541f2e34))
* **cloudformation/stack_set:** add stack_set_instance_region variable to stack set instance ([#316](https://github.com/bradms98/terraform-modules/issues/316)) ([da78e71](https://github.com/bradms98/terraform-modules/commit/da78e714646661e768754ce74df9434300b8abfe))
* **cloudfront:** add native Origin Access Control (OAC) management to the cloudfront module ([#278](https://github.com/bradms98/terraform-modules/issues/278)) ([af73731](https://github.com/bradms98/terraform-modules/commit/af737314dec4a09a38d6e9d495522a3374618b8a))
* **dhcp_options_set:** multi-VPC support, netbios, and output fix ([#199](https://github.com/bradms98/terraform-modules/issues/199)) ([e3cc3ac](https://github.com/bradms98/terraform-modules/commit/e3cc3ac03ba6b8288e125f18e672e9b92c90e7b8))
* **iam:** add policy name lookup to user_policy_attachment ([#301](https://github.com/bradms98/terraform-modules/issues/301)) ([422e714](https://github.com/bradms98/terraform-modules/commit/422e714661c013591d64cbfad9b50ed88dc40c48))
* **identity_center:** add group_memberships output and make groups description optional ([#279](https://github.com/bradms98/terraform-modules/issues/279)) ([5479839](https://github.com/bradms98/terraform-modules/commit/5479839dec9cf927aba3a4dbe405f7a50729f8bf))
* kms module chainable from other modules ([#141](https://github.com/bradms98/terraform-modules/issues/141)) ([99f42d1](https://github.com/bradms98/terraform-modules/commit/99f42d1b6bf2733fbceb085c159f4a64b609e91a))
* Module - AWS IPAM (modules/aws/ipam) ([#274](https://github.com/bradms98/terraform-modules/issues/274)) ([f50d7d8](https://github.com/bradms98/terraform-modules/commit/f50d7d88df4798cc5d502eb6ec86ce6fffa0656a))
* **organizations/organization:** add default SCP denying sso:CreateInstance in member accounts ([#269](https://github.com/bradms98/terraform-modules/issues/269)) ([dd18c28](https://github.com/bradms98/terraform-modules/commit/dd18c286fd1009570b8cf366ccea8dc3dbae805d))
* route tables are able to be disabled ([#82](https://github.com/bradms98/terraform-modules/issues/82)) ([12363a5](https://github.com/bradms98/terraform-modules/commit/12363a59cf7b39040be8d90f45b4fb45cf525244))
* route_table_ids pluralized ([#83](https://github.com/bradms98/terraform-modules/issues/83)) ([80308d8](https://github.com/bradms98/terraform-modules/commit/80308d841be968bb92eeb1eecd455181e15207ad))
* **route53/registered_domain:** add billing_contact and billing_privacy ([#200](https://github.com/bradms98/terraform-modules/issues/200)) ([ef25c5b](https://github.com/bradms98/terraform-modules/commit/ef25c5b2a4e94b6f62d03fd8623106e435918384))
* **s3:** Add configurable SSL/HTTPS enforcement for S3 buckets ([#184](https://github.com/bradms98/terraform-modules/issues/184)) ([a029d1b](https://github.com/bradms98/terraform-modules/commit/a029d1be40fe22ede4aa67e343af875c63575d0c))
* **s3:** modernize bucket server-side encryption options ([#305](https://github.com/bradms98/terraform-modules/issues/305)) ([a1bba3d](https://github.com/bradms98/terraform-modules/commit/a1bba3d423431c1411ad7388b6957ccd1078cf00))
* **scalr:** add workspace hooks support ([#197](https://github.com/bradms98/terraform-modules/issues/197)) ([a2e3e2a](https://github.com/bradms98/terraform-modules/commit/a2e3e2aaf1751874bef463415359409d8729882c))
* **waf:** new AWS WAFv2 module ([#144](https://github.com/bradms98/terraform-modules/issues/144)) ([6188539](https://github.com/bradms98/terraform-modules/commit/61885390ab5da3ed7b3c21081f115ad2d59c121b))
* **waf:** Phase 1 — non-breaking compliance improvements ([c5b6591](https://github.com/bradms98/terraform-modules/commit/c5b659134a015928127c4a7eef2985450d65eda6))


### Bug Fixes

* **amplify:** replace deprecated data.aws_region.current.id with .region ([#309](https://github.com/bradms98/terraform-modules/issues/309)) ([190f2da](https://github.com/bradms98/terraform-modules/commit/190f2daf6ef1f532c141c783ef11266ec6d040fa))
* **automation:** open Oz-authored PRs ready-for-review ([d066c05](https://github.com/bradms98/terraform-modules/commit/d066c058cdd3e42d673ab6a7a6eaa0be482ad766))
* **automation:** open Oz-authored PRs ready-for-review ([#214](https://github.com/bradms98/terraform-modules/issues/214)) ([d066c05](https://github.com/bradms98/terraform-modules/commit/d066c058cdd3e42d673ab6a7a6eaa0be482ad766))
* **automation:** remove labeled trigger from issue-triage; guard bot-edited events ([#245](https://github.com/bradms98/terraform-modules/issues/245)) ([8af70c9](https://github.com/bradms98/terraform-modules/commit/8af70c9d8eea2e7e1ebc425ff33bac1cb59cbc3e))
* **automation:** restore Oz pipeline cascade; correct gh api field ([24ab182](https://github.com/bradms98/terraform-modules/commit/24ab182995023af1c6d2669b9dc03e215a44b197)), closes [#206](https://github.com/bradms98/terraform-modules/issues/206)
* **automation:** restore Oz pipeline cascade; correct gh api field ([#211](https://github.com/bradms98/terraform-modules/issues/211)) ([24ab182](https://github.com/bradms98/terraform-modules/commit/24ab182995023af1c6d2669b9dc03e215a44b197))
* **aws_backup:** use set(string) for organization_backup_plan for_each ([#323](https://github.com/bradms98/terraform-modules/issues/323)) ([a09502b](https://github.com/bradms98/terraform-modules/commit/a09502bafa95684d3f45ce9c646311ff0f9f1dc7))
* **aws/amplify:** suppress perpetual basic_auth_credentials diff via lifecycle.ignore_changes ([#288](https://github.com/bradms98/terraform-modules/issues/288)) ([73acff0](https://github.com/bradms98/terraform-modules/commit/73acff0fb3e0d3e45aa3322baadcf10b9d94234c))
* **aws/athena/workgroup:** add Trivy suppression for caller-controlled encryption (AVD-AWS-0006) ([#249](https://github.com/bradms98/terraform-modules/issues/249)) ([e40bc77](https://github.com/bradms98/terraform-modules/commit/e40bc77460cee94b8d31793d10850c295cb625ac))
* **aws/cloudtrail:** remove invalid empty filter {} from lifecycle rule ([#232](https://github.com/bradms98/terraform-modules/issues/232)) ([4fae6c9](https://github.com/bradms98/terraform-modules/commit/4fae6c98e89e42d4ae8eeabd43c0c45edd9b1d0e))
* **ci:** pin scan workflow actions to commit SHAs ([#204](https://github.com/bradms98/terraform-modules/issues/204)) ([9d7ba10](https://github.com/bradms98/terraform-modules/commit/9d7ba1098cebf8882f13e974e38fd910ad479109))
* **ci:** resolve CHECKOV, TRIVY, and SPELL_CODESPELL linter failures ([#185](https://github.com/bradms98/terraform-modules/issues/185)) ([a37935b](https://github.com/bradms98/terraform-modules/commit/a37935b75efdf65b72cfc78f3827681f72f34f85))
* **cloudtrail:** add DenyHTTP statement to S3 bucket policy ([#188](https://github.com/bradms98/terraform-modules/issues/188)) ([72fe99a](https://github.com/bradms98/terraform-modules/commit/72fe99a0e720a61b0e95d713ad4ebf193d49f8a1))
* correct directory_service_simple_ad module to use vpc_settings ([#192](https://github.com/bradms98/terraform-modules/issues/192)) ([50febcb](https://github.com/bradms98/terraform-modules/commit/50febcb5fe23e33aea98f53394feb2cddc36f262))
* correct terraform-docs auto-commit guidance in skill and AGENTS.md ([#293](https://github.com/bradms98/terraform-modules/issues/293)) ([3d5e186](https://github.com/bradms98/terraform-modules/commit/3d5e186e8e23f92334c7d5e73f070c7dcb7bdd57))
* **guardduty/organization:** bump AWS provider to &gt;= 6.0.0 and update README ([#251](https://github.com/bradms98/terraform-modules/issues/251)) ([d096f52](https://github.com/bradms98/terraform-modules/commit/d096f52c4720658e8aefa949a809747dd7de663c))
* **issue-triage:** instruct users to edit issue body on needs-info ([#247](https://github.com/bradms98/terraform-modules/issues/247)) ([698d7c2](https://github.com/bradms98/terraform-modules/commit/698d7c2c49ba1fed1508340ed448dd63659560b0))
* **s3/bucket:** collapse multi-line policy ternary to single line ([#205](https://github.com/bradms98/terraform-modules/issues/205)) ([f61afde](https://github.com/bradms98/terraform-modules/commit/f61afdecd40a9ddff4305dfddde81b09f09ea2ac))
* **terraform/workspace:** manage execution_mode via tfe_workspace_settings ([#275](https://github.com/bradms98/terraform-modules/issues/275)) ([bb85a33](https://github.com/bradms98/terraform-modules/commit/bb85a33371d3ce45f4c4ba5dabe59d01fa7ae811))

## [8.20.1](https://github.com/zachreborn/terraform-modules/compare/v8.20.0...v8.20.1) (2026-06-16)


### Bug Fixes

* **aws_backup:** use set(string) for organization_backup_plan for_each ([#323](https://github.com/zachreborn/terraform-modules/issues/323)) ([a09502b](https://github.com/zachreborn/terraform-modules/commit/a09502bafa95684d3f45ce9c646311ff0f9f1dc7))

## [8.20.0](https://github.com/zachreborn/terraform-modules/compare/v8.19.1...v8.20.0) (2026-06-15)


### Features

* **cloudformation/stack_set:** add stack_set_instance_region variable to stack set instance ([#316](https://github.com/zachreborn/terraform-modules/issues/316)) ([da78e71](https://github.com/zachreborn/terraform-modules/commit/da78e714646661e768754ce74df9434300b8abfe))

## [8.19.1](https://github.com/zachreborn/terraform-modules/compare/v8.19.0...v8.19.1) (2026-06-14)


### Bug Fixes

* **amplify:** replace deprecated data.aws_region.current.id with .region ([#309](https://github.com/zachreborn/terraform-modules/issues/309)) ([190f2da](https://github.com/zachreborn/terraform-modules/commit/190f2daf6ef1f532c141c783ef11266ec6d040fa))

## [8.19.0](https://github.com/zachreborn/terraform-modules/compare/v8.18.0...v8.19.0) (2026-06-14)


### Features

* **s3:** modernize bucket server-side encryption options ([#305](https://github.com/zachreborn/terraform-modules/issues/305)) ([a1bba3d](https://github.com/zachreborn/terraform-modules/commit/a1bba3d423431c1411ad7388b6957ccd1078cf00))

## [8.18.0](https://github.com/zachreborn/terraform-modules/compare/v8.17.0...v8.18.0) (2026-06-14)


### Features

* **iam:** add policy name lookup to user_policy_attachment ([#301](https://github.com/zachreborn/terraform-modules/issues/301)) ([422e714](https://github.com/zachreborn/terraform-modules/commit/422e714661c013591d64cbfad9b50ed88dc40c48))

## [8.17.0](https://github.com/zachreborn/terraform-modules/compare/v8.16.0...v8.17.0) (2026-06-14)


### Features

* add Zscaler ZPA App Connector vendor module ([#208](https://github.com/zachreborn/terraform-modules/issues/208)) ([c0215ab](https://github.com/zachreborn/terraform-modules/commit/c0215ab0ffcf414146971b7f887b4af232886d8e))
* **identity_center:** add group_memberships output and make groups description optional ([#279](https://github.com/zachreborn/terraform-modules/issues/279)) ([5479839](https://github.com/zachreborn/terraform-modules/commit/5479839dec9cf927aba3a4dbe405f7a50729f8bf))


### Bug Fixes

* **aws/amplify:** suppress perpetual basic_auth_credentials diff via lifecycle.ignore_changes ([#288](https://github.com/zachreborn/terraform-modules/issues/288)) ([73acff0](https://github.com/zachreborn/terraform-modules/commit/73acff0fb3e0d3e45aa3322baadcf10b9d94234c))
* correct terraform-docs auto-commit guidance in skill and AGENTS.md ([#293](https://github.com/zachreborn/terraform-modules/issues/293)) ([3d5e186](https://github.com/zachreborn/terraform-modules/commit/3d5e186e8e23f92334c7d5e73f070c7dcb7bdd57))

## Changelog

All notable changes to this repository are documented in this file.

From `v8.16.0` onward this file is maintained automatically by
[release-please](https://github.com/googleapis/release-please) from
[Conventional Commit](https://www.conventionalcommits.org/) history: each
qualifying merge to `main` updates the open **Release PR**, and merging that PR
cuts the next `vX.Y.Z` tag and publishes the GitHub Release. Do not edit past
release entries by hand — release-please prepends new entries on each release.

For the release/versioning rules (bump mapping, tag prefix, milestone
reconciliation, and the manual fallback), see
[`AGENTS.md` § Release & Tag Strategy](./AGENTS.md#release--tag-strategy).

Releases tagged before this automation was introduced (up to and including
`v8.16.0`) are recorded in the
[GitHub Releases](https://github.com/zachreborn/terraform-modules/releases)
list rather than in this file.
