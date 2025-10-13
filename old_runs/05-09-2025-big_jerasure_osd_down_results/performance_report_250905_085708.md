
Performance Report for 05-09-2025-big-jerasure-osd-down
=======================================================

Table of contents
=================

* [Summary of results for 05-09-2025-big-jerasure-osd-down](#summary-of-results-for-05-09-2025-big-jerasure-osd-down)
* [Response Curves](#response-curves)
	* [Sequential Read](#sequential-read)
	* [Sequential Write](#sequential-write)
	* [Random Read](#random-read)
	* [Random Write](#random-write)
	* [Random Read/Write](#random-readwrite)
* [Configuration yaml](#configuration-yaml)

# Summary of results for 05-09-2025-big-jerasure-osd-down
  
|Workload Name|Maximum Throughput|Latency (ms)|  
| :--- | ---: | ---: |  
|[4096_read](#4096-read)|65009 IOps|2.9|  
|[8192_read](#8192-read)|38624 IOps|5.0|  
|[16384_read](#16384-read)|22778 IOps|8.4|  
|[32768_read](#32768-read)|19055 IOps|10.1|  
|[65536_read](#65536-read)|1093 MB/s|15.3|  
|[262144_read](#262144-read)|1582 MB/s|10.6|  
|[524288_read](#524288-read)|1587 MB/s|10.6|  
|[1048576_read](#1048576-read)|1593 MB/s|13.2|  
|[4096_write](#4096-write)|23450 IOps|43.7|  
|[8192_write](#8192-write)|24356 IOps|52.6|  
|[16384_write](#16384-write)|11478 IOps|44.6|  
|[32768_write](#32768-write)|12575 IOps|61.0|  
|[65536_write](#65536-write)|253 MB/s|132.9|  
|[262144_write](#262144-write)|600 MB/s|111.7|  
|[524288_write](#524288-write)|304 MB/s|221.0|  
|[1048576_write](#1048576-write)|362 MB/s|464.8|  
|[4096_randread](#4096-randread)|68041 IOps|5.6|  
|[8192_randread](#8192-randread)|44860 IOps|5.7|  
|[16384_randread](#16384-randread)|32095 IOps|8.0|  
|[32768_randread](#32768-randread)|28901 IOps|8.8|  
|[65536_randread](#65536-randread)|1443 MB/s|5.8|  
|[262144_randread](#262144-randread)|1632 MB/s|20.6|  
|[524288_randread](#524288-randread)|1794 MB/s|14.0|  
|[1048576_randread](#1048576-randread)|1797 MB/s|16.3|  
|[4096_randwrite](#4096-randwrite)|6659 IOps|57.7|  
|[8192_randwrite](#8192-randwrite)|6551 IOps|78.1|  
|[16384_randwrite](#16384-randwrite)|6436 IOps|79.5|  
|[32768_randwrite](#32768-randwrite)|4818 IOps|106.2|  
|[65536_randwrite](#65536-randwrite)|242 MB/s|103.9|  
|[262144_randwrite](#262144-randwrite)|338 MB/s|198.6|  
|[524288_randwrite](#524288-randwrite)|302 MB/s|110.7|  
|[1048576_randwrite](#1048576-randwrite)|319 MB/s|157.1|  
|[4096_70_30_randrw](#4096-70-30-randrw)|11146 IOps|23.0|  
|[16384_70_30_randrw](#16384-70-30-randrw)|6406 IOps|40.0|  
|[65536_70_30_randrw](#65536-70-30-randrw)|195 MB/s|86.2|  
|[65536_30_70_randrw](#65536-30-70-randrw)|187 MB/s|89.7|
# Response Curves

## Sequential Read

|||
| :---: | :---: |
|<a name="4096-read"></a>![4.0KK  Sequential Read](plots.250905_085708/4096_read.png)|<a name="8192-read"></a>![8.0KK  Sequential Read](plots.250905_085708/8192_read.png)|
|<a name="16384-read"></a>![16.0KK  Sequential Read](plots.250905_085708/16384_read.png)|<a name="32768-read"></a>![32.0KK  Sequential Read](plots.250905_085708/32768_read.png)|
|<a name="65536-read"></a>![64.0KK  Sequential Read](plots.250905_085708/65536_read.png)|<a name="262144-read"></a>![256.0KK  Sequential Read](plots.250905_085708/262144_read.png)|
|<a name="524288-read"></a>![512.0KK  Sequential Read](plots.250905_085708/524288_read.png)|<a name="1048576-read"></a>![1024.0KK  Sequential Read](plots.250905_085708/1048576_read.png)|

## Sequential Write

|||
| :---: | :---: |
|<a name="4096-write"></a>![4.0KK  Sequential Write](plots.250905_085708/4096_write.png)|<a name="8192-write"></a>![8.0KK  Sequential Write](plots.250905_085708/8192_write.png)|
|<a name="16384-write"></a>![16.0KK  Sequential Write](plots.250905_085708/16384_write.png)|<a name="32768-write"></a>![32.0KK  Sequential Write](plots.250905_085708/32768_write.png)|
|<a name="65536-write"></a>![64.0KK  Sequential Write](plots.250905_085708/65536_write.png)|<a name="262144-write"></a>![256.0KK  Sequential Write](plots.250905_085708/262144_write.png)|
|<a name="524288-write"></a>![512.0KK  Sequential Write](plots.250905_085708/524288_write.png)|<a name="1048576-write"></a>![1024.0KK  Sequential Write](plots.250905_085708/1048576_write.png)|

## Random Read

|||
| :---: | :---: |
|<a name="4096-randread"></a>![4.0KK  Random Read](plots.250905_085708/4096_randread.png)|<a name="8192-randread"></a>![8.0KK  Random Read](plots.250905_085708/8192_randread.png)|
|<a name="16384-randread"></a>![16.0KK  Random Read](plots.250905_085708/16384_randread.png)|<a name="32768-randread"></a>![32.0KK  Random Read](plots.250905_085708/32768_randread.png)|
|<a name="65536-randread"></a>![64.0KK  Random Read](plots.250905_085708/65536_randread.png)|<a name="262144-randread"></a>![256.0KK  Random Read](plots.250905_085708/262144_randread.png)|
|<a name="524288-randread"></a>![512.0KK  Random Read](plots.250905_085708/524288_randread.png)|<a name="1048576-randread"></a>![1024.0KK  Random Read](plots.250905_085708/1048576_randread.png)|

## Random Write

|||
| :---: | :---: |
|<a name="4096-randwrite"></a>![4.0KK  Random Write](plots.250905_085708/4096_randwrite.png)|<a name="8192-randwrite"></a>![8.0KK  Random Write](plots.250905_085708/8192_randwrite.png)|
|<a name="16384-randwrite"></a>![16.0KK  Random Write](plots.250905_085708/16384_randwrite.png)|<a name="32768-randwrite"></a>![32.0KK  Random Write](plots.250905_085708/32768_randwrite.png)|
|<a name="65536-randwrite"></a>![64.0KK  Random Write](plots.250905_085708/65536_randwrite.png)|<a name="262144-randwrite"></a>![256.0KK  Random Write](plots.250905_085708/262144_randwrite.png)|
|<a name="524288-randwrite"></a>![512.0KK  Random Write](plots.250905_085708/524288_randwrite.png)|<a name="1048576-randwrite"></a>![1024.0KK  Random Write](plots.250905_085708/1048576_randwrite.png)|

## Random Read/Write

|||
| :---: | :---: |
|<a name="4096-70-30-randrw"></a>![4.0KK 70/30  Random Read/Write](plots.250905_085708/4096_70_30_randrw.png)|<a name="16384-70-30-randrw"></a>![16.0KK 70/30  Random Read/Write](plots.250905_085708/16384_70_30_randrw.png)|
|<a name="65536-70-30-randrw"></a>![64.0KK 70/30  Random Read/Write](plots.250905_085708/65536_70_30_randrw.png)|<a name="65536-30-70-randrw"></a>![64.0KK 30/70  Random Read/Write](plots.250905_085708/65536_30_70_randrw.png)|

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
    vol_size: 52500
    volumes_per_client:
    - 8
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
        - 3
        - 4
        - 6
        - 8
        - 10
        - 12
        - 14
        - 16
        - 20
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
        - 3
        - 4
        - 6
        - 8
        - 12
        - 16
        - 20
        - 24
        - 32
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
      seq256kread:
        jobname: seqread
        mode: read
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
        - 48
        - 64
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
  osds_per_node: 6
  pdsh_ssh_args: -a -x -l%u %h
  rados_cmd: /usr/bin/rados
  rbd_cmd: /usr/bin/rbd
  tmp_dir: /tmp/cbt
  use_existing: true
  user: root
monitoring_profiles:
  collectl:
    args: -c 18 -sCD -i 10 -P -oz -F0 --rawtoo --sep ";" -f {collectl_dir}
```