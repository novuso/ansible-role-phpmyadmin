# Ansible Role: phpMyAdmin

[![MIT License](http://img.shields.io/badge/license-MIT-003399.svg)](http://opensource.org/licenses/MIT)

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
