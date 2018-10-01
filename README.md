# Extend EC2 Volume size

## Requirement

1. python3
2. ansible
3. aws-cli
4. aws-mfa

## Step

exec ```bash extend.sh -a aws-dev -v 3 -i dev-full -b /dev/xvdf```

### extend.sh arguments

    -a aws-profile 
        aws-profile you want access, that's credentials can't expired.

    -b block_device
        bolock device you want extend.

    -i instance_name
        instance name you are designate.

    -v volume-size
        whitch size you want extend to.
