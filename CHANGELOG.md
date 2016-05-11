# Change Log

## [cosmic-core-5.0.1.7](https://github.com/MissionCriticalCloud/cosmic-core/tree/cosmic-core-5.0.1.7) (2016-05-11)
[Full Changelog](https://github.com/MissionCriticalCloud/cosmic-core/compare/cosmic-core-5.0.1.6...cosmic-core-5.0.1.7)

## [cosmic-core-5.0.1.6](https://github.com/MissionCriticalCloud/cosmic-core/tree/cosmic-core-5.0.1.6) (2016-05-11)
[Full Changelog](https://github.com/MissionCriticalCloud/cosmic-core/compare/cosmic-core-5.0.1.5...cosmic-core-5.0.1.6)

**Merged pull requests:**

- Revert "Add a method to check if the default route is present." [\#145](https://github.com/MissionCriticalCloud/cosmic-core/pull/145) ([wilderrodrigues](https://github.com/wilderrodrigues))
- CS-684: Remove ldap module [\#143](https://github.com/MissionCriticalCloud/cosmic-core/pull/143) ([nhelsherif](https://github.com/nhelsherif))
- Move RabbitMQ plugin to own repository [\#142](https://github.com/MissionCriticalCloud/cosmic-core/pull/142) ([bheuvel](https://github.com/bheuvel))
- Speedup vm start by making vm\_passwd saving much faster [\#138](https://github.com/MissionCriticalCloud/cosmic-core/pull/138) ([remibergsma](https://github.com/remibergsma))
- Add a method to check if the default route is present. [\#130](https://github.com/MissionCriticalCloud/cosmic-core/pull/130) ([wilderrodrigues](https://github.com/wilderrodrigues))

## [cosmic-core-5.0.1.5](https://github.com/MissionCriticalCloud/cosmic-core/tree/cosmic-core-5.0.1.5) (2016-05-10)
[Full Changelog](https://github.com/MissionCriticalCloud/cosmic-core/compare/cosmic-core-5.0.1.4...cosmic-core-5.0.1.5)

**Merged pull requests:**

- Remove unused tools/utils folder and scripts. [\#141](https://github.com/MissionCriticalCloud/cosmic-core/pull/141) ([borisroman](https://github.com/borisroman))
- Remove unused Apache logo [\#140](https://github.com/MissionCriticalCloud/cosmic-core/pull/140) ([borisroman](https://github.com/borisroman))
- Remove travis configuration as we are using Jenkins [\#139](https://github.com/MissionCriticalCloud/cosmic-core/pull/139) ([borisroman](https://github.com/borisroman))
- Update pom to latest snapshot [\#134](https://github.com/MissionCriticalCloud/cosmic-core/pull/134) ([borisroman](https://github.com/borisroman))
- Update parent to new snapshot version [\#133](https://github.com/MissionCriticalCloud/cosmic-core/pull/133) ([miguelaferreira](https://github.com/miguelaferreira))

## [cosmic-core-5.0.1.4](https://github.com/MissionCriticalCloud/cosmic-core/tree/cosmic-core-5.0.1.4) (2016-05-04)
[Full Changelog](https://github.com/MissionCriticalCloud/cosmic-core/compare/cosmic-core-5.0.1.3...cosmic-core-5.0.1.4)

**Merged pull requests:**

- Move marvin to new repository [\#132](https://github.com/MissionCriticalCloud/cosmic-core/pull/132) ([borisroman](https://github.com/borisroman))
- \[manual\] prepare for next development iteration [\#131](https://github.com/MissionCriticalCloud/cosmic-core/pull/131) ([borisroman](https://github.com/borisroman))
- Include enhanced multi vpn test [\#129](https://github.com/MissionCriticalCloud/cosmic-core/pull/129) ([bheuvel](https://github.com/bheuvel))

## [cosmic-core-5.0.1.3](https://github.com/MissionCriticalCloud/cosmic-core/tree/cosmic-core-5.0.1.3) (2016-05-02)
[Full Changelog](https://github.com/MissionCriticalCloud/cosmic-core/compare/cosmic-core-5.0.1.1...cosmic-core-5.0.1.3)

**Fixed bugs:**

- VPCs only work on the hypervisor type which name comes first in the alphabet [\#123](https://github.com/MissionCriticalCloud/cosmic-core/issues/123)

**Merged pull requests:**

- Improve marvin logging [\#128](https://github.com/MissionCriticalCloud/cosmic-core/pull/128) ([miguelaferreira](https://github.com/miguelaferreira))
- Fix smoke/test\_vpc\_redundant [\#126](https://github.com/MissionCriticalCloud/cosmic-core/pull/126) ([borisroman](https://github.com/borisroman))
- Use service offering details to point to right hypervisor [\#125](https://github.com/MissionCriticalCloud/cosmic-core/pull/125) ([remibergsma](https://github.com/remibergsma))
- Don't let the Agent write to the configuration file. [\#124](https://github.com/MissionCriticalCloud/cosmic-core/pull/124) ([borisroman](https://github.com/borisroman))
- Porting collection of PRs from ACS 2016-04-25 [\#121](https://github.com/MissionCriticalCloud/cosmic-core/pull/121) ([remibergsma](https://github.com/remibergsma))

## [cosmic-core-5.0.1.1](https://github.com/MissionCriticalCloud/cosmic-core/tree/cosmic-core-5.0.1.1) (2016-04-26)
[Full Changelog](https://github.com/MissionCriticalCloud/cosmic-core/compare/cosmic-core-5.0.1.0...cosmic-core-5.0.1.1)

**Merged pull requests:**

- Fix/passwd server dnsmasq on master only [\#120](https://github.com/MissionCriticalCloud/cosmic-core/pull/120) ([remibergsma](https://github.com/remibergsma))
- Remove Netscaler plugin [\#119](https://github.com/MissionCriticalCloud/cosmic-core/pull/119) ([borisroman](https://github.com/borisroman))
- Remove sample storage/image and storage/volume plugin [\#118](https://github.com/MissionCriticalCloud/cosmic-core/pull/118) ([borisroman](https://github.com/borisroman))
- Fix upgrade path 5.0.0 -\> 5.0.1 [\#117](https://github.com/MissionCriticalCloud/cosmic-core/pull/117) ([remibergsma](https://github.com/remibergsma))
- Depend on latest snapshot version [\#116](https://github.com/MissionCriticalCloud/cosmic-core/pull/116) ([miguelaferreira](https://github.com/miguelaferreira))
- Remove tools/build folder as we do not use it [\#114](https://github.com/MissionCriticalCloud/cosmic-core/pull/114) ([remibergsma](https://github.com/remibergsma))
- Forceencap should be boolean in order for the method to return 'no' [\#113](https://github.com/MissionCriticalCloud/cosmic-core/pull/113) ([remibergsma](https://github.com/remibergsma))

## [cosmic-core-5.0.1.0](https://github.com/MissionCriticalCloud/cosmic-core/tree/cosmic-core-5.0.1.0) (2016-04-22)
[Full Changelog](https://github.com/MissionCriticalCloud/cosmic-core/compare/cosmic-core-5.0.0.0...cosmic-core-5.0.1.0)

**Closed issues:**

- Password server on rVPC unreliable -- works, then doesn't, then works [\#93](https://github.com/MissionCriticalCloud/cosmic-core/issues/93)

**Merged pull requests:**

- Revert "Add usage server fat jar artifact" [\#115](https://github.com/MissionCriticalCloud/cosmic-core/pull/115) ([miguelaferreira](https://github.com/miguelaferreira))
- Use default network devices in the agent.properties [\#112](https://github.com/MissionCriticalCloud/cosmic-core/pull/112) ([remibergsma](https://github.com/remibergsma))
- Use MariaDB connector for database access [\#111](https://github.com/MissionCriticalCloud/cosmic-core/pull/111) ([miguelaferreira](https://github.com/miguelaferreira))
- Remove storage plugin cloudbyte [\#110](https://github.com/MissionCriticalCloud/cosmic-core/pull/110) ([miguelaferreira](https://github.com/miguelaferreira))
- Speedup iptables by prefetching the variables [\#109](https://github.com/MissionCriticalCloud/cosmic-core/pull/109) ([remibergsma](https://github.com/remibergsma))
- Enable IPv6 connectivity for agents to mgt server [\#108](https://github.com/MissionCriticalCloud/cosmic-core/pull/108) ([remibergsma](https://github.com/remibergsma))
- Add usage server fat jar artifact [\#107](https://github.com/MissionCriticalCloud/cosmic-core/pull/107) ([michaelandersen](https://github.com/michaelandersen))
- Remove reporting section from pom [\#106](https://github.com/MissionCriticalCloud/cosmic-core/pull/106) ([miguelaferreira](https://github.com/miguelaferreira))
- Have patchviasocket.pl use socat to make it more reliable [\#105](https://github.com/MissionCriticalCloud/cosmic-core/pull/105) ([remibergsma](https://github.com/remibergsma))
- Fix tests  [\#104](https://github.com/MissionCriticalCloud/cosmic-core/pull/104) ([bheuvel](https://github.com/bheuvel))
- Skip JavaDoc generation [\#103](https://github.com/MissionCriticalCloud/cosmic-core/pull/103) ([miguelaferreira](https://github.com/miguelaferreira))
- Fix Parent version on the pom file [\#102](https://github.com/MissionCriticalCloud/cosmic-core/pull/102) ([wilderrodrigues](https://github.com/wilderrodrigues))
- Refactor/remove lxc plugin [\#101](https://github.com/MissionCriticalCloud/cosmic-core/pull/101) ([bheuvel](https://github.com/bheuvel))
- Fix log and config path for security\_group.py [\#100](https://github.com/MissionCriticalCloud/cosmic-core/pull/100) ([borisroman](https://github.com/borisroman))
- Remove/vmware remaining code [\#99](https://github.com/MissionCriticalCloud/cosmic-core/pull/99) ([wilderrodrigues](https://github.com/wilderrodrigues))
- test\_portforward\_remove.py to test issue \#91 [\#98](https://github.com/MissionCriticalCloud/cosmic-core/pull/98) ([remibergsma](https://github.com/remibergsma))
- Make Marvin SSH output pretty \(and remove duplicates\) [\#97](https://github.com/MissionCriticalCloud/cosmic-core/pull/97) ([remibergsma](https://github.com/remibergsma))
- Fix creation of private gateway with NSX when LSWitch does not exist [\#96](https://github.com/MissionCriticalCloud/cosmic-core/pull/96) ([miguelaferreira](https://github.com/miguelaferreira))
- Make passwd server work reliable on redundant VPCs [\#95](https://github.com/MissionCriticalCloud/cosmic-core/pull/95) ([remibergsma](https://github.com/remibergsma))
- Make MASTER detection for RVR similar to RVPC [\#94](https://github.com/MissionCriticalCloud/cosmic-core/pull/94) ([bheuvel](https://github.com/bheuvel))
- Guest network RVR is on eth2 [\#89](https://github.com/MissionCriticalCloud/cosmic-core/pull/89) ([bheuvel](https://github.com/bheuvel))
- Fix rVPC multi tiers test [\#88](https://github.com/MissionCriticalCloud/cosmic-core/pull/88) ([wilderrodrigues](https://github.com/wilderrodrigues))
- Fix private gateway acl integration test [\#87](https://github.com/MissionCriticalCloud/cosmic-core/pull/87) ([miguelaferreira](https://github.com/miguelaferreira))
- Fix test\_04 rvpc\_network\_garbage\_collector\_nics [\#86](https://github.com/MissionCriticalCloud/cosmic-core/pull/86) ([borisroman](https://github.com/borisroman))
- Rename variable from 'vm' to virtual\_machine' [\#85](https://github.com/MissionCriticalCloud/cosmic-core/pull/85) ([wilderrodrigues](https://github.com/wilderrodrigues))
- Remove tools/appliance [\#83](https://github.com/MissionCriticalCloud/cosmic-core/pull/83) ([remibergsma](https://github.com/remibergsma))
- Remove vagrant [\#82](https://github.com/MissionCriticalCloud/cosmic-core/pull/82) ([remibergsma](https://github.com/remibergsma))
- Remove usage/distro folder [\#81](https://github.com/MissionCriticalCloud/cosmic-core/pull/81) ([remibergsma](https://github.com/remibergsma))
- Remove agent/distro folder [\#80](https://github.com/MissionCriticalCloud/cosmic-core/pull/80) ([remibergsma](https://github.com/remibergsma))
- remove docker [\#79](https://github.com/MissionCriticalCloud/cosmic-core/pull/79) ([remibergsma](https://github.com/remibergsma))
- Removes the plugins that are neither used nor have a proper test environment  [\#78](https://github.com/MissionCriticalCloud/cosmic-core/pull/78) ([wilderrodrigues](https://github.com/wilderrodrigues))
- Update version of parent module of development modules... [\#77](https://github.com/MissionCriticalCloud/cosmic-core/pull/77) ([miguelaferreira](https://github.com/miguelaferreira))
- Set default networkDomain to empty instead of username [\#76](https://github.com/MissionCriticalCloud/cosmic-core/pull/76) ([remibergsma](https://github.com/remibergsma))

## [cosmic-core-5.0.0.0](https://github.com/MissionCriticalCloud/cosmic-core/tree/cosmic-core-5.0.0.0) (2016-03-25)
**Implemented enhancements:**

- Map ldap group to account [\#1](https://github.com/MissionCriticalCloud/cosmic-core/pull/1) ([borisroman](https://github.com/borisroman))

**Fixed bugs:**

- Make deleting static routes in private gw work [\#29](https://github.com/MissionCriticalCloud/cosmic-core/pull/29) ([remibergsma](https://github.com/remibergsma))
- Make /32 static routes for private gw work [\#27](https://github.com/MissionCriticalCloud/cosmic-core/pull/27) ([remibergsma](https://github.com/remibergsma))
- Applies changes from PR 1358 already merged onto ACS [\#22](https://github.com/MissionCriticalCloud/cosmic-core/pull/22) ([wilderrodrigues](https://github.com/wilderrodrigues))
- CLOUDSTACK-9256 add unique key for static routes in json [\#21](https://github.com/MissionCriticalCloud/cosmic-core/pull/21) ([remibergsma](https://github.com/remibergsma))
- Add replace.properties [\#11](https://github.com/MissionCriticalCloud/cosmic-core/pull/11) ([borisroman](https://github.com/borisroman))
- The build folder is required to build packages [\#5](https://github.com/MissionCriticalCloud/cosmic-core/pull/5) ([remibergsma](https://github.com/remibergsma))

**Merged pull requests:**

- Add Maven release mechanism to Cosmic Core [\#75](https://github.com/MissionCriticalCloud/cosmic-core/pull/75) ([wilderrodrigues](https://github.com/wilderrodrigues))
- Refactor validateState method to utils [\#74](https://github.com/MissionCriticalCloud/cosmic-core/pull/74) ([miguelaferreira](https://github.com/miguelaferreira))
- Reimplement router.redundant.vrrp.interval setting [\#73](https://github.com/MissionCriticalCloud/cosmic-core/pull/73) ([remibergsma](https://github.com/remibergsma))
- Remove temporary file if it exists [\#72](https://github.com/MissionCriticalCloud/cosmic-core/pull/72) ([miguelaferreira](https://github.com/miguelaferreira))
- Create destination file if it doesn't exists [\#71](https://github.com/MissionCriticalCloud/cosmic-core/pull/71) ([miguelaferreira](https://github.com/miguelaferreira))
- Refactor local template downlaoder [\#70](https://github.com/MissionCriticalCloud/cosmic-core/pull/70) ([miguelaferreira](https://github.com/miguelaferreira))
- Formatting and replace fail by assert [\#69](https://github.com/MissionCriticalCloud/cosmic-core/pull/69) ([miguelaferreira](https://github.com/miguelaferreira))
- Print stack traces instead of array with stack trace lines [\#68](https://github.com/MissionCriticalCloud/cosmic-core/pull/68) ([miguelaferreira](https://github.com/miguelaferreira))
- Fix problem when removing tiers [\#67](https://github.com/MissionCriticalCloud/cosmic-core/pull/67) ([remibergsma](https://github.com/remibergsma))
- Redundant passwd server [\#66](https://github.com/MissionCriticalCloud/cosmic-core/pull/66) ([remibergsma](https://github.com/remibergsma))
- CLOUDSTACK-9285 Make the Agent reconnect instead of die [\#65](https://github.com/MissionCriticalCloud/cosmic-core/pull/65) ([remibergsma](https://github.com/remibergsma))
- Improve error message when creating port forwarding rule [\#64](https://github.com/MissionCriticalCloud/cosmic-core/pull/64) ([remibergsma](https://github.com/remibergsma))
- Applies the commits from MCCloud to Cosmic [\#63](https://github.com/MissionCriticalCloud/cosmic-core/pull/63) ([wilderrodrigues](https://github.com/wilderrodrigues))
- Remove vmware plugin [\#62](https://github.com/MissionCriticalCloud/cosmic-core/pull/62) ([miguelaferreira](https://github.com/miguelaferreira))
- Remove Juniper SRX plugin [\#61](https://github.com/MissionCriticalCloud/cosmic-core/pull/61) ([miguelaferreira](https://github.com/miguelaferreira))
- Replace cloudstack-common with cosmic-common [\#60](https://github.com/MissionCriticalCloud/cosmic-core/pull/60) ([borisroman](https://github.com/borisroman))
- Revert "Restore build/ directory" [\#59](https://github.com/MissionCriticalCloud/cosmic-core/pull/59) ([miguelaferreira](https://github.com/miguelaferreira))
- Restore build/ directory [\#58](https://github.com/MissionCriticalCloud/cosmic-core/pull/58) ([miguelaferreira](https://github.com/miguelaferreira))
- Rename cloudstack to cosmic in serviceConfig.py [\#57](https://github.com/MissionCriticalCloud/cosmic-core/pull/57) ([borisroman](https://github.com/borisroman))
- Change cloudstack-setup-agent to cosmic-setup-agent [\#56](https://github.com/MissionCriticalCloud/cosmic-core/pull/56) ([borisroman](https://github.com/borisroman))
- Revert "Merge pull request \#1094 from nvazquez/sharedNiciraNVP" [\#55](https://github.com/MissionCriticalCloud/cosmic-core/pull/55) ([miguelaferreira](https://github.com/miguelaferreira))
- Change all agent related paths to be under dir cosmic [\#54](https://github.com/MissionCriticalCloud/cosmic-core/pull/54) ([miguelaferreira](https://github.com/miguelaferreira))
- Updated the README file [\#53](https://github.com/MissionCriticalCloud/cosmic-core/pull/53) ([wilderrodrigues](https://github.com/wilderrodrigues))
- Define variable in pom for plugins to use [\#52](https://github.com/MissionCriticalCloud/cosmic-core/pull/52) ([miguelaferreira](https://github.com/miguelaferreira))
- First part of the Java 8 + Maven refactor [\#51](https://github.com/MissionCriticalCloud/cosmic-core/pull/51) ([wilderrodrigues](https://github.com/wilderrodrigues))
- Correct location of build.properties [\#50](https://github.com/MissionCriticalCloud/cosmic-core/pull/50) ([borisroman](https://github.com/borisroman))
- Remove travis.yml [\#49](https://github.com/MissionCriticalCloud/cosmic-core/pull/49) ([borisroman](https://github.com/borisroman))
- Remove wix/windows support [\#48](https://github.com/MissionCriticalCloud/cosmic-core/pull/48) ([borisroman](https://github.com/borisroman))
- Remove devcloud folder from vagrant [\#47](https://github.com/MissionCriticalCloud/cosmic-core/pull/47) ([borisroman](https://github.com/borisroman))
- Remove ngui [\#46](https://github.com/MissionCriticalCloud/cosmic-core/pull/46) ([borisroman](https://github.com/borisroman))
- Remove devcloud functionality [\#45](https://github.com/MissionCriticalCloud/cosmic-core/pull/45) ([borisroman](https://github.com/borisroman))
- Remove git folder [\#44](https://github.com/MissionCriticalCloud/cosmic-core/pull/44) ([borisroman](https://github.com/borisroman))
- Remove jira folder [\#43](https://github.com/MissionCriticalCloud/cosmic-core/pull/43) ([borisroman](https://github.com/borisroman))
- Remove bugs-wiki folder [\#42](https://github.com/MissionCriticalCloud/cosmic-core/pull/42) ([borisroman](https://github.com/borisroman))
- Remove empty cli folder [\#41](https://github.com/MissionCriticalCloud/cosmic-core/pull/41) ([borisroman](https://github.com/borisroman))
- Remove eclipse folder [\#40](https://github.com/MissionCriticalCloud/cosmic-core/pull/40) ([borisroman](https://github.com/borisroman))
- Remove syslog alert plugin [\#39](https://github.com/MissionCriticalCloud/cosmic-core/pull/39) ([borisroman](https://github.com/borisroman))
- Remove snmp-alert plugin [\#38](https://github.com/MissionCriticalCloud/cosmic-core/pull/38) ([borisroman](https://github.com/borisroman))
- Moves the UI and Client modules into their own submodules [\#37](https://github.com/MissionCriticalCloud/cosmic-core/pull/37) ([wilderrodrigues](https://github.com/wilderrodrigues))
- Remove quickcloud module [\#36](https://github.com/MissionCriticalCloud/cosmic-core/pull/36) ([borisroman](https://github.com/borisroman))
- Makes MidoNet compliant with KVM refactor [\#35](https://github.com/MissionCriticalCloud/cosmic-core/pull/35) ([wilderrodrigues](https://github.com/wilderrodrigues))
- Remove cloud-cli folder [\#34](https://github.com/MissionCriticalCloud/cosmic-core/pull/34) ([borisroman](https://github.com/borisroman))
- Remove dns-notifier network plugin [\#33](https://github.com/MissionCriticalCloud/cosmic-core/pull/33) ([borisroman](https://github.com/borisroman))
- Set indexes on cloud.event table [\#31](https://github.com/MissionCriticalCloud/cosmic-core/pull/31) ([remibergsma](https://github.com/remibergsma))
- Removes the packaging directory from cosmic-core [\#30](https://github.com/MissionCriticalCloud/cosmic-core/pull/30) ([wilderrodrigues](https://github.com/wilderrodrigues))
- Display hostname the VPC router runs on [\#28](https://github.com/MissionCriticalCloud/cosmic-core/pull/28) ([remibergsma](https://github.com/remibergsma))
- Move XenServer plugin [\#26](https://github.com/MissionCriticalCloud/cosmic-core/pull/26) ([wilderrodrigues](https://github.com/wilderrodrigues))
- Ui fixes cloudstack upstream 20160128 [\#25](https://github.com/MissionCriticalCloud/cosmic-core/pull/25) ([remibergsma](https://github.com/remibergsma))
- Removes KVM plugin [\#24](https://github.com/MissionCriticalCloud/cosmic-core/pull/24) ([wilderrodrigues](https://github.com/wilderrodrigues))
- Removes ACS checkstyle module and its references [\#23](https://github.com/MissionCriticalCloud/cosmic-core/pull/23) ([wilderrodrigues](https://github.com/wilderrodrigues))
- Remove Brocade network plugin [\#20](https://github.com/MissionCriticalCloud/cosmic-core/pull/20) ([borisroman](https://github.com/borisroman))
- Remove OVM3 sourcecode from cosmic-core [\#19](https://github.com/MissionCriticalCloud/cosmic-core/pull/19) ([wilderrodrigues](https://github.com/wilderrodrigues))
- Correct order of TABLE removal [\#18](https://github.com/MissionCriticalCloud/cosmic-core/pull/18) ([borisroman](https://github.com/borisroman))
- Run the tests [\#16](https://github.com/MissionCriticalCloud/cosmic-core/pull/16) ([wilderrodrigues](https://github.com/wilderrodrigues))
- Remove BigSwitch plugin [\#15](https://github.com/MissionCriticalCloud/cosmic-core/pull/15) ([borisroman](https://github.com/borisroman))
- Remove NetApp plugin [\#14](https://github.com/MissionCriticalCloud/cosmic-core/pull/14) ([borisroman](https://github.com/borisroman))
- Refactor/core project name pom files [\#13](https://github.com/MissionCriticalCloud/cosmic-core/pull/13) ([wilderrodrigues](https://github.com/wilderrodrigues))
- Removes "impatient" profile [\#12](https://github.com/MissionCriticalCloud/cosmic-core/pull/12) ([wilderrodrigues](https://github.com/wilderrodrigues))
- Ui fixes cloudstack upstream 20160124 [\#10](https://github.com/MissionCriticalCloud/cosmic-core/pull/10) ([remibergsma](https://github.com/remibergsma))
- Add upgrade DB path 4.8.0 -\> 5.0.0 [\#9](https://github.com/MissionCriticalCloud/cosmic-core/pull/9) ([borisroman](https://github.com/borisroman))
- Updated pom files to propagate groupId and version [\#8](https://github.com/MissionCriticalCloud/cosmic-core/pull/8) ([borisroman](https://github.com/borisroman))
- Refactor cosmic-core pom.xml [\#7](https://github.com/MissionCriticalCloud/cosmic-core/pull/7) ([michaelandersen](https://github.com/michaelandersen))
- Revert "Merge pull request \#2 from MissionCriticalCloud/CLOUDSTACK-9142" [\#6](https://github.com/MissionCriticalCloud/cosmic-core/pull/6) ([borisroman](https://github.com/borisroman))
- CLOUDSTACK-8885 [\#4](https://github.com/MissionCriticalCloud/cosmic-core/pull/4) ([borisroman](https://github.com/borisroman))
- CLOUDSTACK-8860: improve error messages in VM deployment code path. [\#3](https://github.com/MissionCriticalCloud/cosmic-core/pull/3) ([borisroman](https://github.com/borisroman))
- CLOUDSTACK-9142 [\#2](https://github.com/MissionCriticalCloud/cosmic-core/pull/2) ([borisroman](https://github.com/borisroman))



\* *This Change Log was automatically generated by [github_changelog_generator](https://github.com/skywinder/Github-Changelog-Generator)*