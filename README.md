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

## ⚙️ Steps Followed

1. Installed Docker and Terraform on the local machine
2. Created a `main.tf` file defining:
   - Docker provider
   - Nginx Docker image
   - Docker container named `nginx-server`
3. Ran the following Terraform commands:
   - `terraform init`
   - `terraform plan`
   - `terraform apply`
4. Resolved port conflict by stopping processes using port 8080
5. Verified the container was running using `docker ps` and accessed Nginx via `http://localhost:8080`

---

## 🔄 Terraform Commands Used

```bash
terraform init
terraform plan
terraform apply
terraform destroy
docker ps
