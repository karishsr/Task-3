**Task 3: Infrastructure as Code (IaC) with Terraform**

1. Objective:
Provision a local Docker container using Terraform.

2. Tools Used:
- Terraform
- Docker
- VS Code

3. What I Did:
- Created a Terraform config to provision an Nginx container.
- Used Docker provider to pull the `nginx:latest` image.
- Exposed it locally on port 8081.
- Verified the container with `docker ps` and browser.
- Destroyed the infra using `terraform destroy`.

4. How to Run:
1. Install Docker and Terraform.
2. Clone this repo.
3. Run:
   ```bash
   terraform init
   terraform apply
