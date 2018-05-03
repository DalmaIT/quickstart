# Dalmait CentOS 7 vagrant workspace

This a quickstart vagrant CentOS 7.x workspace by DalmaIT.

It supports following provider right now:

- virtualbox
- vmware_desktop

## Start

### Virtualbox vagrant workspace

```bash
vagrant up --provider=virtualbox
```

### vmware_desktop vagrant workspace

```bash
vagrant up --provider=vmware_desktop
```

## Continue

Once the vagrant virtual machine is up, you can continue your work with:

```bash
vagrant ssh
```

Then you will login to the VM via ssh protocal

## Destroy

For any reason you wanna destroy current workspace, you can go ahead with:

```bash
vagrant destroy
```

BE CAREFUL with the above command!
