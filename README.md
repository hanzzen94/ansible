## Usage

1. Install **Ansible**.
2. Clone this repository:
   ```bash
   git clone <repository_url>
   cd ansible
   ```
3. Update the inventory file with your hosts.
4. Run the playbook:
   ```bash
   ansible-playbook -i inventory.yml {{ playbook }}.yml
   ```

## Example Inventory

```ini
[servers]
server1 ansible_host=192.168.1.10

[proxmox]
proxmox1 ansible_host=192.168.1.20

[docker_hosts]
docker1 ansible_host=192.168.1.30
```

## Additional Information

For detailed module explanations, refer to the [official Ansible documentation](https://docs.ansible.com/).