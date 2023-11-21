Kerberos-BOF extension for Sliver C2

Original Repo: https://github.com/RalfHacker/Kerberos-BOF/

We have just compiled and created an extension for Sliver.

How to use:

    Download the repository.
    Move it to the '~/.sliver-client/extensions' folder.
    Install the extension:
        extensions install /root/.sliver-client/extensions/kerb-klist
        extensions load /root/.sliver-client/extensions/kerb-klist
    Run krb_klist.
