## ANXS - perl [![Build Status](https://travis-ci.org/ANXS/perl.png)](https://travis-ci.org/ANXS/perl)

Ansible role which manages Perl installation and provides cpan_module, to install modules from CPAN.


#### Requirements & Dependencies
- Tested on Ansible 1.4 or higher.


#### Variables

```yaml
perl_cpanm_version: "1.7102"              # The CPAN release version
perl_cpanm_path: "/usr/local/bin/cpanm"   # The CPAN script location
```


#### Testing
This project comes with a VagrantFile, this is a fast and easy way to test changes to the role, fire it up with `vagrant up`

See [vagrant docs](https://docs.vagrantup.com/v2/) for getting setup with vagrant


#### License

Licensed under the MIT License. See the LICENSE file for details.


#### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/ANXS/perl/issues)!
