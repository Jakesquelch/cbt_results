
Performance Report for 10-09-2025-cbt-osd-down-jerasure-ec-off
==============================================================

Table of contents
=================

* [Summary of results for 10-09-2025-cbt-osd-down-jerasure-ec-off](#summary-of-results-for-10-09-2025-cbt-osd-down-jerasure-ec-off)
* [Response Curves](#response-curves)
	* [Sequential Read](#sequential-read)
	* [Sequential Write](#sequential-write)
	* [Random Read](#random-read)
	* [Random Write](#random-write)
	* [Random Read/Write](#random-readwrite)
* [Configuration yaml](#configuration-yaml)

# Summary of results for 10-09-2025-cbt-osd-down-jerasure-ec-off
  
|Workload Name|Maximum Throughput|Latency (ms)|  
| :--- | ---: | ---: |  
|[4096_read](#4096-read)|63495 IOps|3.0|  
|[8192_read](#8192-read)|37848 IOps|5.1|  
|[16384_read](#16384-read)|22299 IOps|8.6|  
|[32768_read](#32768-read)|18560 IOps|10.3|  
|[65536_read](#65536-read)|1076 MB/s|15.6|  
|[262144_read](#262144-read)|1572 MB/s|10.7|  
|[524288_read](#524288-read)|1581 MB/s|10.6|  
|[1048576_read](#1048576-read)|1589 MB/s|13.2|  
|[4096_write](#4096-write)|18086 IOps|56.6|  
|[8192_write](#8192-write)|20093 IOps|63.7|  
|[16384_write](#16384-write)|9698 IOps|52.8|  
|[32768_write](#32768-write)|12589 IOps|61.0|  
|[65536_write](#65536-write)|248 MB/s|135.4|  
|[262144_write](#262144-write)|604 MB/s|111.0|  
|[524288_write](#524288-write)|308 MB/s|217.7|  
|[1048576_write](#1048576-write)|356 MB/s|472.4|  
|[4096_randread](#4096-randread)|64252 IOps|6.0|  
|[8192_randread](#8192-randread)|42708 IOps|6.0|  
|[16384_randread](#16384-randread)|30732 IOps|8.3|  
|[32768_randread](#32768-randread)|27550 IOps|9.3|  
|[65536_randread](#65536-randread)|1392 MB/s|6.0|  
|[262144_randread](#262144-randread)|1654 MB/s|10.1|  
|[524288_randread](#524288-randread)|1792 MB/s|9.3|  
|[1048576_randread](#1048576-randread)|1791 MB/s|16.4|  
|[4096_randwrite](#4096-randwrite)|3912 IOps|131.6|  
|[8192_randwrite](#8192-randwrite)|3321 IOps|154.1|  
|[16384_randwrite](#16384-randwrite)|6084 IOps|84.1|  
|[32768_randwrite](#32768-randwrite)|4705 IOps|108.7|  
|[65536_randwrite](#65536-randwrite)|236 MB/s|106.6|  
|[262144_randwrite](#262144-randwrite)|335 MB/s|200.2|  
|[524288_randwrite](#524288-randwrite)|299 MB/s|111.8|  
|[1048576_randwrite](#1048576-randwrite)|325 MB/s|154.6|  
|[4096_70_30_randrw](#4096-70-30-randrw)|8665 IOps|29.5|  
|[16384_70_30_randrw](#16384-70-30-randrw)|6198 IOps|41.3|  
|[65536_70_30_randrw](#65536-70-30-randrw)|192 MB/s|87.4|  
|[65536_30_70_randrw](#65536-30-70-randrw)|216 MB/s|77.7|
# Response Curves

## Sequential Read

|||
| :---: | :---: |
|<a name="4096-read"></a>![4.0KK  Sequential Read](plots.250910_092542/4096_read.png)|<a name="8192-read"></a>![8.0KK  Sequential Read](plots.250910_092542/8192_read.png)|
|<a name="16384-read"></a>![16.0KK  Sequential Read](plots.250910_092542/16384_read.png)|<a name="32768-read"></a>![32.0KK  Sequential Read](plots.250910_092542/32768_read.png)|
|<a name="65536-read"></a>![64.0KK  Sequential Read](plots.250910_092542/65536_read.png)|<a name="262144-read"></a>![256.0KK  Sequential Read](plots.250910_092542/262144_read.png)|
|<a name="524288-read"></a>![512.0KK  Sequential Read](plots.250910_092542/524288_read.png)|<a name="1048576-read"></a>![1024.0KK  Sequential Read](plots.250910_092542/1048576_read.png)|

## Sequential Write

|||
| :---: | :---: |
|<a name="4096-write"></a>![4.0KK  Sequential Write](plots.250910_092542/4096_write.png)|<a name="8192-write"></a>![8.0KK  Sequential Write](plots.250910_092542/8192_write.png)|
|<a name="16384-write"></a>![16.0KK  Sequential Write](plots.250910_092542/16384_write.png)|<a name="32768-write"></a>![32.0KK  Sequential Write](plots.250910_092542/32768_write.png)|
|<a name="65536-write"></a>![64.0KK  Sequential Write](plots.250910_092542/65536_write.png)|<a name="262144-write"></a>![256.0KK  Sequential Write](plots.250910_092542/262144_write.png)|
|<a name="524288-write"></a>![512.0KK  Sequential Write](plots.250910_092542/524288_write.png)|<a name="1048576-write"></a>![1024.0KK  Sequential Write](plots.250910_092542/1048576_write.png)|

## Random Read

|||
| :---: | :---: |
|<a name="4096-randread"></a>![4.0KK  Random Read](plots.250910_092542/4096_randread.png)|<a name="8192-randread"></a>![8.0KK  Random Read](plots.250910_092542/8192_randread.png)|
|<a name="16384-randread"></a>![16.0KK  Random Read](plots.250910_092542/16384_randread.png)|<a name="32768-randread"></a>![32.0KK  Random Read](plots.250910_092542/32768_randread.png)|
|<a name="65536-randread"></a>![64.0KK  Random Read](plots.250910_092542/65536_randread.png)|<a name="262144-randread"></a>![256.0KK  Random Read](plots.250910_092542/262144_randread.png)|
|<a name="524288-randread"></a>![512.0KK  Random Read](plots.250910_092542/524288_randread.png)|<a name="1048576-randread"></a>![1024.0KK  Random Read](plots.250910_092542/1048576_randread.png)|

## Random Write

|||
| :---: | :---: |
|<a name="4096-randwrite"></a>![4.0KK  Random Write](plots.250910_092542/4096_randwrite.png)|<a name="8192-randwrite"></a>![8.0KK  Random Write](plots.250910_092542/8192_randwrite.png)|
|<a name="16384-randwrite"></a>![16.0KK  Random Write](plots.250910_092542/16384_randwrite.png)|<a name="32768-randwrite"></a>![32.0KK  Random Write](plots.250910_092542/32768_randwrite.png)|
|<a name="65536-randwrite"></a>![64.0KK  Random Write](plots.250910_092542/65536_randwrite.png)|<a name="262144-randwrite"></a>![256.0KK  Random Write](plots.250910_092542/262144_randwrite.png)|
|<a name="524288-randwrite"></a>![512.0KK  Random Write](plots.250910_092542/524288_randwrite.png)|<a name="1048576-randwrite"></a>![1024.0KK  Random Write](plots.250910_092542/1048576_randwrite.png)|

## Random Read/Write

|||
| :---: | :---: |
|<a name="4096-70-30-randrw"></a>![4.0KK 70/30  Random Read/Write](plots.250910_092542/4096_70_30_randrw.png)|<a name="16384-70-30-randrw"></a>![16.0KK 70/30  Random Read/Write](plots.250910_092542/16384_70_30_randrw.png)|
|<a name="65536-70-30-randrw"></a>![64.0KK 70/30  Random Read/Write](plots.250910_092542/65536_70_30_randrw.png)|<a name="65536-30-70-randrw"></a>![64.0KK 30/70  Random Read/Write](plots.250910_092542/65536_30_70_randrw.png)|

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