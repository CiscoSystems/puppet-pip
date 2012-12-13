puppet-pip
==========

Puppet module to install and manage pip

Parts taken from Puppet, <http://www.puppetlabs.com> and under the Apache 2.0 License

WARNING WARNING WARNING!
This monkey-patches puppet, specifically the pip provider module, in order to add the
required install_options feature.  This *should* be harmless, but of course you
may have a version of puppet from 1976 or 2031 with a completely different form of
provider file.  If that's the case, this will probably comprehensively break the
pip provider.

This has been tested with Puppet v2.7.11.  Use with other versions at your own risk.
