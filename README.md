# Ansible modules

## Module List (currently)

* cabal (Haskell)

## Usage

Modules are found in the path specified by `ANSIBLE_LIBRARY` or the `--module-path` command line option.

If you put the `./library` directory in your top level playbooks, it is automatically added as a search directory.

```
{your_playbooks}/
    library/
        cabal
    roles/
        ...
    site.yml
    hosts
    ...
```

(See [Developing Modules](http://docs.ansible.com/developing_modules.html) )

