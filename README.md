# Ansible Role: phpMyAdmin

[![Ansible Galaxy](http://img.shields.io/badge/galaxy-novuso.phpmyadmin-000000.svg)](https://galaxy.ansible.com/list#/roles/3864)
[![MIT License](http://img.shields.io/badge/license-MIT-003399.svg)](http://opensource.org/licenses/MIT)
[![Build Status](https://travis-ci.org/novuso/ansible-role-phpmyadmin.svg)](https://travis-ci.org/novuso/ansible-role-phpmyadmin)

An Ansible role that manages phpMyAdmin for PHP FPM on Ubuntu 14.04

## Requirements

This Ansible role requires PHP FPM and either the Apache or Nginx HTTP server.

## Role Variables

TODO

## Dependencies

None

## Example Playbook

    ---
    - hosts: all
      roles:
      - novuso.php-ext
      - novuso.php-fpm
      - novuso.phpmyadmin

## License

This is released under the [MIT license](http://opensource.org/licenses/MIT).
