
Performance Report for 10th-Oct-Clay-4+2+5-OSD-down
===================================================

Table of contents
=================

* [Summary of results for 10th-Oct-Clay-4+2+5-OSD-down](#summary-of-results-for-10th-oct-clay-425-osd-down)
* [Response Curves](#response-curves)
	* [Sequential Read](#sequential-read)
	* [Sequential Write](#sequential-write)
	* [Random Read](#random-read)
	* [Random Write](#random-write)
	* [Random Read/Write](#random-readwrite)
* [Configuration yaml](#configuration-yaml)

# Summary of results for 10th-Oct-Clay-4+2+5-OSD-down
  
|Workload Name|Maximum Throughput|Latency (ms)|  
| :--- | ---: | ---: |  
|[4096_read](#4096-read)|77823 IOps|4.9|  
|[8192_read](#8192-read)|64407 IOps|6.0|  
|[16384_read](#16384-read)|50059 IOps|5.7|  
|[32768_read](#32768-read)|43847 IOps|4.4|  
|[65536_read](#65536-read)|2198 MB/s|3.8|  
|[262144_read](#262144-read)|5293 MB/s|25.4|  
|[524288_read](#524288-read)|5971 MB/s|22.5|  
|[1048576_read](#1048576-read)|6579 MB/s|40.8|  
|[4096_write](#4096-write)|141456 IOps|10.9|  
|[8192_write](#8192-write)|135906 IOps|11.3|  
|[16384_write](#16384-write)|106849 IOps|9.6|  
|[32768_write](#32768-write)|62200 IOps|12.3|  
|[65536_write](#65536-write)|2265 MB/s|14.8|  
|[262144_write](#262144-write)|2964 MB/s|22.5|  
|[524288_write](#524288-write)|3131 MB/s|21.2|  
|[1048576_write](#1048576-write)|4006 MB/s|41.4|  
|[4096_randread](#4096-randread)|52005 IOps|14.8|  
|[8192_randread](#8192-randread)|54067 IOps|14.2|  
|[16384_randread](#16384-randread)|53659 IOps|11.0|  
|[32768_randread](#32768-randread)|47593 IOps|10.8|  
|[65536_randread](#65536-randread)|2548 MB/s|9.9|  
|[262144_randread](#262144-randread)|5313 MB/s|6.3|  
|[524288_randread](#524288-randread)|6562 MB/s|40.9|  
|[1048576_randread](#1048576-randread)|6848 MB/s|39.2|  
|[4096_randwrite](#4096-randwrite)|14501 IOps|8.8|  
|[8192_randwrite](#8192-randwrite)|13427 IOps|57.2|  
|[16384_randwrite](#16384-randwrite)|17030 IOps|30.0|  
|[32768_randwrite](#32768-randwrite)|16577 IOps|23.1|  
|[65536_randwrite](#65536-randwrite)|1070 MB/s|23.5|  
|[262144_randwrite](#262144-randwrite)|2996 MB/s|22.3|  
|[524288_randwrite](#524288-randwrite)|3433 MB/s|9.5|  
|[1048576_randwrite](#1048576-randwrite)|3860 MB/s|12.6|  
|[4096_70_30_randrw](#4096-70-30-randrw)|24728 IOps|15.5|  
|[16384_70_30_randrw](#16384-70-30-randrw)|26630 IOps|4.8|  
|[65536_30_70_randrw](#65536-30-70-randrw)|1161 MB/s|14.4|  
|[65536_70_30_randrw](#65536-70-30-randrw)|1538 MB/s|4.1|
# Response Curves

## Sequential Read

|||
| :---: | :---: |
|<a name="4096-read"></a>![4KK  Sequential Read](plots.251010_104753/4096_read.svg)|<a name="8192-read"></a>![8KK  Sequential Read](plots.251010_104753/8192_read.svg)|
|<a name="16384-read"></a>![16KK  Sequential Read](plots.251010_104753/16384_read.svg)|<a name="32768-read"></a>![32KK  Sequential Read](plots.251010_104753/32768_read.svg)|
|<a name="65536-read"></a>![64KK  Sequential Read](plots.251010_104753/65536_read.svg)|<a name="262144-read"></a>![256KK  Sequential Read](plots.251010_104753/262144_read.svg)|
|<a name="524288-read"></a>![512KK  Sequential Read](plots.251010_104753/524288_read.svg)|<a name="1048576-read"></a>![1024KK  Sequential Read](plots.251010_104753/1048576_read.svg)|

## Sequential Write

|||
| :---: | :---: |
|<a name="4096-write"></a>![4KK  Sequential Write](plots.251010_104753/4096_write.svg)|<a name="8192-write"></a>![8KK  Sequential Write](plots.251010_104753/8192_write.svg)|
|<a name="16384-write"></a>![16KK  Sequential Write](plots.251010_104753/16384_write.svg)|<a name="32768-write"></a>![32KK  Sequential Write](plots.251010_104753/32768_write.svg)|
|<a name="65536-write"></a>![64KK  Sequential Write](plots.251010_104753/65536_write.svg)|<a name="262144-write"></a>![256KK  Sequential Write](plots.251010_104753/262144_write.svg)|
|<a name="524288-write"></a>![512KK  Sequential Write](plots.251010_104753/524288_write.svg)|<a name="1048576-write"></a>![1024KK  Sequential Write](plots.251010_104753/1048576_write.svg)|

## Random Read

|||
| :---: | :---: |
|<a name="4096-randread"></a>![4KK  Random Read](plots.251010_104753/4096_randread.svg)|<a name="8192-randread"></a>![8KK  Random Read](plots.251010_104753/8192_randread.svg)|
|<a name="16384-randread"></a>![16KK  Random Read](plots.251010_104753/16384_randread.svg)|<a name="32768-randread"></a>![32KK  Random Read](plots.251010_104753/32768_randread.svg)|
|<a name="65536-randread"></a>![64KK  Random Read](plots.251010_104753/65536_randread.svg)|<a name="262144-randread"></a>![256KK  Random Read](plots.251010_104753/262144_randread.svg)|
|<a name="524288-randread"></a>![512KK  Random Read](plots.251010_104753/524288_randread.svg)|<a name="1048576-randread"></a>![1024KK  Random Read](plots.251010_104753/1048576_randread.svg)|

## Random Write

|||
| :---: | :---: |
|<a name="4096-randwrite"></a>![4KK  Random Write](plots.251010_104753/4096_randwrite.svg)|<a name="8192-randwrite"></a>![8KK  Random Write](plots.251010_104753/8192_randwrite.svg)|
|<a name="16384-randwrite"></a>![16KK  Random Write](plots.251010_104753/16384_randwrite.svg)|<a name="32768-randwrite"></a>![32KK  Random Write](plots.251010_104753/32768_randwrite.svg)|
|<a name="65536-randwrite"></a>![64KK  Random Write](plots.251010_104753/65536_randwrite.svg)|<a name="262144-randwrite"></a>![256KK  Random Write](plots.251010_104753/262144_randwrite.svg)|
|<a name="524288-randwrite"></a>![512KK  Random Write](plots.251010_104753/524288_randwrite.svg)|<a name="1048576-randwrite"></a>![1024KK  Random Write](plots.251010_104753/1048576_randwrite.svg)|

## Random Read/Write

|||
| :---: | :---: |
|<a name="4096-70-30-randrw"></a>![4KK 70/30  Random Read/Write](plots.251010_104753/4096_70_30_randrw.svg)|<a name="16384-70-30-randrw"></a>![16KK 70/30  Random Read/Write](plots.251010_104753/16384_70_30_randrw.svg)|
|<a name="65536-70-30-randrw"></a>![64KK 70/30  Random Read/Write](plots.251010_104753/65536_70_30_randrw.svg)|<a name="65536-30-70-randrw"></a>![64KK 30/70  Random Read/Write](plots.251010_104753/65536_30_70_randrw.svg)|

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
    vol_size: 1204500
    volumes_per_client:
    - 16
    workloads:
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
        - 4
        - 8
        - 16
        - 32
        - 64
        - 128
        - 256
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
        - 588
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
        - 4
        - 8
        - 16
        - 32
        - 64
        - 128
        - 256
        - 512
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
        - 256
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
        jobname: read
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
      64kseqwrite:
        jobname: write
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