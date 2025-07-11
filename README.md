# Landscape Setup Service-account and API Token Creation

## Prerequisite  
Ensure the playbook **`deploy_ssl_to_lxc.yml`** has successfully run.  
This means your Landscape server is properly installed with SSL enabled, and the web interface is accessible via HTTPS at:  


---

## 1. Creating a Standalone Admin User in Landscape

1. **Open the standalone user registration page**  
   Navigate in your browser to:  
If this page is available, you will see a registration form requesting:  
- Name (e.g., `svc-config`)  
- Email address (e.g., `svc-config@example.com`)  
- Passphrase (password)  
- Passphrase confirmation

2. **Fill out the form**  
Enter the required details and choose a strong passphrase.

3. **Submit the form**  
After submission, the user will be created and automatically logged in.

4. **Admin access granted**  
This user becomes the first and main administrator of the Landscape server and will be redirected to the admin dashboard.

---

## 2. Creating API Tokens via the Landscape Web UI

If your Landscape version supports API tokens, you can create them as follows:

1. **Log in to the web interface**  
Log in using the newly created admin user (e.g., `svc-config`).

2. **Go to User Settings**  
Navigate to **User Settings** or **Account Settings**.

3. **Locate the API Tokens section**  
Find the section named **API Tokens** or **Access Tokens**.

4. **Create a new token**  
Click **Create Token** to generate a new API token.

---

Once these steps are complete, you will have a secure Landscape environment with an admin account and, if supported, an API token for automated API access.

---

