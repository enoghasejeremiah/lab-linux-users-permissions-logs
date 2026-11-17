# Linux audit: users, permissions and logs

- Found and removed an extra uid 0 account (uid0.txt)
- Set .env to 600 and proved another user cannot read it
- Removed SUID from backup-helper (suid.txt)
- Ranked attacking IPs from auth.log (sample-auth.log, attackers.txt)
- SSH: keys only, no root login (sshd-after.txt)
