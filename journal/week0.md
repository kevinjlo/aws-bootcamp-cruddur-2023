# Week 0 — Billing and Architecture


## Create AWS Admin User

## Use Cloudshell
Started cloud shell in Canada Central region.
Ran standard aws cli commands as shown in yt videos
</br>
```aws account get-contact-information ```
</br>
```aws sts get-caller-identity```

## Geneate AWS Credentials
Created IAM user from root account
Enabled MFA on user account
Allowed Billing access for IAM users and provisioned requisite IAM policies against the user so that the IAM user can see billing portal
![IAMuser](asset_w0/IAMUser.JPG)
![IAMuserdetails](asset_w0/IAMUser2.JPG)


## Installed AWS CLI
Proof of installation of AWS on CLI </br>
![AWSInstall](asset_w0/awscli_install.JPG)

## Create Billing Alarm

## Create a Budget
