# Ansible Role for Bootstrap

## 3.5.0 - TBC

### Major Changes

  - Default with Python 3

## 3.4.0 - 2019-09-18

### Major Changes

  - Run molecule test manually on Travis CI
  - Install `lsb-base` and `net-tools`

## 3.3.0 - 2019-08-27

### Major Changes

  - Update for RHEL 7
  - Add Vagrant test for RHEL 7

## 3.2.0 - 2019-07-08

### Major Changes

  - Update LXD test profile for Kubernetes v1.15.0 support
  - Fix molecule `group_vars` with links
  - Replace `with_items` with `loop`
  - Replace `with_dict` with `var`
  - Replace `with_first_found` with `lookup('first_found')`

## 3.1.0 - 2019-06-13

### Major Changes

  - Always include default variables from `vars/main.yml`
  - Always use `become: true` with molecule, especially for vagrant

## 3.0.0 - 2019-05-20

### Major Changes

  - Upgrade minimal Ansible support to 2.8.0

## 2.6.0 - 2019-05-04

### Major Changes

  - Refine Travis CI Molecue test cases

## 2.5.0 - 2019-04-17

### Major Changes

  - Remove `python-urllib3` for RHEL/CentOS
  - Run test with `travis_wait 120`

## 2.4.0 - 2019-03-03

### Major Changes

  - Add openSUSE Leap 15 support
  - Remove CentOS 6 support

## 2.3.5 - 2019-02-09

  - Ininitial release for Ansible 2.6
  - Support both Ubuntu 16.04/18.04 and RHEL/Centos 6/7
