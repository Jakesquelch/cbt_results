
Performance Report for 1st-Oct-3way-balanced-baseline
=====================================================

Table of contents
=================

* [Summary of results for 1st-Oct-3way-balanced-baseline](#summary-of-results-for-1st-oct-3way-balanced-baseline)
* [Response Curves](#response-curves)
	* [Sequential Read](#sequential-read)
	* [Sequential Write](#sequential-write)
	* [Random Read](#random-read)
	* [Random Write](#random-write)
	* [Random Read/Write](#random-readwrite)
* [Configuration yaml](#configuration-yaml)

# Summary of results for 1st-Oct-3way-balanced-baseline
  
|Workload Name|Maximum Throughput|Latency (ms)|  
| :--- | ---: | ---: |  
|[4096_read](#4096-read)|138070 IOps|0.7|  
|[8192_read](#8192-read)|125045 IOps|0.8|  
|[16384_read](#16384-read)|111570 IOps|2.6|  
|[32768_read](#32768-read)|91239 IOps|2.8|  
|[65536_read](#65536-read)|4871 MB/s|5.2|  
|[131072_read](#131072-read)|7798 MB/s|8.6|  
|[262144_read](#262144-read)|12045 MB/s|16.7|  
|[393216_read](#393216-read)|10751 MB/s|7.0|  
|[524288_read](#524288-read)|12733 MB/s|15.8|  
|[786432_read](#786432-read)|12692 MB/s|23.8|  
|[1048576_read](#1048576-read)|12089 MB/s|8.3|  
|[2097152_read](#2097152-read)|11191 MB/s|9.0|  
|[4194304_read](#4194304-read)|10354 MB/s|19.4|  
|[4096_write](#4096-write)|492507 IOps|3.1|  
|[8192_write](#8192-write)|328957 IOps|4.7|  
|[16384_write](#16384-write)|181650 IOps|5.6|  
|[32768_write](#32768-write)|101798 IOps|7.5|  
|[65536_write](#65536-write)|3483 MB/s|9.6|  
|[131072_write](#131072-write)|3718 MB/s|13.5|  
|[262144_write](#262144-write)|3924 MB/s|17.0|  
|[393216_write](#393216-write)|3951 MB/s|25.3|  
|[524288_write](#524288-write)|4009 MB/s|4.0|  
|[786432_write](#786432-write)|3992 MB/s|18.5|  
|[1048576_write](#1048576-write)|4015 MB/s|41.2|  
|[2097152_write](#2097152-write)|4146 MB/s|31.1|  
|[4194304_write](#4194304-write)|3816 MB/s|32.8|  
|[4096_randread](#4096-randread)|185438 IOps|4.1|  
|[8192_randread](#8192-randread)|178815 IOps|4.3|  
|[16384_randread](#16384-randread)|164000 IOps|3.6|  
|[32768_randread](#32768-randread)|134280 IOps|2.9|  
|[65536_randread](#65536-randread)|6881 MB/s|3.7|  
|[131072_randread](#131072-randread)|10147 MB/s|3.3|  
|[262144_randread](#262144-randread)|12833 MB/s|5.2|  
|[393216_randread](#393216-randread)|13059 MB/s|7.7|  
|[524288_randread](#524288-randread)|12833 MB/s|3.9|  
|[786432_randread](#786432-randread)|12381 MB/s|4.1|  
|[1048576_randread](#1048576-randread)|12053 MB/s|5.6|  
|[2097152_randread](#2097152-randread)|11212 MB/s|9.0|  
|[4194304_randread](#4194304-randread)|10224 MB/s|19.7|  
|[4096_randwrite](#4096-randwrite)|49783 IOps|5.1|  
|[8192_randwrite](#8192-randwrite)|47446 IOps|5.4|  
|[16384_randwrite](#16384-randwrite)|46475 IOps|8.2|  
|[32768_randwrite](#32768-randwrite)|43324 IOps|8.8|  
|[65536_randwrite](#65536-randwrite)|2370 MB/s|10.6|  
|[262144_randwrite](#262144-randwrite)|4054 MB/s|16.4|  
|[524288_randwrite](#524288-randwrite)|4531 MB/s|7.1|  
|[1048576_randwrite](#1048576-randwrite)|4142 MB/s|5.6|  
|[4096_70_30_randrw](#4096-70-30-randrw)|98855 IOps|2.6|  
|[16384_70_30_randrw](#16384-70-30-randrw)|89858 IOps|2.8|  
|[65536_30_70_randrw](#65536-30-70-randrw)|2960 MB/s|5.6|  
|[65536_70_30_randrw](#65536-70-30-randrw)|4284 MB/s|3.9|
# Response Curves

## Sequential Read

|||
| :---: | :---: |
|<a name="4096-read"></a>![4KK  Sequential Read](plots.251001_133319/4096_read.png)|<a name="8192-read"></a>![8KK  Sequential Read](plots.251001_133319/8192_read.png)|
|<a name="16384-read"></a>![16KK  Sequential Read](plots.251001_133319/16384_read.png)|<a name="32768-read"></a>![32KK  Sequential Read](plots.251001_133319/32768_read.png)|
|<a name="65536-read"></a>![64KK  Sequential Read](plots.251001_133319/65536_read.png)|<a name="131072-read"></a>![128KK  Sequential Read](plots.251001_133319/131072_read.png)|
|<a name="262144-read"></a>![256KK  Sequential Read](plots.251001_133319/262144_read.png)|<a name="393216-read"></a>![384KK  Sequential Read](plots.251001_133319/393216_read.png)|
|<a name="524288-read"></a>![512KK  Sequential Read](plots.251001_133319/524288_read.png)|<a name="786432-read"></a>![768KK  Sequential Read](plots.251001_133319/786432_read.png)|
|<a name="1048576-read"></a>![1024KK  Sequential Read](plots.251001_133319/1048576_read.png)|<a name="2097152-read"></a>![2048KK  Sequential Read](plots.251001_133319/2097152_read.png)|
|<a name="4194304-read"></a>![4096KK  Sequential Read](plots.251001_133319/4194304_read.png)||

## Sequential Write

|||
| :---: | :---: |
|<a name="4096-write"></a>![4KK  Sequential Write](plots.251001_133319/4096_write.png)|<a name="8192-write"></a>![8KK  Sequential Write](plots.251001_133319/8192_write.png)|
|<a name="16384-write"></a>![16KK  Sequential Write](plots.251001_133319/16384_write.png)|<a name="32768-write"></a>![32KK  Sequential Write](plots.251001_133319/32768_write.png)|
|<a name="65536-write"></a>![64KK  Sequential Write](plots.251001_133319/65536_write.png)|<a name="131072-write"></a>![128KK  Sequential Write](plots.251001_133319/131072_write.png)|
|<a name="262144-write"></a>![256KK  Sequential Write](plots.251001_133319/262144_write.png)|<a name="393216-write"></a>![384KK  Sequential Write](plots.251001_133319/393216_write.png)|
|<a name="524288-write"></a>![512KK  Sequential Write](plots.251001_133319/524288_write.png)|<a name="786432-write"></a>![768KK  Sequential Write](plots.251001_133319/786432_write.png)|
|<a name="1048576-write"></a>![1024KK  Sequential Write](plots.251001_133319/1048576_write.png)|<a name="2097152-write"></a>![2048KK  Sequential Write](plots.251001_133319/2097152_write.png)|
|<a name="4194304-write"></a>![4096KK  Sequential Write](plots.251001_133319/4194304_write.png)||

## Random Read

|||
| :---: | :---: |
|<a name="4096-randread"></a>![4KK  Random Read](plots.251001_133319/4096_randread.png)|<a name="8192-randread"></a>![8KK  Random Read](plots.251001_133319/8192_randread.png)|
|<a name="16384-randread"></a>![16KK  Random Read](plots.251001_133319/16384_randread.png)|<a name="32768-randread"></a>![32KK  Random Read](plots.251001_133319/32768_randread.png)|
|<a name="65536-randread"></a>![64KK  Random Read](plots.251001_133319/65536_randread.png)|<a name="131072-randread"></a>![128KK  Random Read](plots.251001_133319/131072_randread.png)|
|<a name="262144-randread"></a>![256KK  Random Read](plots.251001_133319/262144_randread.png)|<a name="393216-randread"></a>![384KK  Random Read](plots.251001_133319/393216_randread.png)|
|<a name="524288-randread"></a>![512KK  Random Read](plots.251001_133319/524288_randread.png)|<a name="786432-randread"></a>![768KK  Random Read](plots.251001_133319/786432_randread.png)|
|<a name="1048576-randread"></a>![1024KK  Random Read](plots.251001_133319/1048576_randread.png)|<a name="2097152-randread"></a>![2048KK  Random Read](plots.251001_133319/2097152_randread.png)|
|<a name="4194304-randread"></a>![4096KK  Random Read](plots.251001_133319/4194304_randread.png)||

## Random Write

|||
| :---: | :---: |
|<a name="4096-randwrite"></a>![4KK  Random Write](plots.251001_133319/4096_randwrite.png)|<a name="8192-randwrite"></a>![8KK  Random Write](plots.251001_133319/8192_randwrite.png)|
|<a name="16384-randwrite"></a>![16KK  Random Write](plots.251001_133319/16384_randwrite.png)|<a name="32768-randwrite"></a>![32KK  Random Write](plots.251001_133319/32768_randwrite.png)|
|<a name="65536-randwrite"></a>![64KK  Random Write](plots.251001_133319/65536_randwrite.png)|<a name="262144-randwrite"></a>![256KK  Random Write](plots.251001_133319/262144_randwrite.png)|
|<a name="524288-randwrite"></a>![512KK  Random Write](plots.251001_133319/524288_randwrite.png)|<a name="1048576-randwrite"></a>![1024KK  Random Write](plots.251001_133319/1048576_randwrite.png)|

## Random Read/Write

|||
| :---: | :---: |
|<a name="4096-70-30-randrw"></a>![4KK 70/30  Random Read/Write](plots.251001_133319/4096_70_30_randrw.png)|<a name="16384-70-30-randrw"></a>![16KK 70/30  Random Read/Write](plots.251001_133319/16384_70_30_randrw.png)|
|<a name="65536-70-30-randrw"></a>![64KK 70/30  Random Read/Write](plots.251001_133319/65536_70_30_randrw.png)|<a name="65536-30-70-randrw"></a>![64KK 30/70  Random Read/Write](plots.251001_133319/65536_30_70_randrw.png)|

# Configuration yaml


```benchmarks:
  librbdfio:
    cmd_path: /usr/local/bin/fio
    fio_out_format: json
    log_avg_msec: 100
    log_bw: true
    log_iops: true
    log_lat: true
    norandommap: true
    osd_ra:
    - 4096
    poolname: rbd_replicated
    prefill:
      blocksize: 64k
      numjobs: 1
    procs_per_volume:
    - 1
    ramp: 30
    rbdname: cbt-librbdfio
    time: 90
    time_based: true
    use_existing_volumes: true
    vol_size: 608333
    volumes_per_client:
    - 16
    workloads:
      128krandomread:
        jobname: randread
        mode: randread
        numjobs:
        - 1
        op_size: 131072
        total_iodepth:
        - 4
        - 8
        - 12
        - 16
        - 32
        - 48
        - 64
        - 128
        - 256
        - 384
      16k7030:
        jobname: randmix
        mode: randrw
        numjobs:
        - 1
        op_size: 16384
        rwmixread: 70
        total_iodepth:
        - 1
        - 2
        - 3
        - 4
        - 8
        - 16
        - 24
        - 32
        - 64
        - 128
        - 256
      16krandomread:
        jobname: randread
        mode: randread
        numjobs:
        - 1
        op_size: 16384
        total_iodepth:
        - 4
        - 8
        - 12
        - 16
        - 24
        - 48
        - 64
        - 128
        - 256
        - 384
        - 588
      16krandomwrite:
        jobname: randwrite
        mode: randwrite
        numjobs:
        - 1
        op_size: 16384
        total_iodepth:
        - 1
        - 2
        - 3
        - 4
        - 8
        - 16
        - 32
        - 64
        - 128
        - 256
        - 384
        - 512
      1Mrandomread:
        jobname: randread
        mode: randread
        numjobs:
        - 1
        op_size: 1048576
        total_iodepth:
        - 1
        - 2
        - 3
        - 4
        - 8
        - 12
        - 16
        - 20
        - 24
        - 28
        - 32
        - 48
        - 64
        - 96
        - 128
      1Mrandomwrite:
        jobname: randwrite
        mode: randwrite
        numjobs:
        - 1
        op_size: 1048576
        total_iodepth:
        - 1
        - 2
        - 3
        - 4
        - 5
        - 6
        - 8
        - 16
        - 24
        - 32
        - 48
      1Mseqread:
        jobname: seqread
        mode: read
        numjobs:
        - 1
        op_size: 1048576
        total_iodepth:
        - 1
        - 2
        - 4
        - 8
        - 12
        - 16
        - 24
        - 32
        - 48
        - 64
        - 96
        - 128
        - 192
        - 256
      1Mseqwrite:
        jobname: seqwrite
        mode: write
        numjobs:
        - 1
        op_size: 1048576
        total_iodepth:
        - 2
        - 4
        - 6
        - 8
        - 16
        - 32
        - 48
        - 64
        - 96
        - 128
        - 160
      256krandomread:
        jobname: randread
        mode: randread
        numjobs:
        - 1
        op_size: 262144
        total_iodepth:
        - 1
        - 2
        - 3
        - 4
        - 5
        - 8
        - 16
        - 24
        - 32
        - 64
        - 128
        - 192
        - 256
      256krandomwrite:
        jobname: randwrite
        mode: randwrite
        numjobs:
        - 1
        op_size: 262144
        total_iodepth:
        - 1
        - 2
        - 3
        - 4
        - 5
        - 8
        - 16
        - 32
        - 64
        - 96
        - 128
        - 256
      2Mrandomread:
        jobname: randread
        mode: randread
        numjobs:
        - 1
        op_size: 2097152
        total_iodepth:
        - 4
        - 8
        - 12
        - 16
        - 32
        - 48
        - 64
        - 96
      2Mseqread:
        jobname: seqread
        mode: read
        numjobs:
        - 1
        op_size: 2097152
        total_iodepth:
        - 1
        - 2
        - 4
        - 8
        - 12
        - 16
        - 24
        - 32
        - 48
        - 64
        - 96
        - 128
      2Mseqwrite:
        jobname: seqwrite
        mode: write
        numjobs:
        - 1
        op_size: 2097152
        total_iodepth:
        - 1
        - 2
        - 4
        - 6
        - 8
        - 16
        - 32
        - 48
        - 64
      32krandomread:
        jobname: randread
        mode: randread
        numjobs:
        - 1
        op_size: 32768
        total_iodepth:
        - 2
        - 4
        - 6
        - 8
        - 12
        - 16
        - 24
        - 32
        - 64
        - 128
        - 256
        - 384
        - 512
      32krandomwrite:
        jobname: randwrite
        mode: randwrite
        numjobs:
        - 1
        op_size: 32768
        total_iodepth:
        - 1
        - 2
        - 3
        - 4
        - 8
        - 16
        - 32
        - 64
        - 128
        - 256
        - 384
        - 512
      384krandomread:
        jobname: randread
        mode: randread
        numjobs:
        - 1
        op_size: 393216
        total_iodepth:
        - 4
        - 8
        - 12
        - 16
        - 32
        - 48
        - 64
        - 128
        - 256
      4Mrandomread:
        jobname: randread
        mode: randread
        numjobs:
        - 1
        op_size: 4194304
        total_iodepth:
        - 4
        - 8
        - 12
        - 16
        - 32
        - 48
        - 64
        - 96
      4Mseqread:
        jobname: seqread
        mode: read
        numjobs:
        - 1
        op_size: 4194304
        total_iodepth:
        - 1
        - 2
        - 4
        - 8
        - 12
        - 16
        - 24
        - 32
        - 48
        - 64
      4Mseqwrite:
        jobname: seqwrite
        mode: write
        numjobs:
        - 1
        op_size: 4194304
        total_iodepth:
        - 1
        - 2
        - 4
        - 6
        - 8
        - 16
        - 32
      4k7030:
        jobname: randmix
        mode: randrw
        numjobs:
        - 1
        op_size: 4096
        rwmixread: 70
        total_iodepth:
        - 1
        - 2
        - 3
        - 4
        - 8
        - 16
        - 24
        - 32
        - 64
        - 128
        - 256
        - 384
      4krandomread:
        jobname: randread
        mode: randread
        numjobs:
        - 1
        op_size: 4096
        total_iodepth:
        - 4
        - 8
        - 12
        - 16
        - 32
        - 48
        - 64
        - 128
        - 256
        - 384
        - 512
        - 768
      4krandomwrite:
        jobname: randwrite
        mode: randwrite
        numjobs:
        - 1
        op_size: 4096
        total_iodepth:
        - 2
        - 4
        - 8
        - 16
        - 32
        - 64
        - 128
        - 256
        - 384
        - 512
        - 768
      512krandomread:
        jobname: randread
        mode: randread
        numjobs:
        - 1
        op_size: 524288
        total_iodepth:
        - 1
        - 2
        - 3
        - 4
        - 8
        - 16
        - 24
        - 32
        - 40
        - 48
        - 64
        - 96
        - 128
        - 192
        - 256
      512krandomwrite:
        jobname: randwrite
        mode: randwrite
        numjobs:
        - 1
        op_size: 524288
        total_iodepth:
        - 1
        - 2
        - 3
        - 4
        - 5
        - 6
        - 8
        - 16
        - 24
        - 32
        - 48
        - 64
      512kseqread:
        jobname: seqread
        mode: read
        numjobs:
        - 1
        op_size: 524288
        total_iodepth:
        - 1
        - 2
        - 4
        - 8
        - 12
        - 16
        - 24
        - 32
        - 48
        - 64
        - 96
        - 128
        - 192
        - 256
        - 384
      512kseqwrite:
        jobname: seqwrite
        mode: write
        numjobs:
        - 1
        op_size: 524288
        total_iodepth:
        - 1
        - 2
        - 4
        - 6
        - 8
        - 16
        - 32
        - 48
        - 64
        - 96
        - 128
      64k3070:
        jobname: randmix
        mode: randrw
        numjobs:
        - 1
        op_size: 65536
        rwmixread: 30
        total_iodepth:
        - 1
        - 2
        - 3
        - 4
        - 8
        - 16
        - 32
        - 64
        - 96
        - 128
        - 256
      64k7030:
        jobname: randmix
        mode: randrw
        numjobs:
        - 1
        op_size: 65536
        rwmixread: 70
        total_iodepth:
        - 1
        - 2
        - 3
        - 4
        - 8
        - 16
        - 32
        - 64
        - 96
        - 128
        - 256
      64krandomread:
        jobname: randread
        mode: randread
        numjobs:
        - 1
        op_size: 65536
        total_iodepth:
        - 2
        - 4
        - 6
        - 8
        - 12
        - 16
        - 24
        - 32
        - 64
        - 128
        - 256
        - 384
      64krandomwrite:
        jobname: randwrite
        mode: randwrite
        numjobs:
        - 1
        op_size: 65536
        total_iodepth:
        - 2
        - 4
        - 6
        - 8
        - 16
        - 24
        - 32
        - 64
        - 128
        - 256
        - 384
      64kseqread:
        jobname: seqread
        mode: read
        numjobs:
        - 1
        op_size: 65536
        total_iodepth:
        - 2
        - 4
        - 6
        - 8
        - 16
        - 24
        - 32
        - 64
        - 128
        - 192
        - 256
        - 384
      64kseqwrite:
        jobname: seqwrite
        mode: write
        numjobs:
        - 1
        op_size: 65536
        total_iodepth:
        - 4
        - 8
        - 12
        - 16
        - 32
        - 48
        - 64
        - 128
        - 256
        - 384
        - 512
      768krandomread:
        jobname: randread
        mode: randread
        numjobs:
        - 1
        op_size: 786432
        total_iodepth:
        - 4
        - 8
        - 12
        - 16
        - 32
        - 48
        - 64
        - 128
        - 192
      8krandomread:
        jobname: randread
        mode: randread
        numjobs:
        - 1
        op_size: 8192
        total_iodepth:
        - 4
        - 8
        - 12
        - 16
        - 32
        - 48
        - 64
        - 128
        - 256
        - 384
        - 588
        - 768
      8krandomwrite:
        jobname: randwrite
        mode: randwrite
        numjobs:
        - 1
        op_size: 8192
        total_iodepth:
        - 2
        - 4
        - 8
        - 16
        - 32
        - 64
        - 128
        - 256
        - 384
        - 512
        - 768
      precondition:
        jobname: precond1rw
        mode: randwrite
        monitor: false
        numjobs:
        - 1
        op_size: 65536
        time: 600
        total_iodepth:
        - 16
      seq128kread:
        jobname: seqread
        mode: read
        numjobs:
        - 1
        op_size: 131072
        total_iodepth:
        - 1
        - 2
        - 4
        - 8
        - 16
        - 32
        - 64
        - 128
        - 256
        - 512
      seq128kwrite:
        jobname: seqwrite
        mode: write
        numjobs:
        - 1
        op_size: 131072
        total_iodepth:
        - 1
        - 2
        - 4
        - 6
        - 8
        - 16
        - 32
        - 48
        - 64
        - 96
        - 128
        - 256
        - 384
      seq16kread:
        jobname: seqread
        mode: read
        numjobs:
        - 1
        op_size: 16384
        total_iodepth:
        - 2
        - 4
        - 8
        - 12
        - 16
        - 24
        - 32
        - 64
        - 96
        - 128
        - 192
        - 288
      seq16kwrite:
        jobname: seqwrite
        mode: write
        numjobs:
        - 1
        op_size: 16384
        total_iodepth:
        - 2
        - 4
        - 8
        - 16
        - 32
        - 48
        - 64
        - 128
        - 256
        - 384
        - 512
        - 768
        - 1024
      seq256kread:
        jobname: seqread
        mode: read
        numjobs:
        - 1
        op_size: 262144
        total_iodepth:
        - 1
        - 2
        - 4
        - 8
        - 16
        - 32
        - 64
        - 128
        - 256
        - 512
        - 768
      seq256kwrite:
        jobname: seqwrite
        mode: write
        numjobs:
        - 1
        op_size: 262144
        total_iodepth:
        - 1
        - 2
        - 4
        - 8
        - 16
        - 24
        - 32
        - 64
        - 96
        - 128
        - 256
      seq32kread:
        jobname: seqread
        mode: read
        numjobs:
        - 1
        op_size: 32768
        total_iodepth:
        - 2
        - 4
        - 8
        - 12
        - 16
        - 24
        - 32
        - 64
        - 96
        - 128
        - 192
        - 256
      seq32kwrite:
        jobname: seqwrite
        mode: write
        numjobs:
        - 1
        op_size: 32768
        total_iodepth:
        - 2
        - 4
        - 8
        - 16
        - 32
        - 64
        - 128
        - 256
        - 512
        - 768
      seq384kread:
        jobname: seqread
        mode: read
        numjobs:
        - 1
        op_size: 393216
        total_iodepth:
        - 1
        - 2
        - 4
        - 8
        - 16
        - 32
        - 64
        - 128
        - 192
      seq384kwrite:
        jobname: seqwrite
        mode: write
        numjobs:
        - 1
        op_size: 393216
        total_iodepth:
        - 1
        - 2
        - 4
        - 6
        - 8
        - 16
        - 32
        - 48
        - 64
        - 96
        - 128
        - 256
        - 512
      seq4kread:
        jobname: seqread
        mode: read
        numjobs:
        - 1
        op_size: 4096
        total_iodepth:
        - 2
        - 4
        - 8
        - 12
        - 16
        - 24
        - 32
        - 64
        - 96
        - 128
        - 192
        - 288
        - 384
      seq4kwrite:
        jobname: seqwrite
        mode: write
        numjobs:
        - 1
        op_size: 4096
        total_iodepth:
        - 2
        - 8
        - 16
        - 24
        - 32
        - 48
        - 64
        - 128
        - 256
        - 384
        - 512
        - 768
        - 1024
        - 1280
        - 1536
      seq768kread:
        jobname: seqread
        mode: read
        numjobs:
        - 1
        op_size: 786432
        total_iodepth:
        - 1
        - 2
        - 4
        - 8
        - 12
        - 16
        - 24
        - 32
        - 48
        - 64
        - 96
        - 128
        - 192
        - 256
        - 384
      seq768kwrite:
        jobname: seqwrite
        mode: write
        numjobs:
        - 1
        op_size: 786432
        total_iodepth:
        - 1
        - 2
        - 4
        - 6
        - 8
        - 16
        - 32
        - 48
        - 64
        - 96
        - 128
      seq8kread:
        jobname: seqread
        mode: read
        numjobs:
        - 1
        op_size: 8192
        total_iodepth:
        - 2
        - 4
        - 8
        - 12
        - 16
        - 24
        - 32
        - 64
        - 96
        - 128
        - 192
        - 288
        - 384
      seq8kwrite:
        jobname: seqwrite
        mode: write
        numjobs:
        - 1
        op_size: 8192
        total_iodepth:
        - 2
        - 8
        - 16
        - 24
        - 32
        - 48
        - 64
        - 128
        - 256
        - 384
        - 512
        - 768
        - 1024
        - 1280
        - 1536
cluster:
  archive_dir: /tmp/cbt
  ceph-mgr_cmd: /usr/bin/ceph-mgr
  ceph-mon_cmd: /usr/bin/ceph-mon
  ceph-osd_cmd: /usr/bin/ceph-osd
  ceph-run_cmd: /usr/bin/ceph-run
  ceph_cmd: /usr/bin/ceph
  clients:
  - --- server1 ---
  clusterid: ceph
  conf_file: /cbt/ceph.conf.4x1x1.fs
  fs: xfs
  head: --- server1 ---
  iterations: 1
  mgrs:
    --- server1 ---:
      a: null
  mkfs_opts: -f -i size=2048
  mons:
    --- server1 ---:
      a: --- IP Address --:6789
  mount_opts: -o inode64,noatime,logbsize=256k
  osds:
  - --- server1 ---
  osds_per_node: 8
  pdsh_ssh_args: -a -x -l%u %h
  rados_cmd: /usr/bin/rados
  rbd_cmd: /usr/bin/rbd
  tmp_dir: /tmp/cbt
  use_existing: true
  user: ljsanders
monitoring_profiles:
  collectl:
    args: -c 18 -sCD -i 10 -P -oz -F0 --rawtoo --sep ";" -f {collectl_dir}
```