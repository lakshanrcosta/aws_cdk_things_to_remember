# CDK Commands

## CDK Init App

```bash
cdk init app --language typescript [preferred_language]
```

## CDK Bootstrap

```bash
cdk bootstrap --profile [aws_profile]
```

## Generate CDK out config template

```bash
cdk synth (generates the cdk.out config template)
```

## CDK Deploy

```bash
cdk deploy --profile [aws_profile]
```

## CDK List (Lists all stacks which is in local development)

```bash
cdk list --profile [aws_profile]
```

## CDK Diff (Lists the differences between local development and cloud)

```bash
cdk diff --profile [aws_profile]
```

## CDK Doctor (Checks for any issue in development environment)

```bash
cdk doctor
```

## CDK Destroy (Delete the stack from cloudformation)

```bash
cdk destroy [stack_name] --profile [profile_name]