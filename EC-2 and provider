provider "aws" {
  region     = "ap-south-1"
  access_key = "AKIATQRXEXIDHIF5CWXK"
  secret_key = "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"
}

module "ec2_instance" {
  source  = "terraform-aws-modules/ec2-instance/aws"

  name = "ec2-user"
  ami="ami-099b3d23e336c2e83"
  instance_type          = "t2.micro"
  key_name               = "Akhi"
  monitoring             = false
  vpc_security_group_ids = ["sg-02645727312587faf"]
  
}
