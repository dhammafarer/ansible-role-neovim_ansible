Role Name
=========

Demonstrates the use of LSP with ansible-language-server in neovim

Requirements
------------
Requires community.general.npm module.

Role Variables
--------------

language_servers: a list of language servers to install

install_treesitter: whether to install TreeSitter for syntax

Dependencies
------------

Doesn't require any roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - palekiwi.neovim_ansible

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
