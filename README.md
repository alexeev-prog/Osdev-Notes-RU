# Osdev Notes на русском
Перевод книги о том как создавать свои ОС с нуля.

## Главы

* [Часть 0: Введение](00_Introduction/01_README.md)
    * [Предполагаемые знания](00_Introduction/02_AssumedKnowledge.md)
    * [Об авторах](00_Introduction/03_AboutTheAuthors.md)

### Не переведено

* [Part 1: Building & Boot Protocols](01_Build_Process/README.md)
    * [Building a Kernel](01_Build_Process/01_Overview.md)
    * [Bootloaders and Boot Protocols](01_Build_Process/02_Boot_Protocols.md)
    * [Makefiles](01_Build_Process/03_Gnu_Makefiles.md)
    * [Linker Scripts](01_Build_Process/04_Linker_Scripts.md)
    * [Generating a Bootable Iso](01_Build_Process/05_Generating_Iso.md)
* [Part 2: Architecture and Basic Drivers](02_Architecture/README.md)
    * [Overview](02_Architecture/01_Overview.md)
    * [Hello World](02_Architecture/02_Hello_World.md)
    * [A Higher Half Kernel](02_Architecture/03_HigherHalf.md)
    * [Global Descriptor Table](02_Architecture/04_GDT.md)
    * [Interrupts](02_Architecture/05_InterruptHandling.md)
    * [ACPI Tables](02_Architecture/06_ACPITables.md)
    * [APIC](02_Architecture/07_APIC.md)
    * [Timers](02_Architecture/08_Timers.md)
    * [PS2 Keyboard Overview](02_Architecture/09_Add_Keyboard_Support.md)
    * [PS2 Keyboard Interrupt Handling](02_Architecture/10_Keyboard_Interrupt_Handling.md)
    * [PS2 Keyboard Driver implementation](02_Architecture/11_Keyboard_Driver_Implemenation.md)
* [Part 3: Video Output](03_Video_Output/README.md)
    * [The Framebuffer](03_Video_Output/01_Framebuffer.md)
    * [Drawing Text on Framebuffer](03_Video_Output/02_DrawingTextOnFB.md)
* [Part 4: Memory Management](04_Memory_Management/README.md)
    * [Overview](04_Memory_Management/01_Overview.md)
    * [Physical Memory](04_Memory_Management/02_Physical_Memory.md)
    * [Paging](04_Memory_Management/03_Paging.md)
    * [Virtual Memory Manager](04_Memory_Management/04_Virtual_Memory_Manager.md)
    * [Heap Allocation](04_Memory_Management/05_Heap_Allocation.md)
* [Part 5: Scheduling](05_Scheduling/README.md)
    * [Overview](05_Scheduling/01_Overview.md)
    * [The Scheduler](05_Scheduling/02_Scheduler.md)
    * [Processes and Threads](05_Scheduling/03_Processes_And_Threads.md)
    * [Locks](05_Scheduling/04_Locks.md)
* [Part 6: Getting to Userspace](06_Userspace/README.md)
    * [Overview](06_Userspace/01_Overview.md)
    * [Switching Modes](06_Userspace/02_Switching_Modes.md)
    * [Updated Interrupt Handling](06_Userspace/03_Handling_Interrupts.md)
    * [System Calls](06_Userspace/04_System_Calls.md)
    * [Example Syscall ABI](06_Userspace/05_Example_ABI.md)
* [Part 7: Inter-Process Communication](07_IPC/README.md)
    * [Overview](07_IPC/01_Overview.md)
    * [Shared Memory](07_IPC/02_Shared_Memory.md)
    * [Message Passing](07_IPC/03_Message_Passing.md)
* [Part 8: File System](08_VirtualFileSystem/README.md)
    * [Overview](08_VirtualFileSystem/01_Overview.md)
    * [The Virtual File System](08_VirtualFileSystem/02_VirtualFileSystem.md)
    * [The Tar File System](08_VirtualFileSystem/03_TarFileSystem.md)
* [Part 9: Loading & Executing ELFs](09_Loading_Elf/README.md)
    * [Theory](09_Loading_Elf/01_Elf_Theory.md)
    * [Loading and Running](09_Loading_Elf/03_Loading_And_Running.md)
* [Part 10: Going Beyond](10_Going_Beyond/README.md)
* [Extras: Appendices](99_Appendices/README.md)
    * [General Troubleshooting](99_Appendices/A_Troubleshooting.md)
    * [Tips and Tricks](99_Appendices/B_Tips_And_Tricks.md)
    * [C Language](99_Appendices/C_Language_Info.md)
    * [Working With NASM](99_Appendices/D_Nasm.md)
    * [All About Cross Compilers](99_Appendices/E_Cross_Compilers.md)
    * [Debugging](99_Appendices/F_Debugging.md)
    * [Memory Protection](99_Appendices/G_Memory_Protection.md)
    * [Useful Resources](99_Appendices/H_Useful_Resources.md)
    * [Acknowledgments](99_Appendices/I_Acknowledgments.md)

## Проекты

* [DreamOs64](https://github.com/dreamos82/Dreamos64): 64 битная ОС написанная [Ivan G](https://github.com/dreamos82).
* [Northport](https://github.com/DeanoBurrito/northport): 64 битная ОС с SMT и поддержкой RISC-V [Dean T](https://github.com/DeanoBurrito/).
* [DreamOs](https://github.com/dreamos82/Dreamos): 32-разрядная ОС, написанная с нуля. Этот проект прекращен, но о нем все равно стоит упомянуть. Написано тоже [Ivan G](https://github.com/dreamos82).

## Авторы

* [Ivan G](https://github.com/dreamos82) (dreamos82) - Автор и создатель.
* [Dean T](https://github.com/DeanoBurrito/) (DeanoBurrito) - Автор.

## Лицензия

Содержимое (код, текст и другие ресурсы) этого хранилища доступно по лицензии Creative Commons Attribution-Некоммерческая публичная лицензия 4.0, полный текст смотрите в файле [ЛИЦЕНЗИЯ](LICENSE.md).

Хотя эта лицензия не является юридической рекомендацией, ее можно кратко охарактеризовать следующим образом:
- Вы можете свободно делиться (копировать и распространять) этим материалом на любом носителе или в любом формате.
- Адаптировать (переделывать, трансформировать и дополнять) материал.

При соблюдении следующих ограничений:
- Вы должны предоставить соответствующую информацию, предоставить ссылку на лицензию и указать, были ли внесены изменения.
- Вы не можете использовать этот материал в коммерческих целях.

Обратите внимание, что мы не предоставляем никаких гарантий любого рода.

<a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc/4.0/88x31.png" /></a>
