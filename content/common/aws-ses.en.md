---
author: ['Sherman Hui']
date: 1636319197
title: "aws ses"
description: "aws ses, CLI for AWS Simple Email Service."
categories: "common"
---
> High-scale inbound and outbound cloud email service.

> More information: <https://awscli.amazonaws.com/v2/documentation/api/latest/reference/ses/index.html>.

- Create a new receipt rule set:

```bash
aws ses create-receipt-rule-set --rule-set-name rule_set_name --generate-cli-skeleton
```

- Describe the active receipt rule set:

```bash
aws ses describe-active-receipt-rule-set --generate-cli-skeletion
```

- Describe a specific receipt rule:

```bash
aws ses describe-receipt-rule --rule-set-name rule_set_name --rule-name rule_name --generate-cli-skeleton
```

- List all receipt rule sets:

```bash
aws ses list-receipt-rule-sets --starting-token token_string --max-items integer --generate-cli-skeleton
```

- Delete a specific receipt rule set (the currently active rule set cannot be deleted):

```bash
aws ses delete-receipt-rule-set --rule-set-name rule_set_name --generate-cli-skeleton
```

- Delete a specific receipt rule:

```bash
aws ses delete-receipt-rule --rule-set-name rule_set_name --rule-name rule_name --generate-cli-skeleton
```

- Send an email:

```bash
aws ses send-email --from from_address --destination "ToAddresses=addresses" --message "Subject={Data=subject_text,Charset=utf8},Body={Text={Data=body_text,Charset=utf8},Html={Data=message_body_containing_html,Charset=utf8"
```

- Show help for a specific SES subcommand:

```bash
aws ses subcommand help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Sherman Hui](mailto:11592023+shermanhui@users.noreply.github.com) | aws-ses: add page (#7136) | 2021-11-07T22:06:37 | [b2d6839fd9ad](https://github.com/tldr-pages/tldr/commit/b2d6839fd9ad004a1730f8a34430878de396eccb)

