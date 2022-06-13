## Terraform

<details>
<summary>Explain what Terraform is and how does it works</summary><br><b>
</b></details>

<details>
<summary>Why one would prefer using Terraform and not other technologies? (e.g. Ansible, Puppet, CloudFormation)</summary><br><b>
</b></details>

<details>
<summary>How do you structure your Terraform projects?</summary><br><b>
</b></details>

<details>
<summary>True or False? Terraform follows the mutable infrastructure paradigm</summary><br><b>
</b></details>

<details>
<summary>True or False? Terraform uses declarative style to describe the expected end state</summary><br><b>
</b></details>

<details>
<summary>What is HCL?</summary><br><b>
</b></details>

<details>
<summary>Explain what is "Terraform configuration"</summary><br><b>
</b></details>

<details>
<summary>Explain what the following commands do:
  * <code>terraform init</code>
  * <code>terraform plan</code>
  * <code>terraform validate</code>
  * <code>terraform apply</code>
</summary><br><b>
</b></details>

#### Terraform - Resources

<details>
<summary>What is a "resource"?</summary><br><b>
</b></details>

<details>
<summary>Explain each part of the following line: `resource "aws_instance" "web_server" {...}`</summary><br><b>
</b></details>

<details>
<summary>What is the ID of the following resource: `resource "aws_instance" "web_server" {...}`</summary><br><b>
</b></details>

<details>
<summary>True or False? Resource ID must be unique within a workspace</summary><br><b>
</b></details>

<details>
<summary>Explain each of the following in regards to resources
</b></details>

#### Terraform - Providers

<details>
<summary>Explain what is a "provider"</summary><br><b>
</b></details>

<details>
<summary>What is the name of the provider in this case: `resource "libvirt_domain" "instance" {...}`</summary><br><b>
</b></details>

#### Terraform - Variables

<details>
<summary>What are Input Variables in Terraform? Why one should use them?</summary><br><b>
</b></details>

<details>
<summary>How to define variables?</summary><br><b>
</b></details>

<details>
<summary>How variables are used in modules?</summary><br><b>
</b></details>

<details>
<summary>How would you enforce users that use your variables to provide values with certain constraints? For example, a number greater than 1</summary><br><b>
</b></details>

<details>
<summary>What is the effect of setting variable as "sensitive"?</summary><br><b>
</b></details>

<details>
<summary>True or False? If an expression's result depends on a sensitive variable, it will be treated as sensitive as well</summary><br><b>
</b></details>

<details>
<summary>The same variable is defined in the following places:
</b></details>

<details>
<summary>What other way is there to define lots of variables in more "simplified" way?</summary><br><b>
</b></details>

#### Terraform - State

<details>
<summary>What <code>terraform.tfstate</code> file is used for?</summary><br><b>
</b></details>

<details>
<summary>How do you rename an existing resource?</summary><br><b>
</b></details>

<details>
<summary>Why does it matter where you store the tfstate file? Where would you store it?</summary><br><b>
</b></details>

<details>
<summary>Which command is responsible for creating state file?</summary><br><b>
</b></details>

<details>
<summary>By default where does the state get stored?</summary><br><b>
</b></details>

<details>
<summary>Can we store tfstate file at remote location? If yes, then in which condition you will do this?</summary><br><b>
</b></details>

<details>
<summary>Mention some best practices related to tfstate</summary><br><b>
</b></details>

<details>
<summary>How and why concurrent edits of the state file should be avoided?</summary><br><b>
</b></details>

<details>
<summary>Describe how you manage state file(s) when you have multiple environments (e.g. development, staging and production)</summary><br><b>
</b></details>

<details>
<summary>How to write down a variable which changes by an external source or during <code>terraform apply</code>?</summary><br><b>
</b></details>

<details>
<summary>You've deployed a virtual machine with Terraform and you would like to pass data to it (or execute some commands). Which concept of Terraform would you use?</summary><br><b>
</b></details>

#### Terraform - Provisioners

<details>
<summary>What are "Provisioners"? What they are used for?</summary><br><b>
</b></details>

<details>
<summary>What is <code>local-exec</code> and <code>remote-exec</code> in the context of provisioners?</summary><br><b>
</b></details>

<details>
<summary>What is a "tainted resource"?</summary><br><b>
</b></details>

<details>
<summary>What <code>terraform taint</code> does?</summary><br><b>
</b></details>

<details>
<summary>What types of variables are supported in Terraform?</summary><br><b>
</b></details>

<details>
<summary>What is a data source? In what scenarios for example would need to use it?</summary><br><b>
</b></details>

<details>
<summary>What are output variables and what <code>terraform output</code> does?</summary><br><b>
</b></details>

<details>
<summary>Explain Modules</summary>
</b></details>

<details>
<summary>What is the Terraform Registry?</summary><br><b>
</b></details>

<details>
<summary>Explain <code>remote-exec</code> and <code>local-exec</code></summary><br><b>
</b></details>


<details>
<summary>Explain "Remote State". When would you use it and how?</summary><br><b>
</b></details>

<details>
<summary>Explain "State Locking"</summary><br><b>
</b></details>

<details>
<summary>What is the "Random" provider? What is it used for</summary><br><b>
</b></details>

<details>
<summary>How do you test a terraform module?</summary><br><b>
</b></details>

<details>
<summary>Aside from <code>.tfvars</code> files or CLI arguments, how can you inject dependencies from other modules?</summary><br><b>
</b></details>

<details>
<summary>What is Terraform import?</summary><br><b>
</b></details>

<details>
<summary>How do you import existing resource using Terraform import?</summary><br><b>
</b></details>
