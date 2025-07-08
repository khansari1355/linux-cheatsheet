# File Permissions in Linux (chmod, chown, umask)

## 🔍 Checking Permissions

```bash
ls -l
Example output:
-rw-r--r-- 1 khansari khansari 1234 Jul 6 12:00 file.txt
chmod – Change File Permissions
| Symbol | Meaning |
| ------ | ------- |
| r      | Read    |
| w      | Write   |
| x      | Execute |
Numeric values:

r = 4, w = 2, x = 1
chmod 755 file.sh
Examples:
chmod +x script.sh – Add execute permission

chmod 644 file.txt – Owner: rw-, Group: r--, Others: r--
chown – Change Owner
sudo chown user:group file.txt
Example:
sudo chown root:root test.sh
umask – Default Permission Mask
umask
If result is 0022, new files will be
Files: 644 (rw-r--r--)
Directories: 755 (rwxr-xr-x)

