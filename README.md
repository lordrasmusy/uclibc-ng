

# uClibc-ng Git Version Testing Fork

This fork is intended for testing the current Git version of uClibc-ng in various configurations. We will be testing combinations of architecture, compiler, kernel, and configuration to ensure its functionality.

To utilize GitHub Actions for testing, you can simply create a pull request.

In case of any errors, you can download the archive artifacts. It contains the kernel, toolchain, and configuration files that were used in the testing.

The toolchains have been built for Ubuntu 22.04 but may also work on other distributions.

Feel free to contribute and help improve uClibc-ng by testing it in different setups.



Discord : https://discord.gg/x7xm7EXW


Upstream Links

https://uclibc-ng.org/

https://cgit.uclibc-ng.org/cgi/cgit/uclibc-ng.git/

|Arch  |Status|Testsuite Image|Test Result|
|------|------|------|------|
|aarch64-4.19.56|[![aarch64-4.19.56](https://img.shields.io/github/actions/workflow/status/lordrasmus/uclibc-ng/make-aarch64-4.19.56.yml?style=flat)](https://github.com/lordrasmus/uclibc-ng/actions/workflows/make-aarch64-4.19.56.yml)|:white_check_mark:|[![aarch64-4.19.56test](https://gist.githubusercontent.com/lordrasmus/867aa95ade60fa5b1ad098fa6c6a1968/raw/aarch64-4.19.56_test_result.svg)](https://gist.githubusercontent.com/lordrasmus/867aa95ade60fa5b1ad098fa6c6a1968/raw/aarch64-4.19.56_test_result.txt)
|alpha-4.19.56|[![alpha-4.19.56](https://img.shields.io/github/actions/workflow/status/lordrasmus/uclibc-ng/make-alpha-4.19.56.yml?style=flat)](https://github.com/lordrasmus/uclibc-ng/actions/workflows/make-alpha-4.19.56.yml)|:white_check_mark:|[![alpha-4.19.56test](https://gist.githubusercontent.com/lordrasmus/867aa95ade60fa5b1ad098fa6c6a1968/raw/alpha-4.19.56_test_result.svg)](https://gist.githubusercontent.com/lordrasmus/867aa95ade60fa5b1ad098fa6c6a1968/raw/alpha-4.19.56_test_result.txt)
|arc|[![arc](https://img.shields.io/github/actions/workflow/status/lordrasmus/uclibc-ng/make-arc.yml?style=flat)](https://github.com/lordrasmus/uclibc-ng/actions/workflows/make-arc.yml)|:white_check_mark:|:x:
|arm-cortex-a7|[![arm-cortex-a7](https://img.shields.io/github/actions/workflow/status/lordrasmus/uclibc-ng/make-arm.yml?style=flat)](https://github.com/lordrasmus/uclibc-ng/actions/workflows/make-arm.yml)|:white_check_mark:|[![arm-cortex-a7test](https://gist.githubusercontent.com/lordrasmus/867aa95ade60fa5b1ad098fa6c6a1968/raw/arm-cortex-a7_test_result.svg)](https://gist.githubusercontent.com/lordrasmus/867aa95ade60fa5b1ad098fa6c6a1968/raw/arm-cortex-a7_test_result.txt)
|avr32-4.4.302|[![avr32-4.4.302](https://img.shields.io/github/actions/workflow/status/lordrasmus/uclibc-ng/make-avr32.yml?style=flat)](https://github.com/lordrasmus/uclibc-ng/actions/workflows/make-avr32.yml)|:white_check_mark:|:x:
|bfin|[![bfin](https://img.shields.io/github/actions/workflow/status/lordrasmus/uclibc-ng/make-bfin.yml?style=flat)](https://github.com/lordrasmus/uclibc-ng/actions/workflows/make-bfin.yml)|:white_check_mark:|:x:
|c6x|[![c6x](https://img.shields.io/github/actions/workflow/status/lordrasmus/uclibc-ng/make-c6x.yml?style=flat)](https://github.com/lordrasmus/uclibc-ng/actions/workflows/make-c6x.yml)|:x:|:x:
|cris|[![cris](https://img.shields.io/github/actions/workflow/status/lordrasmus/uclibc-ng/make-cris.yml?style=flat)](https://github.com/lordrasmus/uclibc-ng/actions/workflows/make-cris.yml)|:white_check_mark:|:x:
|csky|[![csky](https://img.shields.io/github/actions/workflow/status/lordrasmus/uclibc-ng/make-csky.yml?style=flat)](https://github.com/lordrasmus/uclibc-ng/actions/workflows/make-csky.yml)|:x:|:x:
|h8300|[![h8300](https://img.shields.io/github/actions/workflow/status/lordrasmus/uclibc-ng/make-h8300.yml?style=flat)](https://github.com/lordrasmus/uclibc-ng/actions/workflows/make-h8300.yml)|:x:|:x:
|hppa|[![hppa](https://img.shields.io/github/actions/workflow/status/lordrasmus/uclibc-ng/make-hppa.yml?style=flat)](https://github.com/lordrasmus/uclibc-ng/actions/workflows/make-hppa.yml)|:white_check_mark:|[![hppatest](https://gist.githubusercontent.com/lordrasmus/867aa95ade60fa5b1ad098fa6c6a1968/raw/hppa_test_result.svg)](https://gist.githubusercontent.com/lordrasmus/867aa95ade60fa5b1ad098fa6c6a1968/raw/hppa_test_result.txt)
|ia64|[![ia64](https://img.shields.io/github/actions/workflow/status/lordrasmus/uclibc-ng/make-ia64.yml?style=flat)](https://github.com/lordrasmus/uclibc-ng/actions/workflows/make-ia64.yml)|:white_check_mark:|:x:
|kvx|[![kvx](https://img.shields.io/github/actions/workflow/status/lordrasmus/uclibc-ng/make-kvx.yml?style=flat)](https://github.com/lordrasmus/uclibc-ng/actions/workflows/make-kvx.yml)|:white_check_mark:|[![kvxtest](https://gist.githubusercontent.com/lordrasmus/867aa95ade60fa5b1ad098fa6c6a1968/raw/kvx_test_result.svg)](https://gist.githubusercontent.com/lordrasmus/867aa95ade60fa5b1ad098fa6c6a1968/raw/kvx_test_result.txt)
|m68k|[![m68k](https://img.shields.io/github/actions/workflow/status/lordrasmus/uclibc-ng/make-m68k.yml?style=flat)](https://github.com/lordrasmus/uclibc-ng/actions/workflows/make-m68k.yml)|:white_check_mark:|[![m68ktest](https://gist.githubusercontent.com/lordrasmus/867aa95ade60fa5b1ad098fa6c6a1968/raw/m68k_test_result.svg)](https://gist.githubusercontent.com/lordrasmus/867aa95ade60fa5b1ad098fa6c6a1968/raw/m68k_test_result.txt)
|microblazeel|[![microblazeel](https://img.shields.io/github/actions/workflow/status/lordrasmus/uclibc-ng/make-microblazeel.yml?style=flat)](https://github.com/lordrasmus/uclibc-ng/actions/workflows/make-microblazeel.yml)|:white_check_mark:|:x:
|mips32el|[![mips32el](https://img.shields.io/github/actions/workflow/status/lordrasmus/uclibc-ng/make-mips32el.yml?style=flat)](https://github.com/lordrasmus/uclibc-ng/actions/workflows/make-mips32el.yml)|:white_check_mark:|[![mips32eltest](https://gist.githubusercontent.com/lordrasmus/867aa95ade60fa5b1ad098fa6c6a1968/raw/mips32el_test_result.svg)](https://gist.githubusercontent.com/lordrasmus/867aa95ade60fa5b1ad098fa6c6a1968/raw/mips32el_test_result.txt)
|mips64-n32-4.19.56|[![mips64-n32-4.19.56](https://img.shields.io/github/actions/workflow/status/lordrasmus/uclibc-ng/make-mips64-n32-4.19.56.yml?style=flat)](https://github.com/lordrasmus/uclibc-ng/actions/workflows/make-mips64-n32-4.19.56.yml)|:white_check_mark:|[![mips64-n32-4.19.56test](https://gist.githubusercontent.com/lordrasmus/867aa95ade60fa5b1ad098fa6c6a1968/raw/mips64-n32-4.19.56_test_result.svg)](https://gist.githubusercontent.com/lordrasmus/867aa95ade60fa5b1ad098fa6c6a1968/raw/mips64-n32-4.19.56_test_result.txt)
|mips64-n32-6.1.60|[![mips64-n32-6.1.60](https://img.shields.io/github/actions/workflow/status/lordrasmus/uclibc-ng/make-mips64-n32-6.1.60.yml?style=flat)](https://github.com/lordrasmus/uclibc-ng/actions/workflows/make-mips64-n32-6.1.60.yml)|:white_check_mark:|[![mips64-n32-6.1.60test](https://gist.githubusercontent.com/lordrasmus/867aa95ade60fa5b1ad098fa6c6a1968/raw/mips64-n32-6.1.60_test_result.svg)](https://gist.githubusercontent.com/lordrasmus/867aa95ade60fa5b1ad098fa6c6a1968/raw/mips64-n32-6.1.60_test_result.txt)
|mips64-n64-6.1.60|[![mips64-n64-6.1.60](https://img.shields.io/github/actions/workflow/status/lordrasmus/uclibc-ng/make-mips64-n64-6.1.60.yml?style=flat)](https://github.com/lordrasmus/uclibc-ng/actions/workflows/make-mips64-n64-6.1.60.yml)|:white_check_mark:|[![mips64-n64-6.1.60test](https://gist.githubusercontent.com/lordrasmus/867aa95ade60fa5b1ad098fa6c6a1968/raw/mips64-n64-6.1.60_test_result.svg)](https://gist.githubusercontent.com/lordrasmus/867aa95ade60fa5b1ad098fa6c6a1968/raw/mips64-n64-6.1.60_test_result.txt)
|mips64el-n32-4.19.56|[![mips64el-n32-4.19.56](https://img.shields.io/github/actions/workflow/status/lordrasmus/uclibc-ng/make-mips64le-n32-4.19.56.yml?style=flat)](https://github.com/lordrasmus/uclibc-ng/actions/workflows/make-mips64le-n32-4.19.56.yml)|:white_check_mark:|[![mips64el-n32-4.19.56test](https://gist.githubusercontent.com/lordrasmus/867aa95ade60fa5b1ad098fa6c6a1968/raw/mips64el-n32-4.19.56_test_result.svg)](https://gist.githubusercontent.com/lordrasmus/867aa95ade60fa5b1ad098fa6c6a1968/raw/mips64el-n32-4.19.56_test_result.txt)
|mips64el-n32-6.1.60|[![mips64el-n32-6.1.60](https://img.shields.io/github/actions/workflow/status/lordrasmus/uclibc-ng/make-mips64le-n32-6.1.60.yml?style=flat)](https://github.com/lordrasmus/uclibc-ng/actions/workflows/make-mips64le-n32-6.1.60.yml)|:white_check_mark:|[![mips64el-n32-6.1.60test](https://gist.githubusercontent.com/lordrasmus/867aa95ade60fa5b1ad098fa6c6a1968/raw/mips64el-n32-6.1.60_test_result.svg)](https://gist.githubusercontent.com/lordrasmus/867aa95ade60fa5b1ad098fa6c6a1968/raw/mips64el-n32-6.1.60_test_result.txt)
|mips64le-n64-6.1.60|[![mips64le-n64-6.1.60](https://img.shields.io/github/actions/workflow/status/lordrasmus/uclibc-ng/make-mips64le-n64-6.1.60.yml?style=flat)](https://github.com/lordrasmus/uclibc-ng/actions/workflows/make-mips64le-n64-6.1.60.yml)|:white_check_mark:|[![mips64le-n64-6.1.60test](https://gist.githubusercontent.com/lordrasmus/867aa95ade60fa5b1ad098fa6c6a1968/raw/mips64le-n64-6.1.60_test_result.svg)](https://gist.githubusercontent.com/lordrasmus/867aa95ade60fa5b1ad098fa6c6a1968/raw/mips64le-n64-6.1.60_test_result.txt)
|nds32le|[![nds32le](https://img.shields.io/github/actions/workflow/status/lordrasmus/uclibc-ng/make-nds32le.yml?style=flat)](https://github.com/lordrasmus/uclibc-ng/actions/workflows/make-nds32le.yml)|:white_check_mark:|:x:
|nios2|[![nios2](https://img.shields.io/github/actions/workflow/status/lordrasmus/uclibc-ng/make-nios2.yml?style=flat)](https://github.com/lordrasmus/uclibc-ng/actions/workflows/make-nios2.yml)|:white_check_mark:|[![nios2test](https://gist.githubusercontent.com/lordrasmus/867aa95ade60fa5b1ad098fa6c6a1968/raw/nios2_test_result.svg)](https://gist.githubusercontent.com/lordrasmus/867aa95ade60fa5b1ad098fa6c6a1968/raw/nios2_test_result.txt)
|or1k|[![or1k](https://img.shields.io/github/actions/workflow/status/lordrasmus/uclibc-ng/make-or1k.yml?style=flat)](https://github.com/lordrasmus/uclibc-ng/actions/workflows/make-or1k.yml)|:white_check_mark:|[![or1ktest](https://gist.githubusercontent.com/lordrasmus/867aa95ade60fa5b1ad098fa6c6a1968/raw/or1k_test_result.svg)](https://gist.githubusercontent.com/lordrasmus/867aa95ade60fa5b1ad098fa6c6a1968/raw/or1k_test_result.txt)
|powerpc|[![powerpc](https://img.shields.io/github/actions/workflow/status/lordrasmus/uclibc-ng/make-powerpc.yml?style=flat)](https://github.com/lordrasmus/uclibc-ng/actions/workflows/make-powerpc.yml)|:white_check_mark:|[![powerpctest](https://gist.githubusercontent.com/lordrasmus/867aa95ade60fa5b1ad098fa6c6a1968/raw/powerpc_test_result.svg)](https://gist.githubusercontent.com/lordrasmus/867aa95ade60fa5b1ad098fa6c6a1968/raw/powerpc_test_result.txt)
|riscv32-4.19.56|[![riscv32-4.19.56](https://img.shields.io/github/actions/workflow/status/lordrasmus/uclibc-ng/make-riscv32-4.19.56.yml?style=flat)](https://github.com/lordrasmus/uclibc-ng/actions/workflows/make-riscv32-4.19.56.yml)|:white_check_mark:|:x:
|riscv64-shared|[![riscv64-shared](https://img.shields.io/github/actions/workflow/status/lordrasmus/uclibc-ng/make-riscv64-shared.yml?style=flat)](https://github.com/lordrasmus/uclibc-ng/actions/workflows/make-riscv64-shared.yml)|:white_check_mark:|[![riscv64-sharedtest](https://gist.githubusercontent.com/lordrasmus/867aa95ade60fa5b1ad098fa6c6a1968/raw/riscv64-shared_test_result.svg)](https://gist.githubusercontent.com/lordrasmus/867aa95ade60fa5b1ad098fa6c6a1968/raw/riscv64-shared_test_result.txt)
|riscv64-static|[![riscv64-static](https://img.shields.io/github/actions/workflow/status/lordrasmus/uclibc-ng/make-riscv64-static.yml?style=flat)](https://github.com/lordrasmus/uclibc-ng/actions/workflows/make-riscv64-static.yml)|:white_check_mark:|[![riscv64-statictest](https://gist.githubusercontent.com/lordrasmus/867aa95ade60fa5b1ad098fa6c6a1968/raw/riscv64-static_test_result.svg)](https://gist.githubusercontent.com/lordrasmus/867aa95ade60fa5b1ad098fa6c6a1968/raw/riscv64-static_test_result.txt)
|sh2-4.19.56|[![sh2-4.19.56](https://img.shields.io/github/actions/workflow/status/lordrasmus/uclibc-ng/make-sh2-4.19.56.yml?style=flat)](https://github.com/lordrasmus/uclibc-ng/actions/workflows/make-sh2-4.19.56.yml)|:white_check_mark:|:x:
|sh4-4.19.56|[![sh4-4.19.56](https://img.shields.io/github/actions/workflow/status/lordrasmus/uclibc-ng/make-sh4-4.19.56.yml?style=flat)](https://github.com/lordrasmus/uclibc-ng/actions/workflows/make-sh4-4.19.56.yml)|:white_check_mark:|[![sh4-4.19.56test](https://gist.githubusercontent.com/lordrasmus/867aa95ade60fa5b1ad098fa6c6a1968/raw/sh4-4.19.56_test_result.svg)](https://gist.githubusercontent.com/lordrasmus/867aa95ade60fa5b1ad098fa6c6a1968/raw/sh4-4.19.56_test_result.txt)
|sparc64-4.19.56|[![sparc64-4.19.56](https://img.shields.io/github/actions/workflow/status/lordrasmus/uclibc-ng/make-sparc64-4.19.56.yml?style=flat)](https://github.com/lordrasmus/uclibc-ng/actions/workflows/make-sparc64-4.19.56.yml)|:white_check_mark:|[![sparc64-4.19.56test](https://gist.githubusercontent.com/lordrasmus/867aa95ade60fa5b1ad098fa6c6a1968/raw/sparc64-4.19.56_test_result.svg)](https://gist.githubusercontent.com/lordrasmus/867aa95ade60fa5b1ad098fa6c6a1968/raw/sparc64-4.19.56_test_result.txt)
|sparc_linuxthreads-4.19.56|[![sparc_linuxthreads-4.19.56](https://img.shields.io/github/actions/workflow/status/lordrasmus/uclibc-ng/make-sparc_linuxthreads-4.19.56.yml?style=flat)](https://github.com/lordrasmus/uclibc-ng/actions/workflows/make-sparc_linuxthreads-4.19.56.yml)|:white_check_mark:|[![sparc_linuxthreads-4.19.56test](https://gist.githubusercontent.com/lordrasmus/867aa95ade60fa5b1ad098fa6c6a1968/raw/sparc_linuxthreads-4.19.56_test_result.svg)](https://gist.githubusercontent.com/lordrasmus/867aa95ade60fa5b1ad098fa6c6a1968/raw/sparc_linuxthreads-4.19.56_test_result.txt)
|sparc_nptl-4.19.56|[![sparc_nptl-4.19.56](https://img.shields.io/github/actions/workflow/status/lordrasmus/uclibc-ng/make-sparc_nptl-4.19.56.yml?style=flat)](https://github.com/lordrasmus/uclibc-ng/actions/workflows/make-sparc_nptl-4.19.56.yml)|:white_check_mark:|[![sparc_nptl-4.19.56test](https://gist.githubusercontent.com/lordrasmus/867aa95ade60fa5b1ad098fa6c6a1968/raw/sparc_nptl-4.19.56_test_result.svg)](https://gist.githubusercontent.com/lordrasmus/867aa95ade60fa5b1ad098fa6c6a1968/raw/sparc_nptl-4.19.56_test_result.txt)
|tile-4.14.311|[![tile-4.14.311](https://img.shields.io/github/actions/workflow/status/lordrasmus/uclibc-ng/make-tile-4.14.311.yml?style=flat)](https://github.com/lordrasmus/uclibc-ng/actions/workflows/make-tile-4.14.311.yml)|:white_check_mark:|:x:
|x86|[![x86](https://img.shields.io/github/actions/workflow/status/lordrasmus/uclibc-ng/make-x86.yml?style=flat)](https://github.com/lordrasmus/uclibc-ng/actions/workflows/make-x86.yml)|:white_check_mark:|[![x86test](https://gist.githubusercontent.com/lordrasmus/867aa95ade60fa5b1ad098fa6c6a1968/raw/x86_test_result.svg)](https://gist.githubusercontent.com/lordrasmus/867aa95ade60fa5b1ad098fa6c6a1968/raw/x86_test_result.txt)
|x86_64|[![x86_64](https://img.shields.io/github/actions/workflow/status/lordrasmus/uclibc-ng/make-x86_64.yml?style=flat)](https://github.com/lordrasmus/uclibc-ng/actions/workflows/make-x86_64.yml)|:white_check_mark:|[![x86_64test](https://gist.githubusercontent.com/lordrasmus/867aa95ade60fa5b1ad098fa6c6a1968/raw/x86_64_test_result.svg)](https://gist.githubusercontent.com/lordrasmus/867aa95ade60fa5b1ad098fa6c6a1968/raw/x86_64_test_result.txt)
|x86_64-vdso|[![x86_64-vdso](https://img.shields.io/github/actions/workflow/status/lordrasmus/uclibc-ng/make-x86_64-vdso.yml?style=flat)](https://github.com/lordrasmus/uclibc-ng/actions/workflows/make-x86_64-vdso.yml)|:white_check_mark:|:x:
|xtensa-4.19.56|[![xtensa-4.19.56](https://img.shields.io/github/actions/workflow/status/lordrasmus/uclibc-ng/make-xtensa-4.19.56.yml?style=flat)](https://github.com/lordrasmus/uclibc-ng/actions/workflows/make-xtensa-4.19.56.yml)|:white_check_mark:|[![xtensa-4.19.56test](https://gist.githubusercontent.com/lordrasmus/867aa95ade60fa5b1ad098fa6c6a1968/raw/xtensa-4.19.56_test_result.svg)](https://gist.githubusercontent.com/lordrasmus/867aa95ade60fa5b1ad098fa6c6a1968/raw/xtensa-4.19.56_test_result.txt)
|xtensa-no-mmu-4.19.56|[![xtensa-no-mmu-4.19.56](https://img.shields.io/github/actions/workflow/status/lordrasmus/uclibc-ng/make-xtensa-no-mmu-4.19.56.yml?style=flat)](https://github.com/lordrasmus/uclibc-ng/actions/workflows/make-xtensa-no-mmu-4.19.56.yml)|:x:|:x:
