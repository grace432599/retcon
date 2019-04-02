## Use

### OSX

```
xcode-select --install
sudo easy_install pip
sudo pip install ansible
ansible-galaxy install geerlingguy.homebrew
ansible-playbook main.yml -i hosts -K
```

- Update apps in the AppStore
- Sync Visual Studio Code settings using the sync extension, the token stored in the password store, and the `26ab34bdf52f9661f4aab3addfd977bb` gist.
- Use System Preferences to:
  - Remap CapsLock to Escape.
  - Change my avatar.

### Archlinux

```
pacman -S ansible
ansible-playbook main.yml -i hosts.ini -K --extra-vars "ansible_python_interpreter=/usr/bin/python2"
```
