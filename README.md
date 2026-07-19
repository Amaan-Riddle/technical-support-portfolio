# Technical Support & Systems Engineering Portfolio

Welcome to my technical portfolio. This repository serves as a live proof-of-work showcasing my hands-on skills in database querying, system administration, and infrastructure management.

## 🛠️ Core Technical Commands & Skills

### 1. Linux System Troubleshooting
* **Check Live Application Logs:** `tail -f /var/log/nginx/access.log`
* **Monitor Running Processes & Memory:** `top` or `htop`
* **Check Free Disk Space (Human Readable):** `df -h`
* **Verify Active Network Ports:** `netstat -tuln`

### 2. SQL Data & Support Queries
* **Find a specific user record by email:**
  ```sql
  SELECT user_id, status, created_at FROM users WHERE email = 'customer@email.com';
  ```
* **Identify active sessions lagging over 5 minutes:**
  ```sql
  SELECT session_id, user_id FROM user_sessions WHERE status = 'ACTIVE' AND last_activity < NOW() - INTERVAL 5 MINUTE;
  ```
