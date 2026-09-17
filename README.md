# Sauce Labs / Backtrace Git symlink source lookup PoC

This public repository is a harmless proof fixture for authorized testing of the Backtrace source-code integration. The Git index records `etc-hostname-link` with mode `120000`; its blob content is `/etc/hostname`. No filesystem symlink is stored in this project directory.

Expected control file content: `owned-repository-control-dbv3`

