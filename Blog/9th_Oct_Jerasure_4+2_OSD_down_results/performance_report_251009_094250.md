
Performance Report for 9th-Oct-Jerasure-4+2-OSD-down
====================================================

Table of contents
=================

* [Summary of results for 9th-Oct-Jerasure-4+2-OSD-down](#summary-of-results-for-9th-oct-jerasure-42-osd-down)
* [Response Curves](#response-curves)
	* [Sequential Read](#sequential-read)
	* [Sequential Write](#sequential-write)
	* [Random Read](#random-read)
	* [Random Write](#random-write)
	* [Random Read/Write](#random-readwrite)
* [Configuration yaml](#configuration-yaml)

# Summary of results for 9th-Oct-Jerasure-4+2-OSD-down
  
|Workload Name|Maximum Throughput|Latency (ms)|  
| :--- | ---: | ---: |  
|[4096_read](#4096-read)|86279 IOps|4.4|  
|[8192_read](#8192-read)|71977 IOps|5.3|  
|[16384_read](#16384-read)|54546 IOps|5.3|  
|[32768_read](#32768-read)|49597 IOps|3.9|  
|[65536_read](#65536-read)|2757 MB/s|3.0|  
|[262144_read](#262144-read)|6370 MB/s|21.1|  
|[524288_read](#524288-read)|7061 MB/s|19.0|  
|[1048576_read](#1048576-read)|7528 MB/s|35.7|  
|[4096_write](#4096-write)|154904 IOps|9.9|  
|[8192_write](#8192-write)|159837 IOps|9.6|  
|[16384_write](#16384-write)|138893 IOps|7.4|  
|[32768_write](#32768-write)|81494 IOps|9.4|  
|[65536_write](#65536-write)|2818 MB/s|8.9|  
|[262144_write](#262144-write)|3714 MB/s|17.9|  
|[524288_write](#524288-write)|3805 MB/s|17.4|  
|[1048576_write](#1048576-write)|4634 MB/s|35.7|  
|[4096_randread](#4096-randread)|56798 IOps|13.5|  
|[8192_randread](#8192-randread)|57036 IOps|13.5|  
|[16384_randread](#16384-randread)|56520 IOps|10.4|  
|[32768_randread](#32768-randread)|50856 IOps|7.5|  
|[65536_randread](#65536-randread)|2909 MB/s|8.6|  
|[262144_randread](#262144-randread)|5741 MB/s|5.8|  
|[524288_randread](#524288-randread)|7162 MB/s|37.5|  
|[1048576_randread](#1048576-randread)|7443 MB/s|36.1|  
|[4096_randwrite](#4096-randwrite)|14933 IOps|17.1|  
|[8192_randwrite](#8192-randwrite)|14418 IOps|53.3|  
|[16384_randwrite](#16384-randwrite)|17735 IOps|28.9|  
|[32768_randwrite](#32768-randwrite)|17104 IOps|22.4|  
|[65536_randwrite](#65536-randwrite)|1115 MB/s|15.0|  
|[262144_randwrite](#262144-randwrite)|3188 MB/s|20.9|  
|[524288_randwrite](#524288-randwrite)|3788 MB/s|8.6|  
|[1048576_randwrite](#1048576-randwrite)|4430 MB/s|10.9|  
|[4096_70_30_randrw](#4096-70-30-randrw)|25977 IOps|14.8|  
|[16384_70_30_randrw](#16384-70-30-randrw)|28007 IOps|9.1|  
|[65536_30_70_randrw](#65536-30-70-randrw)|1291 MB/s|13.0|  
|[65536_70_30_randrw](#65536-70-30-randrw)|1688 MB/s|5.0|
# Response Curves

## Sequential Read

|||
| :---: | :---: |
|<a name="4096-read"></a>![4KK  Sequential Read](plots.251009_094250/4096_read.png)|<a name="8192-read"></a>![8KK  Sequential Read](plots.251009_094250/8192_read.png)|
|<a name="16384-read"></a>![16KK  Sequential Read](plots.251009_094250/16384_read.png)|<a name="32768-read"></a>![32KK  Sequential Read](plots.251009_094250/32768_read.png)|
|<a name="65536-read"></a>![64KK  Sequential Read](plots.251009_094250/65536_read.png)|<a name="262144-read"></a>![256KK  Sequential Read](plots.251009_094250/262144_read.png)|
|<a name="524288-read"></a>![512KK  Sequential Read](plots.251009_094250/524288_read.png)|<a name="1048576-read"></a>![1024KK  Sequential Read](plots.251009_094250/1048576_read.png)|

## Sequential Write

|||
| :---: | :---: |
|<a name="4096-write"></a>![4KK  Sequential Write](plots.251009_094250/4096_write.png)|<a name="8192-write"></a>![8KK  Sequential Write](plots.251009_094250/8192_write.png)|
|<a name="16384-write"></a>![16KK  Sequential Write](plots.251009_094250/16384_write.png)|<a name="32768-write"></a>![32KK  Sequential Write](plots.251009_094250/32768_write.png)|
|<a name="65536-write"></a>![64KK  Sequential Write](plots.251009_094250/65536_write.png)|<a name="262144-write"></a>![256KK  Sequential Write](plots.251009_094250/262144_write.png)|
|<a name="524288-write"></a>![512KK  Sequential Write](plots.251009_094250/524288_write.png)|<a name="1048576-write"></a>![1024KK  Sequential Write](plots.251009_094250/1048576_write.png)|

## Random Read

|||
| :---: | :---: |
|<a name="4096-randread"></a>![4KK  Random Read](plots.251009_094250/4096_randread.png)|<a name="8192-randread"></a>![8KK  Random Read](plots.251009_094250/8192_randread.png)|
|<a name="16384-randread"></a>![16KK  Random Read](plots.251009_094250/16384_randread.png)|<a name="32768-randread"></a>![32KK  Random Read](plots.251009_094250/32768_randread.png)|
|<a name="65536-randread"></a>![64KK  Random Read](plots.251009_094250/65536_randread.png)|<a name="262144-randread"></a>![256KK  Random Read](plots.251009_094250/262144_randread.png)|
|<a name="524288-randread"></a>![512KK  Random Read](plots.251009_094250/524288_randread.png)|<a name="1048576-randread"></a>![1024KK  Random Read](plots.251009_094250/1048576_randread.png)|

## Random Write

|||
| :---: | :---: |
|<a name="4096-randwrite"></a>![4KK  Random Write](plots.251009_094250/4096_randwrite.png)|<a name="8192-randwrite"></a>![8KK  Random Write](plots.251009_094250/8192_randwrite.png)|
|<a name="16384-randwrite"></a>![16KK  Random Write](plots.251009_094250/16384_randwrite.png)|<a name="32768-randwrite"></a>![32KK  Random Write](plots.251009_094250/32768_randwrite.png)|
|<a name="65536-randwrite"></a>![64KK  Random Write](plots.251009_094250/65536_randwrite.png)|<a name="262144-randwrite"></a>![256KK  Random Write](plots.251009_094250/262144_randwrite.png)|
|<a name="524288-randwrite"></a>![512KK  Random Write](plots.251009_094250/524288_randwrite.png)|<a name="1048576-randwrite"></a>![1024KK  Random Write](plots.251009_094250/1048576_randwrite.png)|

## Random Read/Write

|||
| :---: | :---: |
|<a name="4096-70-30-randrw"></a>![4KK 70/30  Random Read/Write](plots.251009_094250/4096_70_30_randrw.png)|<a name="16384-70-30-randrw"></a>![16KK 70/30  Random Read/Write](plots.251009_094250/16384_70_30_randrw.png)|
|<a name="65536-70-30-randrw"></a>![64KK 70/30  Random Read/Write](plots.251009_094250/65536_70_30_randrw.png)|<a name="65536-30-70-randrw"></a>![64KK 30/70  Random Read/Write](plots.251009_094250/65536_30_70_randrw.png)|

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