# My OSX Setup

[![Continuous integration](https://github.com/jaspermondie/my-osx-setup/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/svo/my-osx-setup/actions/workflows/main.yml)

## Testing

If no Virtual Machine already in place:

```
vagrant up
```

If Virtual Machine already created:

```
vagrant provision
```

## Building

### Including Bootstrapping

```
./prepare.sh && ./build.sh
```

Above sets up `brew`, `python`, `pip` and `ansible` before running the `playbook.yml`.

### Ansible Only

```
./build.sh
```
