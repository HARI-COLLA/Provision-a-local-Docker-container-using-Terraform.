# Task 3 - Provision a Local Docker Container Using Terraform 🐳

## 🎯 Objective

To provision a Docker container running the Nginx web server using **Terraform** as part of the DevOps internship assignment (Task 3).

---

## 🛠️ Tools Used

- Terraform
- Docker
- Git & GitHub
- VS Code (or any code editor)

---

## 🧱 Project Structure
├── main.tf # Terraform configuration
└── README.md # Task summary and documentation



---

## ⚙️ Steps Performed

1. Installed Docker and Terraform locally.
2. Created a `main.tf` file with:
   - Docker provider
   - Nginx image resource
   - Docker container resource named `nginx-server`
3. Executed Terraform commands to:
   - Initialize the project
   - Preview planned infrastructure
   - Apply the configuration
4. Resolved port conflict (8080) by stopping existing services.
5. Verified successful deployment using `docker ps` and browser access to `http://localhost:8080`
6. Finally, used `terraform destroy` to clean up the created infrastructure.

---

## 🔄 Terraform Commands Used

```bash
terraform init          # Initializes the project
terraform plan          # Shows the execution plan
terraform apply         # Provisions the container
terraform destroy       # Tears down the infrastructure
docker ps               # Verifies running container






