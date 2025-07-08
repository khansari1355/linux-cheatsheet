# User and Group Management in Linux

## 👤 User Commands

### Add User
```bash
sudo adduser ali
Delete User (with home)
sudo deluser --remove-home ali
Lock/Unlock User
sudo usermod -L ali
sudo usermod -U ali
Rename User
sudo usermod -l newname oldname
# Group Commands
#Add Group
sudo delgroup devops
#Add User to Group
sudo usermod -aG devops ali
#List User's Groups
groups ali
#Change Primary Group
sudo usermod -g devops ali


