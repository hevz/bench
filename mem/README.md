# Memory copy benchmarks

## Hardware

Loongson-3c5000 16-core machine (2.2GHz)

## Results

```
rte_memcpy size 16384 dest_offset 0 src_offset 0 speed  16574.703 MB/s
modified kernel memcpy size 16384 dest_offset 0 src_offset 0 speed  16623.918 MB/s
kernel memcpy size 16384 dest_offset 0 src_offset 0 speed  16631.707 MB/s
hmemcpy size 16384 dest_offset 0 src_offset 0 speed  16655.826 MB/s
memcpy size 16384 dest_offset 0 src_offset 0 speed  16639.680 MB/s

rte_memcpy size 16384 dest_offset 0 src_offset 8 speed  16664.355 MB/s
modified kernel memcpy size 16384 dest_offset 0 src_offset 8 speed  16512.326 MB/s
kernel memcpy size 16384 dest_offset 0 src_offset 8 speed  15857.224 MB/s
hmemcpy size 16384 dest_offset 0 src_offset 8 speed  16656.536 MB/s
memcpy size 16384 dest_offset 0 src_offset 8 speed  16640.211 MB/s

rte_memcpy size 16384 dest_offset 0 src_offset 6 speed  14893.495 MB/s
modified kernel memcpy size 16384 dest_offset 0 src_offset 6 speed  14748.232 MB/s
kernel memcpy size 16384 dest_offset 0 src_offset 6 speed  14186.587 MB/s
hmemcpy size 16384 dest_offset 0 src_offset 6 speed  14867.978 MB/s
memcpy size 16384 dest_offset 0 src_offset 6 speed  14862.178 MB/s

rte_memcpy size 92 dest_offset 0 src_offset 0 speed  10687.839 MB/s
modified kernel memcpy size 92 dest_offset 0 src_offset 0 speed  6412.605 MB/s
kernel memcpy size 92 dest_offset 0 src_offset 0 speed  3735.924 MB/s
hmemcpy size 92 dest_offset 0 src_offset 0 speed  11315.875 MB/s
memcpy size 92 dest_offset 0 src_offset 0 speed  9161.105 MB/s

rte_memcpy size 92 dest_offset 1 src_offset 0 speed  9160.505 MB/s
modified kernel memcpy size 92 dest_offset 1 src_offset 0 speed  8016.491 MB/s
kernel memcpy size 92 dest_offset 1 src_offset 0 speed  2723.312 MB/s
hmemcpy size 92 dest_offset 1 src_offset 0 speed  11316.789 MB/s
memcpy size 92 dest_offset 1 src_offset 0 speed  8745.081 MB/s

rte_memcpy size 92 dest_offset 6 src_offset 0 speed  9160.505 MB/s
modified kernel memcpy size 92 dest_offset 6 src_offset 0 speed  8016.491 MB/s
kernel memcpy size 92 dest_offset 6 src_offset 0 speed  4580.702 MB/s
hmemcpy size 92 dest_offset 6 src_offset 0 speed  11316.789 MB/s
memcpy size 92 dest_offset 6 src_offset 0 speed  9258.647 MB/s

rte_memcpy size 92 dest_offset 6 src_offset 6 speed  11250.402 MB/s
modified kernel memcpy size 92 dest_offset 6 src_offset 6 speed  8364.701 MB/s
kernel memcpy size 92 dest_offset 6 src_offset 6 speed  4815.630 MB/s
hmemcpy size 92 dest_offset 6 src_offset 6 speed  11312.217 MB/s
memcpy size 92 dest_offset 6 src_offset 6 speed  9161.105 MB/s

rte_memcpy size 160 dest_offset 0 src_offset 0 speed  12895.724 MB/s
modified kernel memcpy size 160 dest_offset 0 src_offset 0 speed  9862.172 MB/s
kernel memcpy size 160 dest_offset 0 src_offset 0 speed  5297.898 MB/s
hmemcpy size 160 dest_offset 0 src_offset 0 speed  15240.475 MB/s
memcpy size 160 dest_offset 0 src_offset 0 speed  14578.479 MB/s

rte_memcpy size 160 dest_offset 1 src_offset 0 speed  12418.567 MB/s
modified kernel memcpy size 160 dest_offset 1 src_offset 0 speed  11974.872 MB/s
kernel memcpy size 160 dest_offset 1 src_offset 0 speed  3798.257 MB/s
hmemcpy size 160 dest_offset 1 src_offset 0 speed  15240.475 MB/s
memcpy size 160 dest_offset 1 src_offset 0 speed  11176.767 MB/s

rte_memcpy size 160 dest_offset 6 src_offset 0 speed  12419.831 MB/s
modified kernel memcpy size 160 dest_offset 6 src_offset 0 speed  11973.697 MB/s
kernel memcpy size 160 dest_offset 6 src_offset 0 speed  4311.183 MB/s
hmemcpy size 160 dest_offset 6 src_offset 0 speed  15240.475 MB/s
memcpy size 160 dest_offset 6 src_offset 0 speed  11975.460 MB/s

rte_memcpy size 160 dest_offset 6 src_offset 6 speed  11176.767 MB/s
modified kernel memcpy size 160 dest_offset 6 src_offset 6 speed  13411.015 MB/s
kernel memcpy size 160 dest_offset 6 src_offset 6 speed  5153.333 MB/s
hmemcpy size 160 dest_offset 6 src_offset 6 speed  15240.475 MB/s
memcpy size 160 dest_offset 6 src_offset 6 speed  11975.460 MB/s

rte_memcpy size 1488 dest_offset 0 src_offset 0 speed  16206.183 MB/s
modified kernel memcpy size 1488 dest_offset 0 src_offset 0 speed  16772.573 MB/s
kernel memcpy size 1488 dest_offset 0 src_offset 0 speed  15181.103 MB/s
hmemcpy size 1488 dest_offset 0 src_offset 0 speed  16594.174 MB/s
memcpy size 1488 dest_offset 0 src_offset 0 speed  16593.931 MB/s

rte_memcpy size 1488 dest_offset 1 src_offset 0 speed  14855.632 MB/s
modified kernel memcpy size 1488 dest_offset 1 src_offset 0 speed  14926.943 MB/s
kernel memcpy size 1488 dest_offset 1 src_offset 0 speed  5631.217 MB/s
hmemcpy size 1488 dest_offset 1 src_offset 0 speed  14927.042 MB/s
memcpy size 1488 dest_offset 1 src_offset 0 speed  14646.295 MB/s

rte_memcpy size 1488 dest_offset 6 src_offset 0 speed  14855.826 MB/s
modified kernel memcpy size 1488 dest_offset 6 src_offset 0 speed  14927.042 MB/s
kernel memcpy size 1488 dest_offset 6 src_offset 0 speed  5552.661 MB/s
hmemcpy size 1488 dest_offset 6 src_offset 0 speed  14926.943 MB/s
memcpy size 1488 dest_offset 6 src_offset 0 speed  14820.522 MB/s

rte_memcpy size 1488 dest_offset 6 src_offset 6 speed  16248.291 MB/s
modified kernel memcpy size 1488 dest_offset 6 src_offset 6 speed  16506.450 MB/s
kernel memcpy size 1488 dest_offset 6 src_offset 6 speed  5643.523 MB/s
hmemcpy size 1488 dest_offset 6 src_offset 6 speed  16594.052 MB/s
memcpy size 1488 dest_offset 6 src_offset 6 speed  16506.570 MB/s

rte_memcpy size 4096 dest_offset 0 src_offset 0 speed  16608.187 MB/s
modified kernel memcpy size 4096 dest_offset 0 src_offset 0 speed  16770.813 MB/s
kernel memcpy size 4096 dest_offset 0 src_offset 0 speed  16771.353 MB/s
hmemcpy size 4096 dest_offset 0 src_offset 0 speed  16770.813 MB/s
memcpy size 4096 dest_offset 0 src_offset 0 speed  16262.702 MB/s

rte_memcpy size 4096 dest_offset 1 src_offset 0 speed  14881.860 MB/s
modified kernel memcpy size 4096 dest_offset 1 src_offset 0 speed  14715.026 MB/s
kernel memcpy size 4096 dest_offset 1 src_offset 0 speed  5406.434 MB/s
hmemcpy size 4096 dest_offset 1 src_offset 0 speed  14907.283 MB/s
memcpy size 4096 dest_offset 1 src_offset 0 speed  14769.848 MB/s

rte_memcpy size 4096 dest_offset 6 src_offset 0 speed  14881.434 MB/s
modified kernel memcpy size 4096 dest_offset 6 src_offset 0 speed  14716.690 MB/s
kernel memcpy size 4096 dest_offset 6 src_offset 0 speed  5547.959 MB/s
hmemcpy size 4096 dest_offset 6 src_offset 0 speed  14907.567 MB/s
memcpy size 4096 dest_offset 6 src_offset 0 speed  14868.968 MB/s

rte_memcpy size 4096 dest_offset 6 src_offset 6 speed  16609.247 MB/s
modified kernel memcpy size 4096 dest_offset 6 src_offset 6 speed  16355.678 MB/s
kernel memcpy size 4096 dest_offset 6 src_offset 6 speed  5355.459 MB/s
hmemcpy size 4096 dest_offset 6 src_offset 6 speed  16770.813 MB/s
memcpy size 4096 dest_offset 6 src_offset 6 speed  16706.061 MB/s
```
