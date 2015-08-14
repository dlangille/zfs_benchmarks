# zfs_benchmarks
Various benchmarks on different ZFS configuration and their respective resilver times

The goal is not so much exact timings, but getting an idea of relative speed.  For example, how much faster is config X than config Y for a given workload?  This should help people decide what vdevs to set up. For example, if config X is only slower by a factor of 0.93% but has much more redundancy, you might choose that one instead.

I'm setting up a new server.  I have a bunch of disks available.  This is the ideal time to test various ZFS cofigurations with respect to benchmarks. It is also an opporunity to compare re-silver times.

The first test is ready to start.  It's a cp versus zfs send comparision.  See https://github.com/dlangille/zfs_benchmarks/issues/8 for details.
