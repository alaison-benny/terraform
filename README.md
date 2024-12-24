# How to write a terraform configuration file creation? sample
............................................
Let's get some more practice! Now navigate to the directory path /root/terraform-projects/provider-a. Create a configuration file called code.tf.

Using the local_file resource type, write the resource block with the below requirements into the file:

Resource name = iac_code

File name = /opt/practice

Content = Setting up infrastructure as code


When ready, only run the terraform init command, we will run the terraform apply command later on.
-------------------------------------------------

resource "local_file" "iac_code" {
          filename = "/opt/practice"
          content = "Setting up infrastructure as code"
}
