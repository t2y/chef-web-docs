========================================================
Deprecation: Libvirt plugin attributes changes (OHAI-4)
========================================================
`[edit on GitHub] <https://github.com/chef/chef-web-docs/blob/master/chef_master/source/deprecations_ohai_libvirt_plugin.rst>`__

The Ohai libvirt plugin no longer places libvirt attributes under ``node['virtualization']`` and instead uses the ``node['libvirt']`` namespace to match other virtualization plugins.

Remediation
=============
