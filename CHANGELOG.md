# CHANGELOG

## In development

- Replaced all individual snippet indices with 'this' keyword [#221](https://github.com/nre-learning/nrelabs-curriculum/pull/221)
- Rename syringe.yaml to lesson.meta.yaml, and move lessons into descriptive subdirs [#222](https://github.com/nre-learning/nrelabs-curriculum/pull/222)
- Prepare curriculum for collections [#224](https://github.com/nre-learning/nrelabs-curriculum/pull/224)
- Update all paths with new lesson directory mount point [#227](https://github.com/nre-learning/nrelabs-curriculum/pull/227)

## v0.3.3 - July 9, 2019

### Curriculum

- Added stage 4 to the "Network Automation with Salt" Lesson-30. This stage will explain how to configure Junos devices using Salt.

## v0.3.2 - April 19, 2019

- Three new lessons [#217](https://github.com/nre-learning/nrelabs-curriculum/pull/217)
  - Added new "Automated Device Inventory" Lesson-33. Use PyEz & YAML to automate device inventory.
  - Added new "Automated Configuration Backup" Lesson-34. Use PyEz & YAML to automate configuration backups.
  - Added new "Device Specific Template Generation" Lesson-35. Use PyEz, Jinja2 & YAML to generate and push templates.

## v0.3.1 - March 27, 2019

### Curriculum

- Adding Lesson-26 Vendor-Neutral Network Configuration with OpenConfig [#191](https://github.com/nre-learning/nrelabs-curriculum/pull/191)
- New "Terraform and Junos" Lesson [#184](https://github.com/nre-learning/nrelabs-curriculum/pull/184)
- New "Juniper Extension Toolkit (JET)" Lesson [#173])(https://github.com/nre-learning/nrelabs-curriculum/pull/173)

### Other

- Added new community page, in place of the much lighter 'resources' page [#199](https://github.com/nre-learning/nrelabs-curriculum/pull/199)
- Removed unneeded subnet declarations from connections list [#200](https://github.com/nre-learning/nrelabs-curriculum/pull/200)
- Introduce new "configurator" for configuring devices, and templatize mgmt interface configuration  [#207](https://github.com/nre-learning/nrelabs-curriculum/pull/207)

## v0.3.0 - February 11, 2019

### Curriculum

- Adding more metadata to all lessons for Advisor functionality [#172](https://github.com/nre-learning/nrelabs-curriculum/pull/172)
- Greatly improve and expand the NAPALM lesson [#175](https://github.com/nre-learning/nrelabs-curriculum/pull/175)
- Modify NAPALM lesson to use new verification capabilities [#178](https://github.com/nre-learning/nrelabs-curriculum/pull/178)
- Add lesson for STIG validation using JSNAPY and NAPALM [#181](https://github.com/nre-learning/nrelabs-curriculum/pull/181)

### Other

- Remove LLDP configurations globally for now [#182](https://github.com/nre-learning/nrelabs-curriculum/pull/182)

## 0.2.0 - January 24, 2019

### Curriculum

- Adding Lesson-15 Event-Driven Network Automation with StackStorm [#126](https://github.com/nre-learning/nrelabs-curriculum/pull/126)
- Clarify internet access restrictions in REST API lesson and docs [#148](https://github.com/nre-learning/nrelabs-curriculum/pull/148)
- Updated YAML lesson to be less of a Juniper commercial [#161](https://github.com/nre-learning/nrelabs-curriculum/pull/161)
- Document howto check spin up progress and find the UI URL [#166](https://github.com/nre-learning/nrelabs-curriculum/pull/166)

### Other

- Simplified authentication by using consistent credentials, statically [#143](https://github.com/nre-learning/nrelabs-curriculum/pull/143)
- Remove lab guide from lesson definitions [#146](https://github.com/nre-learning/nrelabs-curriculum/pull/146)
- Cleaned up and enabled LLDP within the `vqfx` image [#147](https://github.com/nre-learning/nrelabs-curriculum/pull/147)
- Enable LLDP end-to-end [#150](https://github.com/nre-learning/nrelabs-curriculum/pull/150)
- Added better docs for Syringe environment variables [#160](https://github.com/nre-learning/nrelabs-curriculum/pull/160)
- Moved to a custom githelper image for making lesson repo available in pods with correct permissions [#162](https://github.com/nre-learning/nrelabs-curriculum/pull/162)

## 0.1.4 - January 08, 2019

### Curriculum

- Re-open the NAPALM lesson, now that iframes are working properly [#141](https://github.com/nre-learning/nrelabs-curriculum/pull/141)

### Other

- Added maintenance mode for antidote. Directs to a static page hosted on GCP bucket. [#144](https://github.com/nre-learning/nrelabs-curriculum/pull/144)
- Added new image `utility-vm`, which provides a VM for the few lessons that require it (i.e. Docker) [#142](https://github.com/nre-learning/nrelabs-curriculum/pull/142)

## 0.1.3 - November 15, 2018

### Curriculum

- Adding Lesson-24 Junos Automation with PyEZ (jnpr-raylam)[#117](https://github.com/nre-learning/nrelabs-curriculum/pull/117)
- Adding Lesson-30 Working with Salt [#114](https://github.com/nre-learning/nrelabs-curriculum/pull/114)
- Adding Lesson-16 Jinja2 Templates [#121](https://github.com/nre-learning/nrelabs-curriculum/pull/121)
- Adding Lesson-29 Robot Framework [#125](https://github.com/nre-learning/nrelabs-curriculum/pull/125)

### Other

- Tidied up lesson definitions based on recent syringe changes [#129](https://github.com/nre-learning/nrelabs-curriculum/pull/129)

## 0.1.1 - October 28, 2018

### Curriculum

- Fixed typos in YAML lesson (change) - [#109](https://github.com/nre-learning/nrelabs-curriculum/pull/109) (contributed by pklimai)

### Other

- Significant restructuring of docs, and large improvements to contribution pages [#108](https://github.com/nre-learning/nrelabs-curriculum/pull/108)
- Added "tier" field to all syringe files [#116](https://github.com/nre-learning/nrelabs-curriculum/pull/116)

## v0.1.0

- Initial release, announced and made public at NXTWORK 2018 in Las Vegas
