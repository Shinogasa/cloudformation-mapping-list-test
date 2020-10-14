# cloudformation-mapping-list-test

## About

## Command

### Deploy

```bash
aws cloudformation deploy \
--stack-name test-stack-dev \
--no-execute-changeset \
--template-file template_ng.yml \
--parameter-overrides Env=dev \
--capabilities CAPABILITY_NAMED_IAM
```

### Execute

```bash
aws cloudformation execute-change-set --change-set-name [ARN]
```
