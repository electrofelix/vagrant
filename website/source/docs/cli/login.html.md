---
page_title: "vagrant login - Command-Line Interface"
sidebar_current: "cli-login"
---

# Login

**Command: `vagrant login`**

The login command is used to authenticate with the
[HashiCorp's Atlas](https://atlas.hashicorp.com) server. Logging is only
necessary if you are accessing protected boxes or using
[Vagrant Share](/docs/share).

**Logging in is not a requirement to use Vagrant.** The vast majority
of Vagrant does _not_ require a login. Only certain features such as protected
boxes or [Vagrant Share](/docs/share) require a login.

The reference of available command-line flags to this command
is available below.

## Options

* `--check` - This will check if you are logged in. In addition to outputting
  whether you are logged in or not, the command will have exit status 0 if you are
  logged in, and exit status 1 if you are not.

* `--logout` - This will log you out if you are logged in. If you are already
  logged out, this command will do nothing. It is not an error to call this
  command if you are already logged out.