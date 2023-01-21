
# How to Use

## Install Node LTS 18.x
Install the package node lts 18.13
https://nodejs.org/en/download/

```
npm install --global yarn
yarn
yarn start
```

## Deploy

### Install aws cli 

https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html
https://awscli.amazonaws.com/AWSCLIV2.pkg

### Setup aws credentials
create `chattingcat-deployer` profile for aws cli

```
aws configure --profile chattingcat-deployer
AWS Access Key ID [****************aaaa]:
AWS Secret Access Key [****************aaaa]:
Default region name [ap-northeast-2]:
Default output format [json]:
```

### Deploy

```
yarn deploy 
```

