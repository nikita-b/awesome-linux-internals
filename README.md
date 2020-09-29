# Awesome Linux Internals



### Books
* [The Linux Programming Interface](https://www.man7.org/tlpi/)
* [Understanding the Linux Kernel](https://www.amazon.com/Understanding-Linux-Kernel-Third-Daniel/dp/0596005652)
* [Linux Kernel Development 3rd Edition](https://www.amazon.com/Linux-Kernel-Development-Robert-Love/dp/0672329468/)
* [Systems Performance: Enterprise and the Cloud](http://www.brendangregg.com/blog/2020-07-15/systems-performance-2nd-edition.html)
* [Linux Insides](https://0xax.gitbooks.io/linux-insides/content/index.html) (Opensource)


## Memory Management
* [Kernel Admin Guide](https://www.kernel.org/doc/html/latest/admin-guide/mm/index.html)
* (Video) [MM101 introduction to memory management](https://www.youtube.com/watch?v=i17b3xJv3Uo)

## Perf
* [Brendan Gregg - Perf](http://brendangregg.com/perf.html)
* (Video) [Kernel Recipes 2017 - Perf in Netflix - Brendan Gregg](https://www.youtube.com/watch?v=UVM3WX8Lq2k)

## BPF
* [BPF and XDP Reference Guide](https://docs.cilium.io/en/latest/bpf/) Cilium docs
* [Classic BPF and BPF - Kernel Docs](https://www.kernel.org/doc/Documentation/networking/filter.txt)
* [Dive into BPF: a list of reading material](https://qmonnet.github.io/whirl-offload/2016/09/01/dive-into-bpf/) (Many useful links)
* [Blog about BPF from Alexei Starovoitov and Andrii Nakryiko](https://facebookmicrosites.github.io/bpf/blog/)
* [Brendan Gregg - BPF](http://brendangregg.com/ebpf.html)
* (Video) [BPF at Facebook](https://www.youtube.com/watch?v=bbHFg9IsTk8) Alexei Starovoitov author of BPF
* (Video) [AWS re:Invent 2019: BPF performance analysis at Netflix](https://www.youtube.com/watch?v=16slh29iN1g)
* [Cloudflare architecture and how BPF eats the world](https://blog.cloudflare.com/cloudflare-architecture-and-how-bpf-eats-the-world/)

## CGroup (Control Group)
* [Linux Insides](https://0xax.gitbooks.io/linux-insides/content/Cgroups/linux-cgroups-1.html)
* [Control groups, part 1: On the history of process grouping](https://lwn.net/Articles/603762/)
* [Control groups, part 2: On the different sorts of hierarchies](https://lwn.net/Articles/604413/)
* [Control groups, part 3: First steps to control](https://lwn.net/Articles/605039/)
* [Control groups, part 4: On accounting](https://lwn.net/Articles/606004/)
* [Control groups, part 5: The cgroup hierarchy](https://lwn.net/Articles/606699/)
* [Control groups, part 6: A look under the hood](https://lwn.net/Articles/606925/)
* [Control groups, part 7: To unity and beyond](https://lwn.net/Articles/608425/)

## Boot
* [Linux Kernel Boot Protocol](https://www.kernel.org/doc/Documentation/x86/boot.txt)
* [Kernel booting process. Part 1](https://0xax.gitbooks.io/linux-insides/content/Booting/linux-bootstrap-1.html)
* [Linux Boot Process - Part 1](https://medium.com/@cloudchef/linux-boot-process-part-1-e8fea015dd66)
* [Linux Boot Process - Part 2](https://medium.com/@cloudchef/linux-boot-process-part-2-bd7514913495)

## io_uring (Yep, we have separate section for it)
* (Video) [Faster IO through io_uring](https://www.youtube.com/watch?v=-5T4Cjw46ys)

## Filesystems
* [EXT4 - Kernel Admin Guide](https://www.kernel.org/doc/html/latest/admin-guide/ext4.html)

## Pipes
* (Slides] [The Linux Kernel Implementation of Pipes and FIFOs](https://www.slideshare.net/divyekapoor/linux-kernel-implementation-of-pipes-and-fifos)
* [How are Unix pipes implemented?](https://toroid.org/unix-pipe-implementation)
* [How Linux pipes work under the hood](https://brandonwamboldt.ca/how-linux-pipes-work-under-the-hood-1518/)

## IO Multiplexing
* [Select VS Poll VS Epoll](https://devarea.com/linux-io-multiplexing-select-vs-poll-vs-epoll/)
* [select / poll / epoll: practical difference for system architects](https://www.ulduzsoft.com/2014/01/select-poll-epoll-practical-difference-for-system-architects/)

## Specific tools
* [Atop](https://lwn.net/Articles/387202/)