# Changelog

## [7.3.0](https://github.com/dev-sec/ansible-collection-hardening/tree/7.3.0) (2021-03-11)

[Full Changelog](https://github.com/dev-sec/ansible-collection-hardening/compare/7.2.0...7.3.0)

**Implemented enhancements:**

- Extend GSSAPI configuration support to ssh\_config [\#403](https://github.com/dev-sec/ansible-collection-hardening/pull/403) ([wzzrd](https://github.com/wzzrd))
- add restart handler variable for mysql role [\#399](https://github.com/dev-sec/ansible-collection-hardening/pull/399) ([rndmh3ro](https://github.com/rndmh3ro))

**Closed issues:**

- Unable to connect with SSH \(Permission denied \(publickey\)\) [\#411](https://github.com/dev-sec/ansible-collection-hardening/issues/411)
- TASK \[os\_hardening : configure auditd | package-08\] [\#410](https://github.com/dev-sec/ansible-collection-hardening/issues/410)
- Collection throws undefined ansible\_role\_name error in auditd task [\#409](https://github.com/dev-sec/ansible-collection-hardening/issues/409)
- Ensure permissions on /etc/crontab are configured [\#375](https://github.com/dev-sec/ansible-collection-hardening/issues/375)
- Documentation should be updated [\#361](https://github.com/dev-sec/ansible-collection-hardening/issues/361)

**Merged pull requests:**

- Ensure permissions on /etc/crontab are configured [\#405](https://github.com/dev-sec/ansible-collection-hardening/pull/405) ([joubbi](https://github.com/joubbi))
- remove FQCN from roles in examples [\#404](https://github.com/dev-sec/ansible-collection-hardening/pull/404) ([schurzi](https://github.com/schurzi))
- do not install mysql python package on target host [\#401](https://github.com/dev-sec/ansible-collection-hardening/pull/401) ([rndmh3ro](https://github.com/rndmh3ro))
- make wrong password fail task [\#400](https://github.com/dev-sec/ansible-collection-hardening/pull/400) ([rndmh3ro](https://github.com/rndmh3ro))

## [7.2.0](https://github.com/dev-sec/ansible-collection-hardening/tree/7.2.0) (2021-02-10)

[Full Changelog](https://github.com/dev-sec/ansible-collection-hardening/compare/7.1.1...7.2.0)

**Implemented enhancements:**

- Add variable to specify SSH host RSA key size [\#394](https://github.com/dev-sec/ansible-collection-hardening/pull/394) ([Normo](https://github.com/Normo))
- Set default for ssh host key files only when hardening the server [\#393](https://github.com/dev-sec/ansible-collection-hardening/pull/393) ([Normo](https://github.com/Normo))

**Fixed bugs:**

- A reason why instance would go in rescue mode ?  [\#267](https://github.com/dev-sec/ansible-collection-hardening/issues/267)
- fix galaxy action to update local galaxy.yml [\#395](https://github.com/dev-sec/ansible-collection-hardening/pull/395) ([Normo](https://github.com/Normo))

**Closed issues:**

- Updating version in galaxy.yml should be part of the release process [\#396](https://github.com/dev-sec/ansible-collection-hardening/issues/396)
- ssh\_hardening fail on keypair generation  [\#388](https://github.com/dev-sec/ansible-collection-hardening/issues/388)
- The system must display the date and time of the last successful account logon upon an SSH logon. [\#362](https://github.com/dev-sec/ansible-collection-hardening/issues/362)
- Error in "root password is present" step [\#326](https://github.com/dev-sec/ansible-collection-hardening/issues/326)

**Merged pull requests:**

- fix minimum required ansible version in docs [\#390](https://github.com/dev-sec/ansible-collection-hardening/pull/390) ([schurzi](https://github.com/schurzi))

## [7.1.1](https://github.com/dev-sec/ansible-collection-hardening/tree/7.1.1) (2021-02-05)

[Full Changelog](https://github.com/dev-sec/ansible-collection-hardening/compare/7.1.0...7.1.1)

**Fixed bugs:**

- use fqcn for community.crypto.openssh\_keypair module [\#389](https://github.com/dev-sec/ansible-collection-hardening/pull/389) ([schurzi](https://github.com/schurzi))

**Closed issues:**

- AnsibleUndefinedVariable: 'ansible\_role\_name' is undefined with 7.1.0 [\#387](https://github.com/dev-sec/ansible-collection-hardening/issues/387)

## [7.1.0](https://github.com/dev-sec/ansible-collection-hardening/tree/7.1.0) (2021-02-02)

[Full Changelog](https://github.com/dev-sec/ansible-collection-hardening/compare/7.0.0...7.1.0)

**Implemented enhancements:**

- Default value for ssh\_max\_startups should be changed [\#366](https://github.com/dev-sec/ansible-collection-hardening/issues/366)
- Comment in configuration files should state which collection was there [\#345](https://github.com/dev-sec/ansible-collection-hardening/issues/345)
- Error on applying the sysctl vars on Debian Jessy [\#230](https://github.com/dev-sec/ansible-collection-hardening/issues/230)
- add Support for OpenSSH HostCertificate config option [\#380](https://github.com/dev-sec/ansible-collection-hardening/pull/380) ([mpraeger](https://github.com/mpraeger))
- Syncookie [\#372](https://github.com/dev-sec/ansible-collection-hardening/pull/372) ([joubbi](https://github.com/joubbi))
- Sorted sysctl values and lists in READMEs alphabetically \(No functional changes\). [\#371](https://github.com/dev-sec/ansible-collection-hardening/pull/371) ([joubbi](https://github.com/joubbi))
- make auditd 'max\_log\_file' configurable [\#370](https://github.com/dev-sec/ansible-collection-hardening/pull/370) ([tgueldner-mms](https://github.com/tgueldner-mms))
- reduce maximum unauthenticated ssh sessions [\#368](https://github.com/dev-sec/ansible-collection-hardening/pull/368) ([schurzi](https://github.com/schurzi))
- add a runtime.yml to declare minimum ansible version [\#363](https://github.com/dev-sec/ansible-collection-hardening/pull/363) ([rndmh3ro](https://github.com/rndmh3ro))
- change inclusion of os specific defaults [\#353](https://github.com/dev-sec/ansible-collection-hardening/pull/353) ([schurzi](https://github.com/schurzi))
- make the os\_env\_umask variable usable [\#351](https://github.com/dev-sec/ansible-collection-hardening/pull/351) ([sprat](https://github.com/sprat))
- Fix \#348: make ssh configuration files paths configurable [\#350](https://github.com/dev-sec/ansible-collection-hardening/pull/350) ([sprat](https://github.com/sprat))
- Removed Protocol statement in later versions of sshd, since the code ??? [\#342](https://github.com/dev-sec/ansible-collection-hardening/pull/342) ([joubbi](https://github.com/joubbi))
- Improvements of comments in opensshd.conf.j2  \#338 [\#339](https://github.com/dev-sec/ansible-collection-hardening/pull/339) ([joubbi](https://github.com/joubbi))

**Fixed bugs:**

- Comments in opensshd.conf.j2 should be improved [\#338](https://github.com/dev-sec/ansible-collection-hardening/issues/338)
- check for correct cpu vendor in initramfs-tools [\#374](https://github.com/dev-sec/ansible-collection-hardening/pull/374) ([schurzi](https://github.com/schurzi))
- set hidepid=0 on RHEL/CentOS 7 [\#369](https://github.com/dev-sec/ansible-collection-hardening/pull/369) ([schurzi](https://github.com/schurzi))

**Closed issues:**

- initramfs-tools modules.j2 does not seem to be able to detect AMD CPUs [\#373](https://github.com/dev-sec/ansible-collection-hardening/issues/373)
- How do i install this on Centos 8? [\#367](https://github.com/dev-sec/ansible-collection-hardening/issues/367)
- hidepid=2 gives error when running systemctl on EL7 [\#364](https://github.com/dev-sec/ansible-collection-hardening/issues/364)
- Allow putting the ssh/sshd config in alternative files [\#348](https://github.com/dev-sec/ansible-collection-hardening/issues/348)
- os\_env\_umask has no effect [\#344](https://github.com/dev-sec/ansible-collection-hardening/issues/344)
- Don't modify /etc/sysctl.conf [\#343](https://github.com/dev-sec/ansible-collection-hardening/issues/343)

**Merged pull requests:**

- update ansible-lint to version 5 [\#397](https://github.com/dev-sec/ansible-collection-hardening/pull/397) ([schurzi](https://github.com/schurzi))
- use version tag for changelog action [\#386](https://github.com/dev-sec/ansible-collection-hardening/pull/386) ([schurzi](https://github.com/schurzi))
- make release workflow manually runnable [\#384](https://github.com/dev-sec/ansible-collection-hardening/pull/384) ([schurzi](https://github.com/schurzi))
- run labeler workflow with higher privileges [\#383](https://github.com/dev-sec/ansible-collection-hardening/pull/383) ([schurzi](https://github.com/schurzi))
- remove issue labels from changelog [\#382](https://github.com/dev-sec/ansible-collection-hardening/pull/382) ([schurzi](https://github.com/schurzi))
- Added comment on top of templates about which role manages the file [\#378](https://github.com/dev-sec/ansible-collection-hardening/pull/378) ([joubbi](https://github.com/joubbi))
- Regenerate RSA key with size 4096 bits [\#376](https://github.com/dev-sec/ansible-collection-hardening/pull/376) ([ssttehrani](https://github.com/ssttehrani))
- fix second changelog generation task, too [\#349](https://github.com/dev-sec/ansible-collection-hardening/pull/349) ([rndmh3ro](https://github.com/rndmh3ro))
- fix changelog generation [\#341](https://github.com/dev-sec/ansible-collection-hardening/pull/341) ([rndmh3ro](https://github.com/rndmh3ro))
- Improve README for ssh\_hardening [\#335](https://github.com/dev-sec/ansible-collection-hardening/pull/335) ([szEvEz](https://github.com/szEvEz))

## [7.0.0](https://github.com/dev-sec/ansible-collection-hardening/tree/7.0.0) (2020-11-11)

[Full Changelog](https://github.com/dev-sec/ansible-collection-hardening/compare/6.2.0...7.0.0)

**Breaking changes:**

- Move all roles to one single collection [\#332](https://github.com/dev-sec/ansible-collection-hardening/pull/332) ([rndmh3ro](https://github.com/rndmh3ro))

**Implemented enhancements:**

- Breaking change in ansible-lint - set file permissions explicitly [\#299](https://github.com/dev-sec/ansible-collection-hardening/issues/299)
- Improve Documentation [\#315](https://github.com/dev-sec/ansible-collection-hardening/pull/315) ([schurzi](https://github.com/schurzi))
- Arch support [\#303](https://github.com/dev-sec/ansible-collection-hardening/pull/303) ([rndmh3ro](https://github.com/rndmh3ro))
- fix linting for molecule [\#301](https://github.com/dev-sec/ansible-collection-hardening/pull/301) ([schurzi](https://github.com/schurzi))
- file permissions explicitly defined [\#300](https://github.com/dev-sec/ansible-collection-hardening/pull/300) ([danielkubat](https://github.com/danielkubat))
- Optimize and unify when clause [\#295](https://github.com/dev-sec/ansible-collection-hardening/pull/295) ([Alexhha](https://github.com/Alexhha))
- use find module instead of shell [\#294](https://github.com/dev-sec/ansible-collection-hardening/pull/294) ([danielkubat](https://github.com/danielkubat))
- improve testing [\#287](https://github.com/dev-sec/ansible-collection-hardening/pull/287) ([schurzi](https://github.com/schurzi))
- Mount proc filesystem using hidepid option [\#283](https://github.com/dev-sec/ansible-collection-hardening/pull/283) ([alegrey91](https://github.com/alegrey91))
- unify changelog and release actions [\#279](https://github.com/dev-sec/ansible-collection-hardening/pull/279) ([rndmh3ro](https://github.com/rndmh3ro))
- purge insecure packages [\#275](https://github.com/dev-sec/ansible-collection-hardening/pull/275) ([chris-rock](https://github.com/chris-rock))
- add changelog and release workflow [\#271](https://github.com/dev-sec/ansible-collection-hardening/pull/271) ([rndmh3ro](https://github.com/rndmh3ro))

**Fixed bugs:**

- Task "set 10.hardcore.conf perms to 0400 and root ownership" fails in check mode [\#313](https://github.com/dev-sec/ansible-collection-hardening/issues/313)
- use touch for 10.hardcore.conf to avoid problems with dry-run [\#314](https://github.com/dev-sec/ansible-collection-hardening/pull/314) ([schurzi](https://github.com/schurzi))
- use touch with no date changes [\#310](https://github.com/dev-sec/ansible-collection-hardening/pull/310) ([rndmh3ro](https://github.com/rndmh3ro))
- do not touch sysctl file to avoid idempotency problems [\#309](https://github.com/dev-sec/ansible-collection-hardening/pull/309) ([rndmh3ro](https://github.com/rndmh3ro))
- replace module parameter fixed [\#297](https://github.com/dev-sec/ansible-collection-hardening/pull/297) ([danielkubat](https://github.com/danielkubat))

**Closed issues:**

- Any planned support for RHEL/CentOS 8? [\#298](https://github.com/dev-sec/ansible-collection-hardening/issues/298)

**Merged pull requests:**

- prettier markdown files action added [\#322](https://github.com/dev-sec/ansible-collection-hardening/pull/322) ([danielkubat](https://github.com/danielkubat))
- adjust permissions on shadow file on suse [\#311](https://github.com/dev-sec/ansible-collection-hardening/pull/311) ([rndmh3ro](https://github.com/rndmh3ro))
- fix fedora build [\#296](https://github.com/dev-sec/ansible-collection-hardening/pull/296) ([rndmh3ro](https://github.com/rndmh3ro))
- do not blacklist used filesystems [\#289](https://github.com/dev-sec/ansible-collection-hardening/pull/289) ([schurzi](https://github.com/schurzi))
- move hidepid vars into defaults so theyre overwritable [\#285](https://github.com/dev-sec/ansible-collection-hardening/pull/285) ([rndmh3ro](https://github.com/rndmh3ro))
- install procps in debian so sysctl.conf exists [\#282](https://github.com/dev-sec/ansible-collection-hardening/pull/282) ([rndmh3ro](https://github.com/rndmh3ro))



\* *This Changelog was automatically generated by [github_changelog_generator](https://github.com/github-changelog-generator/github-changelog-generator)*
