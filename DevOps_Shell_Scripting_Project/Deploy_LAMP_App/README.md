**Project:** Automation of Deploying LAMP Stack application by using Shell Scripting.

We are using the same application that we manually deployed into CentOS machine. 

- Take me to [Manual LAMP Stack](https://github.com/VarunTej06/Devops_Projects/tree/main/LAMP%20Stack)

Before doing this project go trough the E-Commerce Application.docx or follow the doc and do manual deployment once in CentOS machine.

On doing above step you had deployed the application manually and it is up and running. 

Instead of doing this deployment manually, we can automate everystep using shell Scripting. 

**deploy.sh** in current directory is the bash script written that automated the deployment of the same application. 

- Can directly run the script in CentOS machine in order to deploy the application. First, give execute permissions.
  <details>
  ```
  $ chmod +x deploy-ecommerce-application.sh
  ```
  </details>
  
- Run the script
  <details>
  ```
  $ ./deploy-ecommerce-application.sh
  ```
  </details>

**Process:** Either create a new file and copy the script into that file and then execute it or Clone the Project repo and do it.
