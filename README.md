# How I did it
1. Install `>= ansible2.4`
2. Create .vault_pass with password for decrypt(hint: AC knows it)
3. Make sure you have the angstwad.docker_ubuntu role in your `~/.ansible/roles/` path
        ansible-galaxy install angstwad.docker_ubuntu
4. run
        ansible-playbook -i prod site.yml --vault-password-file .vault_pass

# Things to Fix


# Things to make better
Jenkins container for automation
