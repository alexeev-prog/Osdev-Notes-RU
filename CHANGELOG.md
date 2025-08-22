commit db000a8884f4cfddb4ff548adebdf5d7dfbb5c2a
Author: Alexeev Bronislav <alexeev.dev@mail.ru>
Date:   Sat Aug 23 05:22:34 2025 +0700

    translate 00_introduction

commit 30ea1fead210ad6ba9cdc57a1d472569b7e7411d
Author: Immanuel Daviel A. Garcia <34188635+AlexDev404@users.noreply.github.com>
Date:   Thu Jul 31 08:11:27 2025 -0600

    Fix typo on line 172 of Interrupt Handling section (#126)
    
    * Fix typo on line 172 of Interrupt Handling section
    
    * Update 05_InterruptHandling.md
    
    * Update I_Acknowledgments.md

commit ee7e1690155c80a19a92d8e2654be74061acdf5e
Author: belka-ew <belka@caraus.de>
Date:   Mon Jul 28 15:23:08 2025 +0200

    Fix a few typos in the linker script part (#125)

commit 5aa23cd1cf98ec4eec17ef7607a352f1ab858fa5
Author: Immanuel Daviel A. Garcia <34188635+AlexDev404@users.noreply.github.com>
Date:   Sun Jul 27 00:47:15 2025 -0600

    Fix typo on line 22 of Interrupt Handling section (#124)

commit 890086e4f0d39b35a76093bbdcc989d5ca82ca8c
Author: Knud <113939798+KnudAndersen@users.noreply.github.com>
Date:   Thu Jul 24 13:56:47 2025 -0500

    Page Fault Vector Typo (#123)
    
    * Page Fault Vector Typo
    
    * Femtoseconds conversion
    
    * RSDP Typo
    
    The signature for the RSDP is "RSD PTR ", and it is not an SDT.
    
    https://uefi.org/specs/ACPI/6.5/05_ACPI_Software_Programming_Model.html?highlight=rsdt#root-system-description-table-rsdt
    
    * APIC Address Incorrect
    
    Fixed the description of the APIC address (the physaddr is not shifted, but the lower bits are masked), and fixed a typo with the location. On my ``qemu-system-x86_64``, the LAPIC base is 0xFEE00000 in physical memory.
    
    * Latex-style exponent
    
    * C struct syntax error
    
    You need to create a entry in the symbol table to reference a C-object itself, e.g. for self-referencing in a struct

commit f36ac62d24566678f448d9ae1efc3b8999d48071
Author: Pratik Devkota <119331464+sudw1n@users.noreply.github.com>
Date:   Mon Jul 21 16:44:24 2025 +0545

    Fix mistakes in "Processes and Threads" (#122)
    
    * fix typo in Scheduler
    
    * define segment selector values in GDT
    
    * use proper macro for segment selector in "Processes and Threads"
    
    * fix missing KERNEL_DS instead of KERNEL_SS in "Processes and Threads"

commit de4a06cf86ec664a5db70a6bcabec116745d1729
Author: Ivan G. <dreamos82@yahoo.it>
Date:   Fri Jul 11 09:59:35 2025 +0100

    Update README.md (#120)
    
    * Update README.md
    
    * Update README.md

commit 6ef44be381495acec298b9e268d3934919fb6218
Author: Pratik Devkota <119331464+sudw1n@users.noreply.github.com>
Date:   Fri Jul 11 14:16:52 2025 +0545

    Update build.sh to use /usr/bin/env shebang (#121)
    
    * use /usr/bin/env in build.sh shebang
    
    * fix typos in code for heap initialization
    
    * fix typo in heap initialization

commit 03a9d6abd63626a86f1954c0a79853257988bf04
Author: Pratik Devkota <119331464+sudw1n@users.noreply.github.com>
Date:   Thu Jul 10 00:33:22 2025 +0545

    Fix mistakes/typos in "Heap Allocation" (#119)
    
    * fix wording about third_alloc() in "Heap Allocation"
    
    * update wording in "Heap Allocation"
    
    * fix incorrect variable name in "Heap Allocation"
    
    * fix typos in "Heap Allocation"

commit c97ae7c1230aff547adb89ed1ff60763bf27b8c2
Author: Ivan G. <dreamos82@yahoo.it>
Date:   Fri Jul 4 13:25:38 2025 +0100

    Improvements to cross compiler instructions (#118)
    
    * Update E_Cross_Compilers.md
    
    * Update E_Cross_Compilers.md
    
    * Update E_Cross_Compilers.md
    
    * Update E_Cross_Compilers.md
    
    * Update E_Cross_Compilers.md
    
    * Update E_Cross_Compilers.md
    
    Changes requested.

commit 2843ea404b87428cefc2ae777dcabb2c8bbb27dd
Author: Pratik Devkota <119331464+sudw1n@users.noreply.github.com>
Date:   Wed Jun 4 16:08:55 2025 +0545

    Fix typo in "Virtual Memory Manager" (#117)
    
    * Fix typo in "Virtual Memory Manager"
    
    * Fix typo in "Heap Allocation"
    
    * Update Acknowledgements

commit a00bc60b20f3a60920f5b0c3ebb441874f349a65
Author: Antonin Ruan <43148004+AntoninRuan@users.noreply.github.com>
Date:   Sat May 31 17:42:05 2025 +0200

    Fix informations in Userspace/Handling_Interrupts (#115)
    
    * fix informations in tss struct and layout of tss system descriptor
    
    * add AntoninRuan in acknowledgments

commit 8165f5258277b40ecdec144c526f6b96d91f8b39
Author: Pratik Devkota <119331464+sudw1n@users.noreply.github.com>
Date:   Thu May 29 13:15:22 2025 +0545

    Fix typos in keyboard driver chapters (#116)
    
    * fix(architecture): typo in "Add Keyboard Support"
    
    * fix(architecture): `SHIFT_MASK` instead of `CTRL_MASK` in chapter 17

commit d61927d535475bce7966d9fb84ce4745f8569589
Author: Vasileios Almpanis <90504973+vasilisalmpanis@users.noreply.github.com>
Date:   Thu Mar 6 17:06:27 2025 +0100

    osdev: userspace: switching modes fix wrong order (#112)

commit c673c5d71edb780ee50db92ec652ad516fd01934
Author: Ivan Gualandri <dreamos82@yahoo.it>
Date:   Sun Feb 23 13:14:54 2025 +0000

    improve formatting of systemcalls chapter

commit d285ddd589f280c04a4f43aa313c9c73b7f18270
Author: NerdNextDoor <73440604+IAmTheNerdNextDoor@users.noreply.github.com>
Date:   Wed Feb 12 22:34:12 2025 +0000

    Update I_Acknowledgments.md for new username (#111)

commit 1016632306206b3eb585fea82701893c4185b0b3
Author: Ivan G. <dreamos82@yahoo.it>
Date:   Sun Jan 19 11:25:49 2025 +0000

    Minor typo fixes, and table syntax fixes (#110)

commit c6d97a8ba2b82bab33a30efa134996ec6a2de277
Author: Ivan G. <59960116+dreamos82@users.noreply.github.com>
Date:   Sun Jan 19 11:14:04 2025 +0000

    Update J_Updates.md (#109)

commit f38606df96c8c09081b40d5fe72656d8942ddebc
Author: MrMasterKeyboard <73440604+AFellowSpeedrunner@users.noreply.github.com>
Date:   Sat Dec 28 01:09:34 2024 +0000

    Typo fixes for Makefile and linker in "Build Process" chapter (#107)
    
    * Fix makefile typos in the "GNU Makefiles" page of "Build Process"
    
    * Fix linker typo in "Linker Scripts" page of "Build Process"
    
    * Update I_Acknowledgments.md to include me
    
    * Remove -shared and -ffreestanding from LD_FLAGS var

commit ad2bea163dbaf0309b13842110ee423231197c03
Author: mrjbom <37502620+mrjbom@users.noreply.github.com>
Date:   Wed Dec 25 02:41:40 2024 +0300

    Typo fix in 07_APIC.md (#106)

commit 565fb693c95d60bf541297a082cff407a8b9cd01
Author: mrjbom <37502620+mrjbom@users.noreply.github.com>
Date:   Tue Dec 17 16:28:21 2024 +0300

    Addition to 07_APIC.md (#105)

commit 02dbd810295e52c357f13168b2727143422a7472
Author: Ivan G. <59960116+dreamos82@users.noreply.github.com>
Date:   Tue Dec 17 00:17:51 2024 +0000

    Add a complete example of how to create an executable for our kernel (#104)
    
    * Add a complete example of how to create an executable for our kernel
    
    * Update 02_Loading_And_Running.md

commit edb122a466a435f24fc2a323be63aab4137783e1
Author: Ivan G. <59960116+dreamos82@users.noreply.github.com>
Date:   Mon Dec 16 12:35:29 2024 +0000

    Update 02_Boot_Protocols.md

commit f548482e9b4bdb77bceb2efc419d0094279908a3
Author: Ivan G. <59960116+dreamos82@users.noreply.github.com>
Date:   Thu Oct 24 23:04:31 2024 +0100

    Change runners (ubuntu-latest -> ubuntu-24) (#102)
    
    * Try to remove pandoc workaround
    
    * Try to force 24.04
    
    * Revert to run only on master

commit fc318802f4fdb764ada770923c0eac7dc8272d96
Author: Ivan G. <59960116+dreamos82@users.noreply.github.com>
Date:   Thu Oct 24 22:36:45 2024 +0100

    Replace stivale2 protocol with limine (#101)
    
    * overview: update from stivale to limine protocol
    
    * Replace stivale 2 protocol (cont)
    
    * Stivale2 replacement, cont...
    
    * replace stivale2 cont.
    
    * replace stivale2 cont.
    
    * stivale replacement (cont)
    
    * stivale replacement cont...
    
    * Update updates
    
    * Fix typo
    
    * Changes requested
    
    * Changes requested
    
    * Minor changes
    
    * Minor fix

commit b7869de7dc8b11e2596f3c6029b4ab21d6bd79d2
Author: Max Tyson <98maxt98@gmail.com>
Date:   Fri Oct 11 21:24:47 2024 +1300

    Fix broken link & Qemu Monitor Over Telnet (#100)
    
    * Fix Broken Link | H_Useful_Resources.md
    
    * Tellnet | F_Debugging.md
    
    * Styling Fixes | Update F_Debugging.md
    
    * Consistency | Update F_Debugging.md

commit 8f5871511f61e31f517859f7b39d08b3ac764183
Author: Kouosi Takayama <152291607+kouosi@users.noreply.github.com>
Date:   Mon Oct 7 21:29:17 2024 +0545

    Fix: typos (#99)
    
    * fix: typo
    
    * fix: remove trailing spaces
    
    * fix: Even more typos
    
    * fix: revise typos according to feedback
    
    * fix: typo limine.cfg + heading

commit 68726ca3ac90ece1cdd9bd20c10459d06adb7090
Author: hogarth <mallet.gaetan@hotmail.fr>
Date:   Mon Sep 9 06:29:44 2024 +0200

    fix: paging address space calculation (#98)

commit 8969dac21df0461bfe48284e3ec58b60914fdb75
Author: Ivan G. <59960116+dreamos82@users.noreply.github.com>
Date:   Sun Sep 8 11:16:48 2024 +0100

    Test markdown detection (#96)
    
    * Add markdown detection as language
    
    * Update FUNDING.yml
    
    * Update README.md
    
    Update some parts of the readme, removing text staitng that was a work in progress.
    
    * Typo fixes
    
    * Fix typo in boot protocols chapter
    
    * Minor fixes on boot protocl chapter
    
    * Add detail for gdb
    
    * Fix error in cross comiler character
    
    * Update updates

commit 7b4257dae82c55c885e76f67f2cbfe1a8b6e9ea1
Author: Hannah <53470737+Hqnnqh@users.noreply.github.com>
Date:   Sun Aug 25 14:00:50 2024 +0200

    Fix typos in Architecture chapter (#97)

commit ab5caf03e1ac790b3837d711f60862850abd7c09
Author: Hannah <53470737+Hqnnqh@users.noreply.github.com>
Date:   Wed Aug 21 15:48:38 2024 +0200

    Fix typos in Memory Management chapter (#95)
    
    * Fix typos in Memory Management chapter
    
    * Fix typos in Heap Allocation Chapter
    
    * Add name to acknowledgements

commit de83517e5401d9719af0611fc02c80f88e119c23
Author: Ivan Gualandri <dreamos82@yahoo.it>
Date:   Sat Aug 17 21:19:15 2024 +0100

    Minor typo fixes

commit cfeeffc1cef06b021821d0252daca9ec9842e7b1
Author: andromdaa <59896970+andromdaa@users.noreply.github.com>
Date:   Sat Aug 3 14:49:47 2024 -0400

    Fix typo in Build Process chapter (#94)

commit ed9255f209af26f47ff3d5f978a1037bb70ab62f
Author: Roxve <116169309+Roxve@users.noreply.github.com>
Date:   Thu Jul 18 23:50:44 2024 +0300

    fixed a small typo (#93)
    
    02_Architecture/08_Timers.md:
    - changed 'ot' to 'to' in local APIC section
    this is a really small typo but it confused me a bit

commit f713f86e32764de5a9796089be82f5d60539cdbb
Author: Ivan Gualandri <dreamos82@yahoo.it>
Date:   Thu Jun 27 19:56:01 2024 +0100

    Update updates

commit 487f793e204205713288a58fee7b497f1ac7e375
Author: Matteo Rosato <85708462+MRRcode979@users.noreply.github.com>
Date:   Tue Jun 25 15:08:44 2024 -0400

    Update Acknowledgements (#92)
    
    * Update I_Acknowledgments.md

commit 5d49e89d244dab7ff3ad671431527fa71ae7a168
Author: Matteo Rosato <85708462+MRRcode979@users.noreply.github.com>
Date:   Tue Jun 25 14:16:50 2024 -0400

    Change "xorisso" typos to "xorriso" (#91)
    
    Thanks for the PR!

commit 128578dc0927246fea076008462afbe77e873a41
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Thu Jun 20 10:56:06 2024 +0100

    Fixes on framebuffer chapter (#90)
    
    * Fixes on frambeuffer chapter
    
    * Fix typo

commit ce27ce20d1fa75c936cc1bc042bb16629163bef6
Author: ShiningLea <anerruption@disroot.org>
Date:   Tue Jun 4 23:16:53 2024 +0200

    Add missing bits for tables in Paging document (#89)
    
    * Add missing bits for tables in Paging document
    
    * Add note about PK's existence
    
    * Add myself in acknowledgments

commit 1a02d1ec386c6469d4b8536efb0b270779ff3547
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Tue May 14 07:39:01 2024 +0100

    Debugging minor changes (#88)
    
    * Minor fixes in the appendices section
    
    * minor syntax fix to acpi chapter
    
    * clarify length field in acpisdt header
    
    * Fix file name (issue #86)
    
    * minor changes to memory management section
    
    * Minor changes to heap chapter
    
    * Requested changes

commit cd440f3339ccc66bbf20b2c3e305cfd62b15deae
Author: Alex <40271862+Moldytzu@users.noreply.github.com>
Date:   Wed May 1 09:49:31 2024 +0300

    rewrite syscall/sysret section (#87)
    
    * rewrite syscall/sysret section
    
    * fix spelling and terminology
    
    * clarify choice of fmask's magic value

commit 063411f4dacf4b64ce5f81449d3d9a66b4244381
Author: Ivan Gualandri <dreamos82@yahoo.it>
Date:   Fri Apr 19 14:34:14 2024 +0100

    Update release date

commit bb2cb22ba2da28b8dbb24839fef7f00c013bb102
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Mon Mar 25 23:01:35 2024 +0000

    Add what to verify section (#85)
    
    * Add what to verify section
    
    * Fix syntax
    
    * Minor updates to verify paragraph in elf part
    
    * Update updates
    
    * Fix broken link
    
    * Move useful info section from appendices
    
    * Changes requested
    
    * Minor fix on Nasm appendice
    
    * Minor typo fixes
    
    * Minor fix on cross compiling chapter
    
    * Minor fix on cross compile chapter
    
    * changes requested

commit 6566d6ef66dae3aa2e4b0319e410115ccd1953c2
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Sat Feb 17 11:07:56 2024 +0000

    Another round of typo fixes (#84)
    
    * Fix typo in useful resources chapter
    
    * Minor improvements to elf chapter
    
    * Requested changes

commit d05ed9b6d477e0e9fbdd2414d770a548e278e6f6
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Mon Jan 29 11:39:41 2024 +0000

    Typo fixes in userspace and FS chapters (#81)
    
    * Minor typo fixes in introduction and boot protocols chapters
    
    * Typo fixes on switching mode chapters
    
    * Typo fixes on VFS chapter
    
    * Fix typo in generating iso chapter
    
    * minor fix on virtual filesystem chapter
    
    * Expand example abi section
    
    * Fix text in userspcae chapters
    
    * Fix typo
    
    * Fix typo in tarfilesystem chapter
    
    * More fixes on tar file system chapter
    
    * Changes requested
    
    * Minor typofixes on tar file system chapter
    
    ---------
    
    Co-authored-by: r4 <dean243@hotmail.com>

commit 1391f7e0a1ca14c2bdaa857bbd8f9cee1a78e3a3
Author: Max Tyson <98maxt98@gmail.com>
Date:   Mon Jan 29 18:40:10 2024 +1300

    Fix RSDPDescriptor Mistake (#83)
    
    * Update 06_ACPITables.md
    
    * Update I_Acknowledgments.md
    
    * Update I_Acknowledgments.md

commit 45086b16f6bfd443fcc2a044a17f9c3e303fa35f
Author: ajccosta <92996262+ajccosta@users.noreply.github.com>
Date:   Mon Jan 22 20:13:53 2024 +0000

    Update 02_Boot_Protocols.md - GDT.md link was broken (#82)

commit b6e610081f60fe94a22f98cf52f64e8eff9291aa
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Sun Jan 7 18:36:52 2024 +0000

    Fix URL in readme.

commit 4349294eb0eaa499f5085fc741ec76a4f97b1d21
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Sun Jan 7 11:02:18 2024 +0000

    Update sync-gh-pages.yaml

commit 3c5923ac7080df001cdd9d50dd50c9e2b6688a40
Merge: 343233a 042119e
Author: Ivan Gualandri <dreamos82@yahoo.it>
Date:   Sat Jan 6 11:14:21 2024 +0000

    Merge branch 'master' of github.com:dreamos82/Osdev-Notes

commit 343233a3289a0e4d6487f131321f0322d5d2447d
Author: Ivan Gualandri <dreamos82@yahoo.it>
Date:   Sat Jan 6 10:55:43 2024 +0000

    Make naming coherent in syscall chapters

commit 042119eb0325e3f7d3929fa5d9fe57bfb6a1f374
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Fri Jan 5 14:04:17 2024 +0000

    Update README.md

commit 8fca6be6790693d9ef6f8f9f94e160a42c392d3f
Author: Ivan Gualandri <dreamos82@yahoo.it>
Date:   Fri Jan 5 13:50:55 2024 +0000

    Minor fixes on System Calls chapter

commit 7ab8217be0a3485aa19180e1d4e720f040ea29ba
Author: Ivan Gualandri <dreamos82@yahoo.it>
Date:   Wed Jan 3 18:40:53 2024 +0000

    Minor syntax fixes

commit 9ec8cf3ab33e9d4c22d4133053768547f9a92eb1
Author: Ivan Gualandri <dreamos82@yahoo.it>
Date:   Mon Jan 1 18:37:26 2024 +0000

    Minor syntax fixes

commit f8cfce12d358343a6bf810eec73a50721d0f0e12
Merge: 258c366 4aad718
Author: Ivan Gualandri <dreamos82@yahoo.it>
Date:   Sat Dec 30 09:39:09 2023 +0000

    Merge branch 'master' of github.com:dreamos82/Osdev-Notes

commit 258c36696fd70ac721d6bd9a9c275675ce0deb35
Author: Ivan Gualandri <dreamos82@yahoo.it>
Date:   Sat Dec 30 09:38:28 2023 +0000

    Minor tpoy and syntax fixes

commit 4aad718e5d110046c7181facfbc6af336c7421a5
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Sat Dec 23 22:47:02 2023 +0000

    Update links to readme (#80)
    
    Fix some links.

commit 624ced49a05a8ec8fa0dec61efb4759a82702b50
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Tue Dec 5 12:13:13 2023 +0000

    Update nasm chapter (#79)
    
    * Fix Examples
    
    * remove line
    
    * Add example for loopy cycle in the nasm appendix
    
    * Update updates

commit 733599f6a7f9332b39744b4be82c68e673b58e94
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Fri Dec 1 13:43:49 2023 +0000

    GDB and userspace updates
    
    * Add smoldtb and drvos to our projects
    
    * replace you with we/us in debu chapter
    
    * Fix typo
    
    * Fix titles
    
    * Add information on how to test userspace
    
    * changes requested in review
    
    * typo fix
    
    * Typo fixes
    
    * Fix typo

commit 6a97731e5ab2464d82e39bc61174174dfa5025e5
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Sun Nov 26 12:57:03 2023 +0000

    Minor fix on Interrupt_Handling (#77)

commit 86ececa895caad2545d4019aee24231e98f6b068
Author: Ivan Gualandri <dreamos82@yahoo.it>
Date:   Fri Nov 17 10:20:11 2023 +0000

    Fix tss struct and minor typo

commit 4b07e31a4a26308011d53a68355b89efe6d214a6
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Thu Nov 16 16:06:27 2023 +0000

    Start expanding the memory management part (#76)
    
    * Update 01_Overview.md
    
    * Update MM 01_Overview.md
    
    typo fix
    
    * Expoand direct map and recursion in paging chapter
    
    * Typo fixes (feeling like the Captain Julio Sham)
    
    * Changes requested in review
    
    * changes requested in review

commit e1b3f116fcd02fe3abddedd6acabc6fc9746c826
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Fri Oct 13 15:24:05 2023 +0100

    Update README.md

commit 71e85c86f528c27c1c7114b105cbf773b06884aa
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Sat Oct 7 13:34:22 2023 +0100

    Usermode fixes (#75)
    
    * Update D_Nasm.md
    
    minor typo fixes
    
    * Fix table in userspace handling interrupts chapter
    
    * Improve userspace tss descriptor table

commit 797b49a9f4e632ea078b4917e3e5ed3a489adaf3
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Wed Sep 27 17:10:42 2023 +0100

    Update D_Nasm.md (#74)
    
    minor typo fixes

commit c321915eb43af067daafb8d89ea013761807e09f
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Wed Sep 27 14:04:26 2023 +0100

    Tentative pandoc fix (#73)
    
    This should resume the release of the pdf

commit fc4799804475dded2f8432f9716e9d745207fd22
Author: Ivan Gualandri <dreamos82@yahoo.it>
Date:   Tue Sep 26 12:48:42 2023 +0100

    Fixes to user space chapters

commit dce5fa4dad903c394ecc735e904221ba5aa4e78a
Author: Marco Rubin <20150305+Rubo3@users.noreply.github.com>
Date:   Sun Sep 24 09:53:41 2023 +0000

    Style changes and grammar fixes (#67)
    
    Various typo fixes!

commit 71c8e492a73f770536f48c3422caec65714a63fd
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Sat Sep 16 13:06:27 2023 +0100

    Added fix to avoid syncing github pages when updating unrelated files (pandoc build script)

commit 18e142e117ff37d2edc3cf9b44ee8dd553c5455f
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Sat Sep 16 00:15:52 2023 +0100

    Update pandoc_workflow.yaml

commit 5aaf7a49ae4e3f897a0b727e2dd43d51c5a00460
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Sat Sep 16 00:09:23 2023 +0100

    Update pandoc_workflow.yaml

commit 29dfa78ece3f984674286b686bacf37201b85ba0
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Sat Sep 16 00:02:24 2023 +0100

    Update pandoc_workflow.yaml

commit a18d5c4c9b3d75a6651b980a31b5540e215b6333
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Fri Sep 15 22:26:43 2023 +0100

    Update pandoc_workflow.yaml

commit eefe4eb3c00a2153a94bf06c500c4154780a2ece
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Fri Sep 15 22:26:22 2023 +0100

    Update pandoc_workflow.yaml

commit 11aa71c28644cab280e7a8b65ec2b9a938bf5244
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Fri Sep 15 22:03:05 2023 +0100

    Update pandoc_workflow.yaml

commit 54cfc0802f692d739edb65227d6adb30edf42ded
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Fri Sep 15 21:50:42 2023 +0100

    Update pandoc_workflow.yaml

commit 43a940e04f71eac57f3ef994346057dfb3f0c5e2
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Fri Sep 15 21:11:38 2023 +0100

    Update pandoc_workflow.yaml

commit c14a846f78447124c59d404d93dadf97858c8592
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Fri Sep 15 21:11:11 2023 +0100

    Update pandoc_workflow.yaml

commit 8d6972bc8ad9e468f2d9aa52f77eedb1f3f189c2
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Fri Sep 15 19:23:40 2023 +0100

    Update pandoc_workflow.yaml

commit 12f000fc37b8fadad01ea28a4dcdabd39ec0ec9c
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Fri Sep 15 19:23:08 2023 +0100

    Update pandoc_workflow.yaml

commit 0a76cbc79542bdf61374aae8bc351bde5223a0d2
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Fri Sep 15 19:16:58 2023 +0100

    Update pandoc_workflow.yaml

commit b3291d231c09d1b3a26b04fffaeaf0191e8a71c6
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Fri Sep 15 12:44:07 2023 +0100

    [WIP] minor fixes to userspace chapter (#71)
    
    * minor fixes to userspace chapter
    
    * Add more detail about selectors
    
    * replace register with selector
    
    * Fix list in Switching modes chapter
    
    * minor changes on scheduler chapter
    
    * Minor changes to handling interrupt chapter (Userspace)
    
    * Minor fix on userspace/handling_interrupts
    
    * fix GDT chapter

commit 16e4b48d4750d85777458acc48763b613f75d5c9
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Fri Sep 1 01:47:45 2023 +0100

    ADD_COMMIT flag to pdf generation, and notes about recursive paging
    
    * Update build script
    
    * Expand vmm section of Prosesses and thread chapter
    
    * Set ADD_COMMIT when calling build.sh

commit b2e8dee63afc6cc95e4d9965b3222fa691392699
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Thu Aug 31 03:36:26 2023 +0100

    Fix paging chapter (#69)
    
    * Minor fixes to paging chapter
    
    * Fix typos
    
    * change requested
    
    * Fix typo

commit fafa55cd3444d337a376327e792f18599186cc90
Author: r4 <dean243@hotmail.com>
Date:   Tue Aug 29 13:25:30 2023 +0000

    IPC: Added info about lockfree queues, awkward sentence reflow. (#68)
    
    * Added info about lockfree queues, awkward sentence reflow.
    
    * Requested changes, added rubo3 to acknowledgements.

commit b8ed97d833231e2731df7a30b3498cb755bbd253
Author: Marco Rubin <20150305+Rubo3@users.noreply.github.com>
Date:   Wed Aug 23 15:36:07 2023 +0200

    Fixed link in 02 README.md (#66)
    
    Thanks! :)

commit afa52de0a0337d701ca009952f92d71f8a809300
Author: Marco Rubin <20150305+Rubo3@users.noreply.github.com>
Date:   Wed Aug 23 14:48:09 2023 +0200

    Fix typo in 01_README.md (#65)

commit 931151a17fda5dffb4405fae0d0b73dcaaf30de3
Author: Marco Rubin <20150305+Rubo3@users.noreply.github.com>
Date:   Wed Aug 23 14:45:39 2023 +0200

    Update chapter links README.md (#64)
    
    Thanks!

commit e1939ab3c188e24b5bf23e1b589f230593c2f1ec
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Tue Aug 22 14:28:03 2023 +0100

    Update 03_Processes_And_Threads.md

commit 86656c455a6e059e32f2e8a327a9be915229e25f
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Tue Aug 22 13:08:13 2023 +0100

    Fix typos and expand thread sleep chapter (#63)
    
    * Fix typos and expand thread sleep chapter
    
    * Fix typo
    
    * Update updates

commit e2c453d32d35ed81463e28a6463c4da80d76a126
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Sun Aug 20 18:46:07 2023 +0100

    Update build.sh

commit cccdca183cad01f1c91411ee2cc26d4ce983fcde
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Sun Aug 20 18:39:31 2023 +0100

    Update pandoc_workflow.yaml

commit dcd7dd8003ff78df67a80bd70d2507c1c793f5d6
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Sun Aug 20 16:14:08 2023 +0100

    Typo fixes on video output section (#62)
    
    * Typo fixes on video output section
    
    * Typo fixes

commit 6c72f061e5f8a4504207f9962f5443f3f16813d5
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Wed Aug 16 10:28:31 2023 +0100

    Update README.md

commit 358cec3a7b4b32ca9ab8b1e593b5ffdee76a8e46
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Tue Aug 15 11:02:09 2023 +0100

    Update build.sh
    
    Fix awk and build command.

commit f717043cdb8d00755745f36e9edede4ca36855d2
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Tue Aug 15 10:53:16 2023 +0100

    Update README.md (#61)
    
    Updating readme

commit c6f1a5614f7c916569fd8566bd40bfeee01e3a16
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Tue Aug 15 10:39:59 2023 +0100

    Added automation to build pdfs on release tags
    
    * Draft build script
    
    * renamed decorators, added alternate test script
    
    * Fix regex
    
    * Create pandoc_workflow.yaml
    
    * Rename test.sh in build.sh
    
    * Update pandoc_workflow.yaml
    
    Add some comments
    
    * add commit log for title page inside the book
    
    * Update pandoc_workflow.yaml
    
    * Added ignore paths
    
    ---------
    
    Co-authored-by: Dean <dean243@hotmail.com>

commit 2e87bc17e23f888e81f4242e9a4a6a5b3356af8d
Author: dean <dean243@hotmail.com>
Date:   Mon Aug 14 20:23:33 2023 +1000

    Added authors note about stack usage.

commit 7f3ebf9754a66103d8afc06641d183a69cb20ce0
Author: Ivan Gualandri <dreamos82@yahoo.it>
Date:   Thu Aug 10 14:02:29 2023 +0100

    minor fixes in memory management

commit 5c58f4d065dd5aa6fa8fe033b09dfe28e5e4ad12
Author: Ivan Gualandri <dreamos82@yahoo.it>
Date:   Wed Aug 9 13:04:02 2023 +0100

    Fix typo

commit 7c4b9ca81a73dcf0b65ee50364b6f9f5f197dd2e
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Tue Aug 8 16:18:24 2023 +0100

    Update J_Updates.md

commit 50c05d872a3aeec52668b9fb2b00004d481b7501
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Tue Aug 8 12:23:05 2023 +0100

    Add appendix chapter (#59)
    
    * add appendix chapter
    
    * Changes suggested
    
    * Other minor changes

commit edfa7e54cc02de8dba886f6e5ea9042c204846f5
Author: Ivan Gualandri <dreamos82@yahoo.it>
Date:   Thu Aug 3 19:08:46 2023 +0100

    Minor typo fixes

commit 515352ebad1ba94edc2c1023c79f0b5dba8c2d92
Author: Ivan Gualandri <dreamos82@yahoo.it>
Date:   Fri Jul 28 11:48:48 2023 +0100

    Minor syntax fix

commit 5b0b95b0bf22ca6d338b6baa69087c45eb3feaf4
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Thu Jul 6 10:09:26 2023 +0100

    Update E_Cross_Compilers.md
    
    Fix typo

commit db7a3f640aa47c93842126aecaa809a2954845e0
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Wed Jul 5 23:50:26 2023 +0100

    Add New appendix on how to build a cross compiler (#58)
    
    * Add New appendix on how to build a cross compiler
    
    * Fix in Makefile chapter
    
    * Added info on clang, grammar and sentence flow.
    
    * Typo fixes
    
    * Minor fix
    
    ---------
    
    Co-authored-by: Dean <dean243@hotmail.com>

commit d67d7edaf1f04e1866fe565145d7571a7b9c6a51
Author: Ivan Gualandri <dreamos82@yahoo.it>
Date:   Sun Jul 2 17:51:36 2023 +0100

    Fix minor typos

commit 151954db772664c0e859e8438623b3bfa8c23bd1
Author: Ivan Gualandri <dreamos82@yahoo.it>
Date:   Sat Jul 1 11:00:46 2023 +0100

    Minor fix

commit b652a6839c69df68ec466e6d74608990eac0a709
Author: Ivan Gualandri <dreamos82@yahoo.it>
Date:   Fri Jun 30 15:44:43 2023 +0100

    Fix typo

commit 3d49fe44663c22c592f9088b217329e2c3bcc3ea
Author: Dean <dean243@hotmail.com>
Date:   Thu Jun 29 22:24:07 2023 +1000

    linker scripts: info about example not using LMAs

commit 0b6ffcc566b429d6378fb50d3e1f3e20e399daaa
Author: Ivan Gualandri <dreamos82@yahoo.it>
Date:   Wed Jun 28 14:04:22 2023 +0100

    Various typo fixes on Vide output part

commit 75acf2cb5bd99618a19ff8bacb18e8507b7887f9
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Fri Jun 23 13:11:35 2023 +0100

    Typo fixes and fix to memory manager example image (#56)

commit 3dd3b29929a6c7e508404f47a7e6afa7aa14fd4f
Author: Luca Francesca <luca@lucafrancesca.me>
Date:   Fri Jun 23 13:18:08 2023 +0200

    Typo in the Free() page and a missing inline code (#57)
    
    * Update 05_Heap_Allocation.md
    
    Typo in the Free() section
    
    * Update 05_Heap_Allocation.md
    
    Inline x

commit 0e1a831a6df75a8bf2213f7d1a6c6bb34f351323
Author: Ivan Gualandri <dreamos82@yahoo.it>
Date:   Tue Jun 20 15:42:13 2023 +0100

    Move nasm useful resources to its section

commit 12ad57d81058cb79b019e5d43be770267cb00316
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Tue Jun 20 10:03:56 2023 +0100

    Further linker fix (#54)
    
    * remove incomplete sentence
    
    * Add few more details about linking
    
    * minor chnges

commit 1ca9ff6977302e13f0ab6e9ebd5bd39e7fd43c39
Author: SeekBytes <seekbytes@protonmail.com>
Date:   Tue Jun 20 10:43:14 2023 +0200

    Fix typo (#55)
    
    thanks  for the fix! :)

commit 1ef8b926eda61e81fe61435f16a03a6d495a7c1c
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Mon Jun 19 06:47:01 2023 +0100

    specify what flags refer to in the linker script chapter (#53)

commit 7a5c446cedc31a06210fceac7ca2ab1164cd31ac
Merge: c61db56 a04d229
Author: Ivan Gualandri <dreamos82@yahoo.it>
Date:   Sat Jun 10 10:21:55 2023 +0100

    Merge branch 'master' of github.com:dreamos82/Osdev-Notes

commit c61db56ca3626c4a50611ca00c4c080ec1be60a9
Author: Ivan Gualandri <dreamos82@yahoo.it>
Date:   Sat Jun 10 10:21:45 2023 +0100

    Fix broken link and update acknowledgments

commit a04d22922339248da0a7f1b8b6f86912f3ab0eb3
Author: Lee Cannon <leecannon@leecannon.xyz>
Date:   Thu Jun 8 02:23:37 2023 +0100

    fix chapter title in README.md (#52)

commit 874419cdf9a8d96c7bd9e1d43677a0d612d60a18
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Wed Jun 7 18:49:10 2023 +0100

    Update README.md

commit beded8eb5e76abe512d246f00bc77e2f926f8a52
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Wed Jun 7 15:19:17 2023 +0100

    Cover acknowledgments (#50)
    
    * Add acknowledgments for the cover art
    
    * Add cover image

commit 6e96246c6ab0e732ab6b702c919c918671021f41
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Wed Jun 7 14:23:35 2023 +0100

    add info about mem and tlb for qemu monitor (#49)

commit ed52bc1addf60c71202de1ea7632dec1ab679f59
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Tue Jun 6 10:46:11 2023 +0100

    Minor layout fixes (#48)
    
    * Minor layout fixes
    
    * Replace memory manager image
    
    * Fixing indentation and line overflows
    
    * Update yaml headers with margin and image fixes
    
    ---------
    
    Co-authored-by: Dean <dean243@hotmail.com>

commit 445ae1a209933d420fb757d9fd7de71ce3477b28
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Mon Jun 5 13:40:20 2023 +0100

    Chapters review (#45)
    
    Hyper Mega merge! BOOM!

commit c867b418f6efb453210a8c44d9b714729f2ee271
Author: Zenails <128232444+zenails@users.noreply.github.com>
Date:   Thu Apr 27 20:26:45 2023 +0200

    Fixed link (#47)

commit f916f94a3afb5ad04c784a15499d832eb1912adc
Author: Ivan Gualandri <dreamos82@yahoo.it>
Date:   Sun Apr 16 12:23:01 2023 +0100

    minor typo fixes on locks chapter

commit 4138f098316ebfa728796f57d3a6a4f73bb1a641
Author: Ivan Gualandri <dreamos82@yahoo.it>
Date:   Sat Apr 15 16:18:42 2023 +0100

    Fix typos

commit 77cc6ea991dfa03591199594f830d64a280398da
Author: Ivan Gualandri <dreamos82@yahoo.it>
Date:   Sat Apr 15 12:17:29 2023 +0100

    Minor fixes

commit 2c2b46fa413708d46f7afaf47f9a07a013010dc2
Author: Ivan Gualandri <dreamos82@yahoo.it>
Date:   Sat Apr 15 12:02:12 2023 +0100

    Fix some images and going beyond chapter

commit a8634c5bc621b5dd800da941d900ac02bd8143e0
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Sat Apr 15 11:40:19 2023 +0100

    Reformat license using markdown (#44)

commit 668d471dba938cb9cfe0904b406d9579725bc454
Author: Ivan Gualandri <dreamos82@yahoo.it>
Date:   Fri Apr 14 12:49:02 2023 +0100

    minor typo fixes

commit 575cba9a58e68e1bef92e6c89858ef955ebdb53c
Author: Ivan Gualandri <dreamos82@yahoo.it>
Date:   Thu Apr 13 19:16:49 2023 +0100

    Fix formatting issue in Debugging section

commit 9f1550b70c3ee60b623c04c188e505b03760d6a4
Author: Dean T <dean243@hotmail.com>
Date:   Thu Apr 13 23:48:17 2023 +1000

    Chapter 8: Loading an ELF file (#41) and chapter rearrange
    
    Added ELF Part and All chapters are rearranged, added parts divisor, and a .pandoc folder with all the configuration stuff that are not part of the main chapters.

commit 1dd6105ba30fd757ebeca3fbe26c95c0d7a266fe
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Fri Mar 17 12:06:54 2023 +0000

    Merged refactor branch: big changes
    
    * Tidying, moved minichapters into folders
    
    * Added chapter 0, license placeholder file, file renaming.
    
    * renamed license file, added contents
    
    * added assumed knowledge, started about the authors section
    
    * added architecture intro, update higher half part
    
    * added info about structure of book
    
    * Fix introduction chapter
    
    * Add about me...
    
    * Start welcome section
    
    * Minor fix and cleanup
    
    * Add plotting pixel information
    
    * Add draw image
    
    * update framebuffer section
    
    * Fixing typos and minor updates
    
    * Expand timers section
    
    * Minor changes on ACPITables and introduction
    
    * Add PIC disable section in apic and Fix syntax on timer section
    
    * Expand APIC
    
    * expand lapic
    
    * Expand ioapic
    
    * Expand ACPI section
    
    * Minor changes
    
    * Update Introduction, and minor fixes
    
    * sentence flow, added x2apic and ipi notes
    
    * Initial work on timers
    
    * Minor changes to introduction
    
    * Expanded PIT section, began work on HPET
    
    * Add pandoc specific stuff
    
    * Fix typo
    
    * Minor updates in debugging section
    
    * Update 04_Virtual_Memory_Manager.md
    
    * Update 03_Driver_Implementation.md
    
    fix syntax
    
    * Fix Syntax
    
    * Use math rendering for formulas
    
    * forgot one formula
    
    * Fix rendering problems of some of the new formulas
    
    * timers: expanded section on hpet
    
    * more work on timers
    
    * finished timer section
    
    * sentence flow and grammar
    
    * Fixing some typos and adding some formulas
    
    * Update 02_Physical_Memory.md
    
    * Update 02_Physical_Memory.md
    
    * Update Framebuffer.md
    
    * Fix some formulas
    
    * Fix few formulas
    
    * bullet point list fixes
    
    * Replace remote stored image files with in-project files
    
    * requested changed, framebuffer updates, inline constants are now inside code blocks.
    
    * 03_Memory_Management/03_Paging.md
    
    * spelling: arent/dont
    
    ---------
    
    Co-authored-by: Dean <dean243@hotmail.com>

commit 1dc55bd30a57d24de3ca46428e8693bc70f183d4
Author: xyve <60116559+xyve7@users.noreply.github.com>
Date:   Fri Mar 10 08:29:48 2023 -0600

    some more additions to the scheduling page (#39)
    
    * dereferenced the context pointer passed
    
    * small troubleshooting tip
    
    * fixed empty line issue
    
    * Update 02_Scheduler.md
    
    fixed as per the maintainers request

commit e2652e706f5808e4a41877a1ab6fca33562960f7
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Mon Feb 20 10:54:06 2023 +0000

    Extra stuff (#40)
    
    Add extra stuff chapter

commit 773a6e986ab8acf44f300079f642a271cfa27726
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Sat Jan 28 17:32:34 2023 +0000

    Update README.md

commit 6f8a77f306be9f41f78d3af2c07794a351890783
Merge: 6b04645 0634e3d
Author: Ivan Gualandri <dreamos82@yahoo.it>
Date:   Sat Jan 21 13:04:28 2023 +0100

    Merge branch 'master' of github.com:dreamos82/Osdev-Notes

commit 6b0464589728c55da13eb406909e00e14dcfe1a4
Author: Ivan Gualandri <dreamos82@yahoo.it>
Date:   Sat Jan 21 13:04:19 2023 +0100

    Fix images path on vfs chapter

commit 0634e3d221c5e69879ac216024cf78f856b2c350
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Thu Jan 19 11:45:19 2023 +0000

    Update 03_TarFileSystem.md

commit e7692ca7cb761be9d1143486d78a8253f0525f4f
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Wed Jan 18 23:30:33 2023 +0000

    Minor syntax fixes (#38)

commit 6cf14d5af1120844aaf19100f050dfcc5efaf3ed
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Wed Jan 18 11:31:36 2023 +0000

    Expanded VFS chapter: tar driver
    
    * Start ustar chapter
    
    * Start tar header section
    
    * Explain octal conversion
    
    * Add image of tar archive
    
    * lookup function update
    
    * Finish tar lookup
    
    * Changes requested in review
    
    * Adding read paragraph
    
    * Finish tar chapter
    
    * changes requested in review
    
    * Changes requested in review
    
    * Add ramfs example
    
    * Fix syntax
    
    * Delete test.tex

commit 54de9dbff589c8a874174703c18d90d6aefd6c68
Author: xyve <60116559+xyve7@users.noreply.github.com>
Date:   Tue Jan 17 09:23:56 2023 -0600

    Update 01_README.md (#37)
    
    small spelling error

commit e454859e40df972e8fd8be639450bb99ad1c5221
Author: Dean T <dean243@hotmail.com>
Date:   Fri Dec 30 02:40:56 2022 +1100

    Chapter 6: IPC (#34)
    
    Add ipc chapter

commit c50c63b46075044f954ca30664f1227c7357cba4
Author: Ivan Gualandri <dreamos82@yahoo.it>
Date:   Tue Dec 27 15:32:37 2022 +0100

    Update readme

commit be591f7b5c4b46b3045a8977554cac310c7d93b4
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Mon Dec 26 03:49:49 2022 +0000

    Added chapter on VFS (chapter 7)
    
    * Start new VFS section
    
    * Update chapter numbering
    
    * Remove old folder
    
    * Start VFS chapter
    
    * arrayfs overview
    
    * vfs explanation
    
    * Update 02_VirtualFileSystem.md
    
    fix typo
    
    * Update 02_VirtualFileSystem.md
    
    * Update 02_VirtualFileSystem.md
    
    * Update 02_VirtualFileSystem.md
    
    * Start mountpoint paragraph
    
    * Define mountpoint_t strcuture
    
    * Update mount chapter
    
    * update mounting/umounting paragraph
    
    * add details about mounting and umounting
    
    * finish mount/umount ad add get_mountpoint_id section
    
    * Add relative path subsection
    
    * Start file open section
    
    * Working on open
    
    * Changes on the file open paragraph
    
    * Outlining file descriptor structure
    
    * Add file descriptor fields details
    
    * Nearly finished open function paragraph
    
    * update open chapter
    
    * Changes requested in review
    
    * details about close function
    
    * Start read section
    
    * Update read function
    
    * Some changes requested
    
    * Other changes requested
    
    * Finishing the Virtual File System Chapter
    
    * Remove text
    
    * Changes requesed in the review

commit 0b63250fa3920a0cec6776adfaefcc308900942a
Author: Dean <dean243@hotmail.com>
Date:   Thu Nov 10 15:40:07 2022 +1100

    memory order description update

commit d2860c3fe23c0029fb126066ebbbb1108b920273
Author: Pigmy-penguin <88971276+Pigmy-penguin@users.noreply.github.com>
Date:   Sun Sep 25 09:34:49 2022 +0200

    Spelling fixups (#33)

commit 3b3ea6d8d6341081b695d1cad7c75d27d79b2ff6
Author: Pigmy-penguin <88971276+Pigmy-penguin@users.noreply.github.com>
Date:   Sat Sep 24 17:59:26 2022 +0200

    Fix typos

commit a600dacd206120c2024584e486907897e38f14fb
Author: Ivan Gualandri <dreamos82@yahoo.it>
Date:   Mon Sep 19 18:27:39 2022 +0100

    Fix some typos

commit 952243f2834f9fb5fd16c21b0e41b8589d1e0050
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Mon Sep 19 13:01:25 2022 +0100

    Scheduling and tasks (#29)
    
    Add scheduling section!

commit 2b13a38f18bab30a7fd23ef867bd7189a48fe76b
Author: Dean <dean243@hotmail.com>
Date:   Fri Jul 15 21:05:44 2022 +1000

    spelling fixes (pushing to main, woo!)

commit 5c0d369af14660efdf5f6553e9c2efbb276fafca
Author: Dean T <dean243@hotmail.com>
Date:   Mon Jul 11 02:34:49 2022 +1000

    Updated Interrupts and GDT chapters (#31)

commit 4df659bb8a6680b9d93b11d06d7d5ea4a567e8ec
Author: Dean T <dean243@hotmail.com>
Date:   Mon Jul 4 19:02:08 2022 +1000

    Added section about userspace (#30)
    
    * branch init
    
    * working commit
    
    * working commit
    
    * Updated from master, added smp info
    
    * incremental changes
    
    * Working commit, updated names to match the rest
    
    * tweaks
    
    * Requested changes
    
    * updated userspace chapter number

commit d63dc097565f1b1b885efc2e32885e9139925a8e
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Tue Jun 14 16:56:58 2022 +0100

    Update nasm paragraph (#28)
    
    * add more details on nasm
    
    * More updates in the nasm section
    
    * Fix table
    
    * Fix links
    
    * minor fixes

commit 2099f03dddfd1a6ca2a146a073c657cdfab2fb60
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Fri Jun 10 19:09:16 2022 +0100

    Update C_Language_Info.md

commit a1b2cd2e895dcf111b69dcf4b6887556987fcaf8
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Tue Jun 7 09:35:03 2022 +0100

    add details about breakpoints and layouts (#27)
    
    * add details about breakpoints and layouts
    
    * Changes requested

commit 70f75feb2d0aa46b23a68070e59b98d6a673cf5e
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Sat Jun 4 13:43:53 2022 +0100

    Minor changes timer nasm (#26)
    
    * Add data structure section in nasm and fix on timer section
    
    * Minor fixes on nasm section
    
    * changes requested

commit 2ac48fd17f706d9e7704f65c19a071f0dfbe3436
Author: Dean <dean243@hotmail.com>
Date:   Fri Jun 3 21:28:06 2022 +1000

    Updated filenames for consistency

commit fc02acd9e9f6b750eb502a5df194e3102e5ad1cd
Author: Dean <dean243@hotmail.com>
Date:   Fri Jun 3 20:54:56 2022 +1000

    restructuring, no content changes.

commit aef70d935d2d6a19576918e71a402b4f2dca8139
Merge: d1197d1 6e45cb5
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Fri Jun 3 10:40:06 2022 +0100

    Merge pull request #23 from dreamos82/compiling_and_building_notes
    
    Adding section of notes on compiling a kernel

commit 6e45cb56ccf0f2b6624037fd2f31503b78ba8409
Author: Dean <dean243@hotmail.com>
Date:   Fri Jun 3 19:36:29 2022 +1000

    incremental commit

commit 2d719705b4e6a8441ce2f7d0f74baddd9f22788f
Merge: 0f599ab 06cee4a
Author: Dean <dean243@hotmail.com>
Date:   Fri Jun 3 17:03:28 2022 +1000

    Merge branch 'compiling_and_building_notes' of https://github.com/dreamos82/Osdev-Notes into compiling_and_building_notes

commit 0f599ab6145a6da3832da61bbfcd35a2b198c16b
Author: Dean <dean243@hotmail.com>
Date:   Fri Jun 3 17:03:25 2022 +1000

    requested changes

commit d1197d14a6de0f2fabf8d2cc3e53783bbdfd4f4a
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Thu Jun 2 10:18:22 2022 +0100

    Update FUNDING.yml

commit 06cee4a879b8848fdf384ee2973f7e9d25720062
Author: Ivan Gualandri <dreamos82@yahoo.it>
Date:   Wed Jun 1 16:59:33 2022 +0100

    Fix table style in linkerscripts section

commit e2ad27a49a81b59d595bfe8475daa8ad3fc610d1
Merge: c24f83c f4cfd1b
Author: Dean <dean243@hotmail.com>
Date:   Thu Jun 2 01:18:17 2022 +1000

    Formatting fix

commit c24f83cf8585b48502ea5acd3cbdf18cd3466fc8
Author: Dean <dean243@hotmail.com>
Date:   Thu Jun 2 01:17:29 2022 +1000

    formatting fix

commit f4cfd1ba0c026a3e7d5d11cdf3b10e3021014b5a
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Wed Jun 1 16:15:17 2022 +0100

    Update GNUMakefiles.md

commit fe22641235326c7656ea212a4ca63db9fdceca3d
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Wed Jun 1 16:11:15 2022 +0100

    Update GNUMakefiles.md

commit b231b7c410c6d35606c54e3cd3a0bbd71e9bbe7e
Author: Dean <dean243@hotmail.com>
Date:   Thu Jun 2 01:01:53 2022 +1000

    partial requested changes

commit b9af520e660ec146e6fe430bf7aed7ce38730c5c
Author: Dean <dean243@hotmail.com>
Date:   Tue May 31 16:49:59 2022 +1000

    woo! the final content commit!

commit 0daf52f10326e98282419e0b532efbbcab8ee897
Author: Dean <dean243@hotmail.com>
Date:   Mon May 30 19:49:43 2022 +1000

    requested changes

commit f19e3a48e84657fec041e02f0024c28c4bf2d3ca
Author: Dean <dean243@hotmail.com>
Date:   Mon May 30 17:28:10 2022 +1000

    minor tweaks

commit e37d38ea8933b1d8a407dcfaaba4152c21f12b7e
Author: Dean <dean243@hotmail.com>
Date:   Mon May 30 17:20:53 2022 +1000

    Added emulator section and useful links

commit e0a0fe57a102383b3652dc64fa9d2d379d10a47d
Author: Dean <dean243@hotmail.com>
Date:   Mon May 30 00:51:06 2022 +1000

    more linker script details, todos

commit 24163b4a9b0012c76e93c2be5c9323465471119e
Author: Ivan Gualandri <dreamos82@yahoo.it>
Date:   Sat May 28 12:18:00 2022 +0100

    Minor fixes on InterruptHandling paragraph

commit ee213dc4ae1e7a1670ab682633dea99efb684ff1
Author: Dean <dean243@hotmail.com>
Date:   Thu May 26 22:05:27 2022 +1000

    incremental commit: linker scripts

commit 2008a86fb81be56de0f7699b746d2357c7c810b1
Merge: f611561 95dce38
Author: Dean <dean243@hotmail.com>
Date:   Thu May 26 20:24:50 2022 +1000

    Merge branch 'compiling_and_building_notes' of https://github.com/dreamos82/Osdev-Notes into compiling_and_building_notes

commit 95dce385cf1a2e47a27ede1f8e11bd44534f2230
Merge: 71e5b81 b863182
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Thu May 26 11:16:32 2022 +0100

    Merge branch 'master' into compiling_and_building_notes

commit b86318268261cda9a40d9bfcd657761205ef96c9
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Thu May 26 11:14:10 2022 +0100

    Update README.md

commit 349d1271fee9795e6e97b5080657cb43b33f923a
Author: Ivan Gualandri <dreamos82@yahoo.it>
Date:   Sat May 21 00:19:21 2022 +0100

    Fix typo

commit f611561189d5bb34a7385e416f640bb90fc4fa71
Merge: 71e5b81 9ba5fb4
Author: Dean <dean243@hotmail.com>
Date:   Fri May 20 01:47:35 2022 +1000

    Merge branch 'master' into compiling_and_building_notes

commit 9ba5fb4b04b57d8bd2c1f3b397dbea2cda7f0e89
Author: Ivan Gualandri <dreamos82@yahoo.it>
Date:   Wed May 18 16:50:13 2022 +0100

    Fix main README paragraphs

commit a154361726b94381895dd63904157be0abf518ae
Merge: c0b0827 c57645a
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Wed May 18 16:37:42 2022 +0100

    Merge pull request #25 from dreamos82/memory_protection
    
    Added info about memory protection

commit c57645ae198647c45bac9330fef3763de7ca7c75
Author: Dean <dean243@hotmail.com>
Date:   Thu May 19 01:35:44 2022 +1000

    spelling fixes

commit b225f7ce25c7665bce14dcbe1861d6886348c15d
Author: Dean <dean243@hotmail.com>
Date:   Thu May 19 01:18:14 2022 +1000

    Added info about memory protection

commit c0b08275d51d86b0f0143e681c0b65e9f4b32139
Merge: 0980da8 34bbd0a
Author: Ivan Gualandri <dreamos82@yahoo.it>
Date:   Wed May 18 12:47:52 2022 +0100

    Merge branch 'master' of github.com:dreamos82/Osdev-Notes

commit 0980da86c19a9bba522d391ead4009d2cf514690
Author: Ivan Gualandri <dreamos82@yahoo.it>
Date:   Wed May 18 12:47:43 2022 +0100

    Remove old keyboard.md file replaced by the new keyboard section

commit 71e5b81c249bcea326b9430ad9d38478d4f25427
Merge: 7784fea 34bbd0a
Author: Dean <dean243@hotmail.com>
Date:   Wed May 18 21:05:41 2022 +1000

    Merge branch 'master' into compiling_and_building_notes

commit 7784fea9fff8b93b94bda9d9b261e3c935cefe57
Author: Dean <dean243@hotmail.com>
Date:   Wed May 18 21:05:24 2022 +1000

    requested changes + updated main readme

commit 34bbd0a70d2e81ab6406702eceda75ced74e5494
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Sun May 15 15:01:18 2022 +0100

    Update README.md

commit 35a034b34d33c3a94daa9fe80ef57682aff2c57c
Author: Ivan Gualandri <dreamos82@yahoo.it>
Date:   Sun May 15 13:49:29 2022 +0100

    Add new section to README and rename folder

commit 33d3e902430a70b85e40714d69594eff343d4698
Merge: 6a0f5ac 758b71b
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Sun May 15 13:29:58 2022 +0100

    Merge pull request #22 from dreamos82/Keyboard_info_section
    
    Keyboard info section

commit 758b71b6b77e97c5f06d17046fbb4976f2c9b54f
Author: Ivan Gualandri <dreamos82@yahoo.it>
Date:   Sun May 15 13:25:34 2022 +0100

    minor fixes

commit 9bb586e32b4cc9cea5367f37f2ab116042a23157
Author: Dean <dean243@hotmail.com>
Date:   Sun May 15 17:35:18 2022 +1000

    removed old file

commit cd95da09c07d682a0d8495ab2f2821b2b220d2a1
Merge: 543fd04 84b4678
Author: Dean <dean243@hotmail.com>
Date:   Sun May 15 17:32:15 2022 +1000

    Merge branch 'master' into compiling_and_building_notes

commit 543fd0435ac3db62a5d3b0add75d7fe8414deecb
Author: Dean <dean243@hotmail.com>
Date:   Sun May 15 17:30:05 2022 +1000

    finished section on makefiles + boot shim info.

commit 31443543c845ec527eababa542ad373bfbe2adc5
Author: Dean T <dean243@hotmail.com>
Date:   Sat May 14 19:37:12 2022 +1000

    editing and sentence flow

commit f604bfa1510a6567bc083817935068ce48fd1fa9
Author: Ivan Gualandri <dreamos82@yahoo.it>
Date:   Fri May 13 01:02:05 2022 +0100

    Changes requested in the review

commit cd28615e316349c62ae88c9aa36a28a08bc90d2a
Author: Ivan Gualandri <dreamos82@yahoo.it>
Date:   Fri May 13 00:11:42 2022 +0100

    Finish driver implementation paragraph

commit e9d2f51e76e57b05d5aa67feec0f10d3136d564d
Author: Ivan Gualandri <dreamos82@yahoo.it>
Date:   Sun May 8 01:16:50 2022 +0100

    Draft scancode translation section

commit 18b732515621157dbccbe55a97e224baa12c28b5
Author: Ivan Gualandri <dreamos82@yahoo.it>
Date:   Mon May 2 12:05:30 2022 +0100

    Rename keyboard files

commit cc2a1de07de9949840cf2838767b019570710e95
Author: Ivan Gualandri <dreamos82@yahoo.it>
Date:   Sun May 1 18:22:33 2022 +0100

    update keyboard driver section

commit 5ca7144eea830ed3d18166d8aba99e8f76abf08c
Author: Ivan Gualandri <dreamos82@yahoo.it>
Date:   Sun May 1 11:18:57 2022 +0100

    Add ctrl,alt,etc keys handling

commit 033faafb29b98a5952235c5ec1ccde9c605ba697
Author: Ivan Gualandri <dreamos82@yahoo.it>
Date:   Fri Apr 29 09:45:58 2022 +0100

    Add paragraph about multi-byte scancodes

commit 596f3532b5305d0480f02f047b273ed369d8b353
Author: Ivan Gualandri <dreamos82@yahoo.it>
Date:   Sun Apr 24 18:17:56 2022 +0100

    Update keyboard section

commit 1dab28c83d2ce0501f4b35de8b6531f98340ba82
Author: Dean <dean243@hotmail.com>
Date:   Fri Apr 22 21:05:06 2022 +1000

    incremental commit

commit 6a0f5ac2989955279caa0c010f9c5bb7f970cc2c
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Tue Apr 19 19:09:50 2022 +0100

    Update README.md

commit 72ea1544569b5c15d5c9df6808ba4f659b97376d
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Tue Apr 19 18:52:50 2022 +0100

    Update FUNDING.yml

commit 9c309b0bd4844d31ec1d91febf5abdc8ee457b38
Author: Ivan Gualandri <dreamos82@yahoo.it>
Date:   Mon Apr 18 19:41:27 2022 +0100

    Create keyboard section

commit e92c8c439b09b625e7df55e0e6f9178fa0741fa1
Author: Ivan Gualandri <dreamos82@yahoo.it>
Date:   Wed Apr 13 15:23:15 2022 +0100

    Start draft of keyboard section

commit dd411b23b0a97fefab71fc24eac63defe3061643
Author: Ivan Gualandri <dreamos82@yahoo.it>
Date:   Wed Apr 13 15:22:43 2022 +0100

    Fix table layout for make it pandoc friendly

commit 0c3c6f8e2a3e0145d7438a175b1e9dd727b42d30
Merge: bf7e03c 9444a09
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Mon Apr 11 08:41:55 2022 +0100

    Merge pull request #18 from dreamos82/dreamos82-paging-improvements
    
    Paging section improvements

commit 9444a09b8da9e529993c5d392e9fdeaca245e5ed
Author: Dean <dean243@hotmail.com>
Date:   Mon Apr 11 13:02:36 2022 +1000

    requested changes

commit 6d92d3b27deb9e03e72e98f5804f32b89e3c22e5
Author: Dean <dean243@hotmail.com>
Date:   Sun Apr 10 19:08:25 2022 +1000

    editing: paging.md

commit ced64808f32f05e00ee916d3cdce0ae0cd6bd493
Author: Dean <dean243@hotmail.com>
Date:   Sun Apr 10 18:16:13 2022 +1000

    partial spelling + grammar commit

commit 914c87266f4772bb14a10c3cb56144e94e3f9c88
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Sat Apr 9 11:45:18 2022 +0100

    Update README.md

commit 8bd859a31aaa8cc2b05eed31ffe3aa179b5a0a41
Author: Dean <dean243@hotmail.com>
Date:   Sat Apr 9 16:22:04 2022 +1000

    incremental commit

commit 076eaa5fbc512bd5b2a64f3603ffa3c5196969bc
Author: Ivan Gualandri <dreamos82@yahoo.it>
Date:   Fri Apr 8 09:25:12 2022 +0100

    fix type of heap_start and heap_end

commit 104df9b5a7f76be279cff8ad1df68ef9c71bcb94
Author: Ivan Gualandri <dreamos82@yahoo.it>
Date:   Fri Apr 8 09:24:19 2022 +0100

    Changes discussed in review to Memory Management section

commit 0c668ade0f8c854850adb64928b2f8756ec872d4
Author: Ivan Gualandri <dreamos82@yahoo.it>
Date:   Fri Apr 8 00:25:46 2022 +0100

    Update Heap_Allocation

commit 0e10f17f53deec636ef2d7ad9bebd46024aa43a7
Author: Ivan Gualandri <dreamos82@yahoo.it>
Date:   Thu Apr 7 16:21:28 2022 +0100

    Fix first part of code review

commit 924b827cbd3d8b8f3af184a463ca875e70df55da
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Thu Apr 7 01:23:04 2022 +0100

    Update Heap_Allocation.md

commit 081c43fc60c8ff2ca77663266b2e17f7bce34058
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Tue Apr 5 23:39:55 2022 +0100

    Update GDT.md

commit 840f305daa57ae9c70a372636f57bcc8ac6c3fac
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Tue Apr 5 23:36:18 2022 +0100

    Update Heap_Allocation.md

commit f505bf405f4c879ff641a374e13f875a035062e0
Author: Ivan Gualandri <dreamos82@yahoo.it>
Date:   Tue Apr 5 23:25:01 2022 +0100

    update merge section of Heap Allocation

commit faa54a170a5350677311400c49d9d3f538d15ad5
Author: Ivan Gualandri <dreamos82@yahoo.it>
Date:   Mon Apr 4 11:52:28 2022 +0100

    Add info on Merging Nodes

commit bf7e03c3dc444ea92ba97e7888ae7f98063d7d4d
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Sat Apr 2 14:50:46 2022 +0100

    Update Keyboard.md

commit 227b6287fecb2c037aec8a639eb5f3fc6762ac23
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Fri Apr 1 23:50:20 2022 +0100

    Update Keyboard.md

commit 325ec10da5cbc9009e001d550c6391b0eb0f3da1
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Fri Apr 1 23:49:36 2022 +0100

    Update Keyboard.md

commit 0ec1929d264dfd675e182812d1c13babfc2c10a6
Author: Ivan Gualandri <dreamos82@yahoo.it>
Date:   Fri Apr 1 12:32:28 2022 +0100

    add struct definition

commit 4d2a2cc7f21b685536b3f6968549a64a75469114
Author: Ivan Gualandri <dreamos82@yahoo.it>
Date:   Fri Apr 1 11:58:18 2022 +0100

    Add implementation of third_alloc

commit 33e69d1ef7590905c4ceec3bee9d87bd27d3977d
Author: Ivan Gualandri <dreamos82@yahoo.it>
Date:   Mon Mar 28 19:43:16 2022 +0100

    Details of third alloc implementation

commit d230c1227bb5fc87a1467af31df116dd710204f5
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Mon Mar 28 01:01:06 2022 +0100

    Update Heap_Allocation.md

commit 01f3dc5577d267f8928b317efed1c177428f9bc1
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Sat Mar 26 12:26:59 2022 +0000

    Update Heap_Allocation.md

commit 51d5b7d886a9854d133094de074cd76986b12e24
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Sat Mar 26 01:02:00 2022 +0000

    Update Heap_Allocation.md

commit ed39ab4bd2d754865ac297e72e00b1fda5f94d75
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Fri Mar 25 12:57:00 2022 +0000

    Update Heap_Allocation.md

commit 1b071877186d62914925b79da1a38d6de91da44e
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Fri Mar 25 12:42:10 2022 +0000

    Update Heap_Allocation.md

commit db441f56cc1b75e506a471b3f9e48990dd9c6495
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Fri Mar 25 12:26:27 2022 +0000

    Update Heap_Allocation.md

commit fc2c92b07396e51211b8e8745a61d0d57fc8b9ea
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Fri Mar 25 12:07:10 2022 +0000

    Update Paging.md

commit 56e257520b704f8389f02f7330905ca3ef543a4b
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Thu Mar 24 23:23:45 2022 +0000

    Update Heap_Allocation.md

commit e14952ddd12b02a8487bfd047de728fc2aa35a1d
Author: Ivan Gualandri <dreamos82@yahoo.it>
Date:   Tue Mar 22 23:40:03 2022 +0000

    add pros and cons of bump allocator

commit 79cee19fd82d10d190346cdd21fef2dc70584253
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Tue Mar 22 01:11:40 2022 +0000

    Update Heap_Allocation.md

commit a56a590a90894a587f0b594fbd817ddf3ef514e3
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Mon Mar 21 11:52:26 2022 +0000

    Update Heap_Allocation.md

commit d9770e83f8a6b1175ec79d99795750359843881d
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Mon Mar 21 00:31:20 2022 +0000

    Update DrawingTextOnFB.md

commit 2e20e6ce407be22602b2671d4c3acd4aff05c995
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Sun Mar 20 16:33:52 2022 +0000

    Update DrawingTextOnFB.md

commit d8403f2d2b86da53bbedc650e51c1645335bdd4a
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Sat Mar 19 11:13:08 2022 +0000

    Update Heap_Allocation.md

commit ae0b9804beb1e435abe926e889746e4b17b540e2
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Sat Mar 19 01:13:55 2022 +0000

    Update Heap_Allocation.md

commit a448412278431081e872d12bbf49b355c8a4ab82
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Sat Mar 19 01:05:18 2022 +0000

    Update Heap_Allocation.md

commit 4ef043ea1448d0339649a1b02fbd86761d4118b5
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Sat Mar 19 00:51:59 2022 +0000

    Update Virtual_Memory_Manager.md

commit 7daadc9601ecb827497d281b81baf629ff90bf14
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Sat Mar 19 00:51:34 2022 +0000

    Update README.md

commit 39ccf092e55b8f57b979e5b6a5fa5ccfab9734eb
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Sat Mar 19 00:49:45 2022 +0000

    Update Heap_Allocation.md

commit 6c0146d3b10f7be797add5a9938b45c8016fea8d
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Sat Mar 19 00:49:31 2022 +0000

    Create Virtual_Memory_Manager.md

commit 837b903fd8f7f0746501416f74d7ec81bec54d21
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Sat Mar 19 00:43:17 2022 +0000

    Update Heap_Allocation.md
    
    Remove part that was moved in this section README

commit a0a89a872fd4e0f77b3fab92b3232a3154bf488b
Author: Ivan Gualandri <dreamos82@yahoo.it>
Date:   Thu Mar 17 00:02:14 2022 +0000

    Minor syntax fixes

commit aee133269b7be5653695c95806f15007f1a50d42
Merge: ee1c760 f145b53
Author: Ivan Gualandri <dreamos82@yahoo.it>
Date:   Wed Mar 16 19:50:53 2022 +0000

    Merge branch 'master' into dreamos82-paging-improvements

commit f145b53f74c30b894bdf5c6c3ac3a68a42c8230f
Merge: 50c2bf9 7db5448
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Wed Mar 16 10:40:56 2022 +0000

    Merge pull request #21 from dreamos82/dreamos82-patch-1
    
    Update sync-gh-pages.yaml

commit 7db54487096801a79ebfc53d3c6fa1e435cc53c1
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Wed Mar 16 10:37:51 2022 +0000

    Update sync-gh-pages.yaml

commit 50c2bf9c13d54a391cd77a35bfebbe03473b6d3c
Merge: 1a0d5f5 eec7b18
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Tue Mar 15 16:13:32 2022 +0000

    Merge pull request #20 from qvjp/master
    
    Fix link

commit 1a0d5f5026ed98c40e389f45b095c06af3ce7515
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Tue Mar 15 16:10:29 2022 +0000

    Update sync-gh-pages.yaml

commit eec7b1808b2e4ac6cc4c7206cc2589ea94910904
Author: Qu Junping <qvjunping@gmail.com>
Date:   Tue Mar 15 22:27:47 2022 +0800

    Fix link

commit e84b9cbd8fe3ed0725c4c08aa84d7a7beb98f29b
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Tue Mar 15 13:44:57 2022 +0000

    Fix table syntax

commit ee1c760364ce4341ec42a4bf59a90e22eeb95c9e
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Tue Mar 15 12:33:46 2022 +0000

    Update Paging.md

commit 84b467802ca2cc0c62e2e98585e5390daf5d6d61
Author: Dean <dean243@hotmail.com>
Date:   Tue Mar 15 22:41:08 2022 +1100

    fix for issue with sync branches script

commit 90242e78c15df6cfba24d11a8dff5f5f46162b3e
Merge: d4c42b0 829e9e4
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Tue Mar 15 11:27:39 2022 +0000

    Merge pull request #17 from dreamos82/feature-sync-pages
    
    gh-pages branch is updates anytime master branch is.

commit 42974028defd76231503c9a829ac0012f24537f0
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Tue Mar 15 10:43:09 2022 +0000

    Update Paging.md

commit 8916b4778461c4da0e9770ffa56d5117c662f5f6
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Tue Mar 15 01:02:53 2022 +0000

    Update Paging.md

commit 828edfa35ca379526b6450b79330c956087d69b1
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Mon Mar 14 11:10:50 2022 +0000

    Update Paging.md

commit 829e9e4f722f01f238e19d86378acc5041f1b691
Author: Dean <dean243@hotmail.com>
Date:   Mon Mar 14 01:08:59 2022 +1100

    fixed origin ref

commit a4df4917f1c64f56d4a4f1752d1856934b1f9fb6
Author: Dean <dean243@hotmail.com>
Date:   Mon Mar 14 01:04:59 2022 +1100

    v2 of fetch process

commit 3feab67e3dd61b53d1bf3e98885355a468700240
Author: Dean <dean243@hotmail.com>
Date:   Mon Mar 14 00:38:46 2022 +1100

    Added gh action to sync gh-pages branch on master update

commit 8fe1e2ac17aff2eaa87281fdfa30876d1c90b6d4
Author: Dean <dean243@hotmail.com>
Date:   Mon Mar 14 00:25:48 2022 +1100

    EOD commit

commit d4c42b0f636c25d2503e420aa4cb02924bc04451
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Sun Mar 13 11:49:17 2022 +0000

    Update RSDP_and_RSDT.md

commit 1342c2b5e25b000e122d0d13da07fff3dd373776
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Sun Mar 13 11:42:08 2022 +0000

    Update RSDP_and_RSDT.md
    
    fix typo

commit e36a80a8479e88ef9a726af2fc8969dbb4fee705
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Sun Mar 13 11:40:57 2022 +0000

    Update RSDP_and_RSDT.md
    
    Add checksum validation info.

commit 7722cabba3935cfb99f236a780dab4015c715854
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Sat Mar 12 00:17:53 2022 +0000

    Update Paging.md

commit 19968a837e20f5a96fe73d29320465acb97cc1d8
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Tue Mar 8 14:46:37 2022 +0000

    Update Paging.md

commit 28b10e91609bba91607b2135a7e4e89c0fe79d3e
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Tue Mar 8 13:46:47 2022 +0000

    Update Paging.md

commit eef50f2ae5e04ac80e1616438bfd1f9610034ce5
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Mon Mar 7 16:37:20 2022 +0000

    Draft of Paging introductory paragraph.

commit e3194d5f8043ae23a5bbe88d308a95e2b748ce34
Author: Dean <dean243@hotmail.com>
Date:   Mon Mar 7 16:37:36 2022 +1100

    incremental commit

commit 4e69c6bf8e0d634721f9d56d121b8f76f0c957f4
Author: Dean <dean243@hotmail.com>
Date:   Fri Mar 4 18:34:14 2022 +1100

    incremental commit

commit 0cef74131c26ad1fb03026688516570e2e6d25ca
Author: Dean <dean243@hotmail.com>
Date:   Fri Mar 4 16:20:39 2022 +1100

    Added missing info on segment selectors.

commit b5d66848dab47c28de5d8679071536ac2603d757
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Thu Mar 3 11:45:03 2022 +0000

    Update APIC.md

commit 1c188e32876c33b7f75c536f66728c0b43fec44e
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Thu Mar 3 09:53:52 2022 +0000

    Update RSDP_and_RSDT.md
    
    fix minor typo

commit 40ac7e446bba6a5d44708ac2b2ecc9aa3b4a7d45
Author: Ivan Gualandri <dreamos82@yahoo.it>
Date:   Thu Mar 3 01:25:34 2022 +0000

    minor fixes on RSDP_and_RSDT.md

commit 8346276ceb9450a3e885c6bc44e4ee8db652d0c7
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Wed Mar 2 16:30:35 2022 +0000

    Delete _config.yml

commit b1cadd2afe4bbf0b62f09ccb7cf7a0bdeae11038
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Wed Mar 2 16:29:06 2022 +0000

    Set theme jekyll-theme-midnight

commit 941c467da2c3b030a53f4f3dc82348cfc9a2204e
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Wed Mar 2 16:25:25 2022 +0000

    Update README.md

commit 4882b79bdf0558c32bb00c96f45e30a3de246bf0
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Wed Mar 2 12:25:05 2022 +0000

    Added memory allocation notes
    
    * Start draft version of memory allocation chapter
    
    * continue link paragraph
    
    * allocation example
    
    * Update Memory_Allocation.md
    
    * Update Memory_Allocation.md
    
    * Update Memory_Allocation.md
    
    * Add Memory Management section
    
    * Update README.md
    
    * Added vmm notes
    
    * Finish introduction for MMU section
    
    * Update README.md
    
    Add example image
    
    * Re organize files and update readme
    
    * Update README.md
    
    * Grammar and minor edits
    
    Co-authored-by: Dean <dean243@hotmail.com>

commit 98c15c73b06e2773a428594d31cc088d6894c52a
Author: Dean <dean243@hotmail.com>
Date:   Wed Mar 2 17:02:47 2022 +1100

    working commit: initial sections written, scaffolding.

commit 13ff6325c024fcb4a097c7646280323bed5b62fd
Author: Dean <dean243@hotmail.com>
Date:   Tue Mar 1 15:10:48 2022 +1100

    Added vmm notes

commit 6c84faf4138b18c803cfdf2538cce8757bc6e7d2
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Mon Feb 28 00:25:27 2022 +0000

    Update Multiboot.md
    
    few fixe to typos on multiboot.md

commit 9c2d9e1ffc70b6d87d2043bf7934f3396f533d77
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Sat Feb 26 00:41:32 2022 +0000

    Update Nasm.md

commit eb01c9e41562c4fff705f9b0762df8a5db208c04
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Thu Feb 24 16:50:07 2022 +0000

    Update README.md

commit 31937e8deecb16570c08717154d03347b2d3d163
Author: Ivan Gualandri <dreamos82@yahoo.it>
Date:   Thu Feb 24 16:40:55 2022 +0000

    Add Memory Management section

commit e5957cf83e21993b4ca44d2e9cc6a08565415fbb
Merge: 78748f6 4b94537
Author: Ivan Gualandri <dreamos82@yahoo.it>
Date:   Tue Feb 22 19:39:10 2022 +0000

    Merge branch 'Memory_allocation' of github.com:dreamos82/Osdev-Notes into Memory_allocation

commit 4b94537f4f77dfd3925a11a697cae72199c0a612
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Tue Feb 22 12:08:04 2022 +0000

    Update Memory_Allocation.md

commit a92d34eb8fc1da2d5fe5e811eaddee55e33f9ed4
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Mon Feb 21 14:33:37 2022 +0000

    Update Memory_Allocation.md

commit 7f1a482d319a29d7b2f54f5f454c2d174bfe80ba
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Mon Feb 21 12:32:42 2022 +0000

    Update Memory_Allocation.md

commit 78748f634984455b3019ef4f1d2eaf9f0c071784
Merge: 52e57c1 5d1c49c
Author: Ivan Gualandri <dreamos82@yahoo.it>
Date:   Fri Feb 18 13:54:31 2022 +0000

    Merge branch 'master' of github.com:dreamos82/Osdev-Notes into Memory_allocation

commit 5d1c49ca25d846f86503af6ca4da48977a487022
Author: Ivan Gualandri <dreamos82@yahoo.it>
Date:   Fri Feb 18 13:50:16 2022 +0000

    few minor improvement on interrupt section

commit 52e57c1bb52a4c697da76f6fb563ddf5814b589a
Author: Ivan Gualandri <dreamos82@yahoo.it>
Date:   Thu Feb 17 16:16:24 2022 +0000

    allocation example

commit 7a46001874a550bc1b8b7d751cfaa1d0edabeead
Author: Ivan Gualandri <dreamos82@yahoo.it>
Date:   Tue Feb 15 19:11:08 2022 +0000

    continue link paragraph

commit 23521d318d7c1e1b78ca685aa8c0f4959ce93c9f
Merge: 7b7faf2 bf2310a
Author: Ivan Gualandri <dreamos82@yahoo.it>
Date:   Tue Feb 15 15:43:53 2022 +0000

    Merge branch 'master' of github.com:dreamos82/Osdev-Notes into Memory_allocation

commit bf2310a17c5108c1f3cdba98c90389da4e0047bc
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Tue Feb 15 12:02:59 2022 +0000

    Update README.md

commit ff2867a54995aeecfe96185b2cf77477c7c2f609
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Tue Feb 15 00:25:48 2022 +0000

    Update README.md

commit 7b7faf26aeec28fa150c86aca3f2a7e97c287148
Author: Ivan Gualandri <dreamos82@yahoo.it>
Date:   Sun Feb 13 13:19:38 2022 +0000

    Start draft version of memory allocation chapter

commit 97ac489bbfa33a666b1a7afbe8437aedea0325cd
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Fri Feb 11 12:08:21 2022 +0000

    Update APIC.md

commit 5f740102e8e259e39370debed51af4be96b2c0fe
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Thu Feb 10 19:25:11 2022 +0000

    Update APIC.md

commit deb7eac94772998702070b766e937c68f49d546f
Merge: 7364f8e 5d8e725
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Tue Feb 8 12:58:15 2022 +0100

    Merge pull request #9 from DeanoBurrito/master
    
    Added info on gdt and volatile.

commit 5d8e7253131a486d29721394541ac785f81be6b6
Author: Dean <dean243@hotmail.com>
Date:   Tue Feb 8 22:30:58 2022 +1100

    Spelling corrections, added section explaining selector type field.

commit 505bcfb85c4e5a4db0391b08ee174ba13da9a232
Author: Dean <dean243@hotmail.com>
Date:   Tue Feb 8 18:14:28 2022 +1100

    Added info on gdt and volatile.

commit 7364f8e6946d81905e5e412eee250f79d1e2e725
Merge: cbeebf4 bcd5904
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Sat Feb 5 03:31:43 2022 +0100

    Merge pull request #8 from dreamos82/Timer.md
    
    Timer.md

commit bcd59043a123ea7579811bf49e33f7cca787802e
Author: Ivan Gualandri <dreamos82@yahoo.it>
Date:   Fri Feb 4 00:45:33 2022 +0000

    Update Timer

commit b5b45be0c17d3024be8510c51af94047276bc3b9
Author: Ivan Gualandri <dreamos82@yahoo.it>
Date:   Thu Feb 3 19:31:45 2022 +0000

    udpate timer.md

commit 3a6f4de86cc4e32c5cce79b73e47c91b8836bc92
Author: Ivan Gualandri <dreamos82@yahoo.it>
Date:   Tue Feb 1 19:23:55 2022 +0000

    Fix links

commit 8bdef2c4cb1cef7718a6bbdef82545210847608e
Author: Ivan Gualandri <dreamos82@yahoo.it>
Date:   Tue Feb 1 19:19:45 2022 +0000

    Update links

commit 30ac9c7c56dc179e394bbb09f74a04b287248135
Author: Ivan Gualandri <dreamos82@yahoo.it>
Date:   Mon Jan 31 19:27:18 2022 +0000

    Add tutorial about timer draft

commit cbeebf471283217211f097850005323e93e38790
Merge: b7025ed 3eba8d7
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Mon Jan 31 11:07:25 2022 +0100

    Merge pull request #7 from dreamos82/Keyboard_Notes
    
    Keyboard notes

commit 3eba8d7443a74a8ce776106cfcc24ef974c9eae1
Author: Ivan Gualandri <dreamos82@yahoo.it>
Date:   Sun Jan 30 15:38:32 2022 +0000

    Add more information regarding the keyboard

commit 54581ca8e9327d751a042d590e495fa829d5c507
Author: Ivan Gualandri <dreamos82@yahoo.it>
Date:   Sun Jan 30 14:31:39 2022 +0000

    Add EOI information

commit f32ca2d9d25a9c9a895cb7479bd7e476bffde17f
Author: Ivan Gualandri <dreamos82@yahoo.it>
Date:   Sun Jan 30 01:15:31 2022 +0000

    add draft on keyboard notes

commit b7025ed0dbc032c65d05e52c4689ee01df605da2
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Wed Jan 26 13:01:48 2022 +0100

    Add info about source overrides (#5)
    
    * Add info about source overrides
    
    * Start to add info about IOREDTBL
    
    * Add info about LVT entry and IOREDTBL
    
    * Finish IOREDTbl entry def
    
    * Fix comments

commit e70f73e3b4c6b8a95dd33d5b0c66dd8e8e529142
Merge: ecd9869 1b519c6
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Wed Jan 26 12:05:37 2022 +0100

    Merge pull request #6 from DeanoBurrito/master
    
    Checked and added info about IO APIC.

commit 1b519c67d8a567effc02838fe02ecc024741017c
Author: Dean <dean243@hotmail.com>
Date:   Mon Jan 24 05:00:07 2022 +1100

    Checked and added info about IO APIC.
    Added TipsAndTricks file.
    Added info about hardware breakpoints.
    Added info about "memory" clobber.
    Expanded section on RSDT, added mirror info for XSDT.

commit ecd98693c8e5af8f341e5d6520e9d45cb074c575
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Sun Jan 16 18:36:11 2022 +0000

    Update APIC.md

commit f5a4b6dfe3c2872708454d7a0f2415e9f44fd838
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Sat Jan 15 10:37:36 2022 +0000

    Update APIC.md

commit b236f743d13d8de97b385ffa4605d41ea92114d7
Author: Ivan Gualandri <dreamos82@yahoo.it>
Date:   Fri Jan 14 15:55:06 2022 +0000

    Add register info for ioapic

commit ad186e3bf3313ba12fe6ed19934a9e307c28ab34
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Tue Jan 11 00:23:38 2022 +0000

    Update APIC.md

commit 57072cf9537532e28f8c66eacd5b1b793206a2f7
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Mon Jan 10 17:33:00 2022 +0000

    Update README.md
    
    Add Acknowledgements

commit fda8f53028f5a3bf08c7bb741d99771e57b00301
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Sun Jan 9 13:39:09 2022 +0100

    Add IOAPIC register read/write (#4)
    
    * Add IOAPIC register read/write

commit f8f5c2002e232658872d6a83ddebf1b8109f16b2
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Sun Jan 2 11:21:59 2022 +0000

    Create FUNDING.yml

commit 14df73bd33cb24e2553a230991cec41892a682ee
Merge: aea9da6 291367a
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Sun Jan 2 11:18:04 2022 +0000

    Merge pull request #3 from DeanoBurrito/master
    
    Added info about c/assembly interop.

commit 291367ae52be6f4e6853279a30cf80b566a1f283
Author: Dean T <dean243@hotmail.com>
Date:   Sun Jan 2 19:24:07 2022 +1100

    Added info about c/assembly interop.

commit aea9da686d95b3bd50f1b9f5f82884296ef5d3b6
Author: Ivan Gualandri <dreamos82@yahoo.it>
Date:   Mon Dec 27 10:41:44 2021 +0000

    Add Some RSDP and RSDT info

commit 1aad75a8baf835607268f0157292f6552f55549f
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Sat Dec 25 00:47:23 2021 +0000

    Update RSDP_and_RSDT.md

commit cbe265128fc0d577fef79755ba3cdc0d5dace272
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Thu Dec 23 16:54:13 2021 +0000

    Update README.md

commit a55c382877de91b0257681cd2da7abf99dc69478
Merge: a5cbf0a f5544aa
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Thu Dec 23 16:52:58 2021 +0000

    Merge pull request #2 from DeanoBurrito/master
    
    Fixed spelling mistakes, added troubling info for sse.

commit f5544aa57d466301eb3a9f38e2f2de484d85a142
Author: Dean T <dean243@hotmail.com>
Date:   Thu Dec 23 23:27:24 2021 +1100

    Fixed spelling mistakes, added troubling info for sse.

commit a5cbf0a79001658b3049ebaac66bab927fab1007
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Wed Dec 22 22:29:13 2021 +0000

    Update Debug.md

commit 0c3a2fcfcb8a9a8701a57bffe2ef4637b4d712cb
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Wed Dec 22 20:42:37 2021 +0000

    Update Debug.md

commit e7fb3f4a53cb9472a4589193a83b6b5ddecf48d9
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Sun Dec 19 14:15:53 2021 +0000

    Update Debug.md

commit d96e334f58f125976a632e4c567543e209935da9
Merge: c823a66 2bdc2a8
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Sun Dec 19 09:43:53 2021 +0000

    Merge pull request #1 from DeanoBurrito/master
    
    Expanded section on GDB and added debugcon section.

commit 2bdc2a8081cec776f2dd5c202e600ed8519a8db9
Author: Dean T <dean243@hotmail.com>
Date:   Sun Dec 19 20:39:33 2021 +1100

    Spelling mistake fix, and added info about halt and interrupts

commit 4ae9e68e0fdc6829a7db7604c814cd4c35b1f2be
Author: Dean T <dean243@hotmail.com>
Date:   Sat Dec 18 20:16:19 2021 +1100

    Expanded section on GDB and added debugcon section.

commit c823a665641f85d47012804758fe242f20921019
Author: Ivan Gualandri <dreamos82@yahoo.it>
Date:   Thu Dec 16 17:13:53 2021 +0000

    Add apic file (to be completed) and some info on qemu monitor

commit b7a3c392d6061349dec59a81d463453e393f7755
Author: Ivan Gualandri <dreamos82@yahoo.it>
Date:   Fri Nov 26 00:51:20 2021 +0000

    Add pointer arithmetic

commit 39d962084180914ff6aad24f8173e9255d6a6ede
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Wed Nov 24 12:03:56 2021 +0000

    Fixing typo

commit 7ec7fd0fc1a5e5421c1c18c9ce9d75287a472989
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Thu Nov 18 12:01:16 2021 +0000

    Add linker example line

commit fe8a6910ec8f429a41cf7c8620a4e8030f858664
Author: Ivan Gualandri <dreamos82@yahoo.it>
Date:   Tue Nov 16 14:50:10 2021 +0000

    Add virtualbox section to Debug. Not finished yet

commit 5219309646240cbff3804b48568df4f001e71fb9
Author: Ivan Gualandri <dreamos82@yahoo.it>
Date:   Mon Nov 15 15:21:06 2021 +0000

    update Readme

commit af2809e5611a33896519e08e388d0d1457c8676b
Author: Ivan Gualandri <dreamos82@yahoo.it>
Date:   Mon Nov 15 15:19:47 2021 +0000

    Add C_Language_Info file

commit e7cca6d66e148ecc92cb86337d81274a7d1ae8c2
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Mon Nov 15 15:14:42 2021 +0000

    Update Framebuffer.md

commit f58c96968e4f82d867780cbbcd9a395945a81d9a
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Mon Nov 15 15:03:22 2021 +0000

    Update Debug.md

commit 4d067578f1dd9a9f83af3bdfd05f07275ae5ae62
Author: Ivan Gualandri <dreamos82@yahoo.it>
Date:   Mon Nov 8 14:17:01 2021 +0000

    Create a RSDP file

commit 727d5e6df82925cee4630e2d376ec58a9e4b578c
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Thu Sep 30 00:43:59 2021 +0100

    Update Paging.md

commit f376f7fd576399b87e8927ff839b8b0c10cd9e2e
Author: Ivan Gualandri <dreamos82@yahoo.it>
Date:   Mon Sep 27 00:39:03 2021 +0100

    improved example paging

commit 2138c880efa0f76cc96177ea86a748c932d24aca
Merge: c8f897b c93e2c9
Author: Ivan Gualandri <dreamos82@yahoo.it>
Date:   Thu Sep 16 01:34:50 2021 +0100

    Merge branch 'master' of github.com:dreamos82/Osdev-Notes

commit c8f897b3e261d3d8fb4b9c503e0ed60594b86dc5
Author: Ivan Gualandri <dreamos82@yahoo.it>
Date:   Thu Sep 16 01:34:31 2021 +0100

    add some details on recursion in paging

commit c93e2c99e2927c67a62bdc941ffad419586ba35c
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Sun Sep 5 01:44:25 2021 +0100

    Update IntterruptHandling.md

commit 8763914c688beb563d85b4d1e7ccd1988d0e4a00
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Sun Sep 5 01:41:11 2021 +0100

    Update Paging.md
    
    Fix tables and typo

commit adff34d6307780cc95fddc06ad80a352f9fa4c3d
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Sat Aug 21 16:19:56 2021 +0100

    Update README.md

commit d168ce2f9a42c1eeb48cd40ee765d318ea495f43
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Tue Aug 17 11:52:44 2021 +0100

    Update README.md

commit 62900ca492cc29395447343c0818623e1f901e44
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Mon Aug 9 10:53:36 2021 +0100

    Update PhysicalMemory.md

commit a744bc88c88f62005b0654d623ebcc44c94d13fe
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Wed Aug 4 09:34:03 2021 +0100

    Fix table

commit f196e21e218b0373571a654a1083b35c0e6d65df
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Wed Aug 4 09:26:16 2021 +0100

    Update Environment_Setup.md

commit c657ec53e7eb57a73938f5e5e279d947f769ced1
Author: Ivan G <59960116+dreamos82@users.noreply.github.com>
Date:   Sun Aug 1 15:03:24 2021 +0100

    Update PhysicalMemory.md

commit 080b7c5dbd6235eb8f1af0836ef167b7acf11990
Author: Ivan Gualandri <dreamos82@yahoo.it>
Date:   Sat Jul 24 08:19:07 2021 +0100

    Initial commit
