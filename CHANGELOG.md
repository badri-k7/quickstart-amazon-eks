# Release Notes

## 🔐 Security
- Enhanced IAM Configuration:
  - Updated IAM policies for AWSQS::Kubernetes::Resource
  - Implemented separate role for VPC proxy function
  - Added missing permissions
- Security Improvements:
  - Enabled default encryption for node EBS volumes
  - Enhanced security group cleanup process

## 🚀 Features
- AMI Volume Management:
  - Added root volume device name parameter
  - Fixed Windows EKS optimized AMIs volume configuration
  - Prevented duplicate EBS volume creation on nodes

## 🔄 Infrastructure
- Improved test job sequencing
- Updated AWSQS::Kubernetes::Resource/Get submodule

## 📝 Documentation
- Established CHANGELOG.md
- Added retirement notice for legacy documentation


