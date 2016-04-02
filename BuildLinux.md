We currently support building Gitso on Ubuntu, Fedora and OpenSUSE.

  1. From within the src directory:
  1. Update hosts.txt to have preset options for the client. Hosts are comma separated and optional.
  1. Run:./makegitso.sh `[`--source, --opensuse, --fedora`]`

## Fedora ##
  * You will first need to install the following:
    * yum install subversion
    * yum install rpmdevtools

## Notes ##
  * We also have the scripts working on CentOS, but CentOS 5.2 doesn't include wxWidgets. If you know differently, please let me know.
  * Currently the stand-alone version is automatically made if you're on Ubuntu, that will probably change at some point. There's no technical reason why it couldn't be done from the other POSIX systems...

## Examples ##
  * http://www.joneslinux.com/wordpress/?p=142