---
layout: container-breadcrumb
title: Changelog
permalink: /logs/changelog/
---

# Linux Kernel Functional Testing (LKFT) Changelog

This log is a high level overview of changes in the LKFT environment and
infrastructure.

## 2018

- 2018-08-01: Added fast 'sanity' test for all trees in LKFT. These can be seen
  at [qa-reports.l.o/lkft](https://qa-reports.linaro.org/lkft/), and provide a
  reliable and quick check for each tree. These run in addition to the full set
  of tests for each push to each tree.
- 2018-08-01: [qa-reports](https://qa-reports.linaro.org/) upgraded to [SQUAD
  0.48](https://github.com/Linaro/squad/blob/master/CHANGELOG.md)
- 2018-07-24: Added Linux build status using Clang to lkft.linaro.org homepage
- 2018-07-19: OpenEmbedded build moved from Morty to Rocko
- 2018-07-16: [qa-reports](https://qa-reports.linaro.org/) upgraded to [SQUAD
  0.47](https://github.com/Linaro/squad/blob/master/CHANGELOG.md)
- 2018-07-06: [LTP Open
  Posix](https://github.com/linux-test-project/ltp/tree/master/testcases/open_posix_testsuite)
  tests added to LKFT on all branches
- 2018-07-05: [qa-reports](https://qa-reports.linaro.org/) upgraded to [SQUAD
  0.46](https://github.com/Linaro/squad/blob/master/CHANGELOG.md)
- 2018-07-04: Dropped 4.16 per [upstream
  announcement](https://lwn.net/Articles/758269/)
- 2018-06-13: Upgrade kselftest version that's run against all stable kernels
  to 4.17
- 2018-06-11: Add 4.17 kernel branch
- 2018-06-01: [qa-reports](https://qa-reports.linaro.org/) upgraded to [SQUAD
  0.45](https://github.com/Linaro/squad/blob/master/CHANGELOG.md)
- 2018-05-30: LTP upgraded to [20180515
  release](https://github.com/linux-test-project/ltp/releases).
- 2018-05-25: [LTP CVE
  tests](https://github.com/linux-test-project/ltp/blob/master/runtest/cve)
  added to LKFT.
- 2018-05-16: QEMU upgraded to 2.12.0, solving performance issues seen on arm64
  and especially arm32.
- 2018-05-14: [qa-reports](https://qa-reports.linaro.org/) upgraded to [SQUAD
  0.44](https://github.com/Linaro/squad/blob/master/CHANGELOG.md)
- 2018-05-07: [qa-reports](https://qa-reports.linaro.org/) upgraded to [SQUAD
  0.43](https://github.com/Linaro/squad/blob/master/CHANGELOG.md)
- 2018-04-27: [qa-reports](https://qa-reports.linaro.org/) upgraded to [SQUAD
  0.42](https://github.com/Linaro/squad/blob/master/CHANGELOG.md)
- 2018-04-25: Dropped 4.15 per [upstream
  announcement](https://lwn.net/Articles/752061/)
- 2018-04-23: [qa-reports](https://qa-reports.linaro.org/) migrated to
  high-availability architecture
- 2018-04-20: Dropped non-RC stable trees from LKFT. The RC branches already
  receive every release, so tracking the stable branch separately was
  duplicative.
- 2018-04-19: [qa-reports](https://qa-reports.linaro.org/) upgraded to [SQUAD
  0.41](https://github.com/Linaro/squad/blob/master/CHANGELOG.md)
- 2018-04-18: Enabled QEMU arm64 and QEMU arm32 environments
- 2018-04-18: kselftest version that is run against all stable branches updated
  from 4.15 to 4.16.
- 2018-04-06: Enabled 4.16 stable branch
- 2018-03-16: Added additional kselftest runs using vsyscall modes 'native' and
  'none' (the default is mode 'emulate').
- 2018-03-16: [qa-reports](https://qa-reports.linaro.org/) upgraded to [SQUAD
  0.40](https://github.com/Linaro/squad/blob/master/CHANGELOG.md)
- 2018-03-09: Kselftest skipfile is now using a [single YAML
  file](https://git.linaro.org/qa/test-definitions.git/tree/automated/linux/kselftest/skipfile-lkft.yaml)
- 2018-03-02: [qa-reports](https://qa-reports.linaro.org/) upgraded to SQUAD
  0.39
- 2018-03-02: QEMU x86_64 added to lkft
- 2018-03-02: DragonBoard 410c added to lkft
- 2018-02-23: [qa-reports](https://qa-reports.linaro.org/) upgraded to SQUAD
  0.38. See https://github.com/Linaro/squad/blob/master/CHANGELOG.md#038
- 2018-02-16: LTP upgraded to 20180118
- 2018-02-16: QEMU jobs in staging for arm64 and x86-64
- 2018-02-09: kselftest version that is run against all stable branches updated
  from 4.14 to 4.15.
- 2018-02-02: [qa-reports](https://qa-reports.linaro.org/) updated to include
  full and per-test logs
- 2018-02-02: LTP skipfile now using a [single YAML
  file](https://git.linaro.org/qa/test-definitions.git/tree/automated/linux/ltp/skipfile-lkft.yaml)
- 2018-02-02: 4.15 is now building and testing
- 2018-02-02: Android projects moved to /lkft-android/
- 2018-01-19: Juno boards changed to use SSD drives over SATA, rather than USB
  thumbdrives for temporary storage when running LTP. This should reduce false
  failures on I/O related tests.
- 2018-01-12: [LKFT LAVA](https://lkft.validation.linaro.org/) upgraded to
  Debian Stretch and LAVA 2018.01.
- 2018-01-05: x86 environments now running LTP on local disk instead of NFS.
  All NFS-related skips have been re-enabled.
- 2018-01-05: b2260 board added to staging environment.

