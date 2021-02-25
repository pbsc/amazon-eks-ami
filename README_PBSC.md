# EKS Node Group AMI

To run for our environment:
```
make 1.18 subnet_id=subnet-040c644e6e23d865a aws_region=us-east-1
```

Modifications made:
- Add script to install ssm agent
- Expose 'subnet_id' packer var in Makefile
