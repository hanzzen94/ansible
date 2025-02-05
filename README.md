# My Ansible Repository

Manage server utilities, configure Podman, set timezone, and update packages using Ansible.

## Usage

1. Install **Ansible**.
2. Run the playbook:
   ```bash
   ansible-playbook -i inventory.yml main.yml
   ```

## Structure

1. `main.yml`: Orchestrates tasks.
2. `packages.yml`: Installs essential packages.
3. `podman_compose_services.yml`: Configures systemd services for Podman Compose.
4. `root.yml`: Disables the root account.
5. `time_zone.yml`: Sets the timezone.
6. `yum_upgrade.yml`: Updates all installed packages.

## Additional Information

For detailed module explanations, refer to the [official Ansible documentation](https://docs.ansible.com/).