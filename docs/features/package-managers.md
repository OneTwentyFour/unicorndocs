---
title: Package Managers
---

Package Managers are arguably one of the most fundamental parts of any distribution. Lucky for you, we've got two!

## toffget

``toffget`` is our signature package manager, and where (most of) the fundamental packages for toffeeOS are maintained. These include:
  - security/authentication-related packages
  - packages for various features, including Android apps

You can check for updates to various packages by performing the following action in Console/Terminal apps:

```
sudo toffget fetch --all
```

To apply ("snag") any updates ``fetch`` receives:

```
sudo toffget snag-new -y
```

To purge a badly-behaving update from your system (only use the ``--rm-user-data`` flag if the package you're trying to remove stores its data in the /home folder):

```
sudo toffget purge (package-name) --rm-user-data -y
```

## RPM (DNF)
We have removed support for RPM/DNF in toffeeOS 2.0. 
