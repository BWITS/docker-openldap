# Changelog

## 1.0.9
  - Update to light-baseimage:0.2.0
  - Makefile with build no cache

## 1.0.8
  - Fix an other startup bug ! whuhu

## 1.0.7
  - Fix startup bug

## 1.0.6
  - Use light-baseimage:0.1.5

## 1.0.5
  - Use light-baseimage:0.1.4
  - Fix replication bug when the hostname was changed

## 1.0.4
  - Use light-baseimage:0.1.3

## 1.0.3
  - Use light-baseimage:0.1.2
  - Fixes :
    - Re-running container with volumes won't start #19

## 1.0.2

  - Add TLS environment variable :
      - LDAP_TLS_CIPHER_SUITE
      - LDAP_TLS_PROTOCOL_MIN
      - LDAP_TLS_VERIFY_CLIENT

## 1.0.1

  - Upgrade baseimage: light-baseimage:0.1.1
  - Rename environment variables

  - Fixes :
    - OpenLdap container won't start when dhparam.pem is missing in bound volume #13

## 1.0.0

  - Use light-baseimage
  - Improve documentation

## 0.10.2

  - New features:
    - Bootstrap config, only on non existing slapd config
    - Limit max open file descriptors to fix slapd memory usage (#9)
    - Don't disable network access from outside (#8)
    - Make log level configurable via environment variable (#7)
    - Support for ldaps (#10)


  - Fixes:
    - Unable to start container with the following invocation. (#6)

## 0.10.1

  - New features:
    - Add ldapi
    - Add ldapi
    - Add custom ldap schema
    - Auto convert .schema to .ldif


  - Fixes :
    - Docker VOLUME is not needed to be able to stop a container without losing data (#2)
    - starting from old data (#3)

## 0.10.0
  - New version initial release
