
Performance Report for 07-09-2025-osd-down-clay
===============================================

Table of contents
=================

* [Summary of results for 07-09-2025-osd-down-clay](#summary-of-results-for-07-09-2025-osd-down-clay)
* [Response Curves](#response-curves)
	* [Sequential Read](#sequential-read)
	* [Sequential Write](#sequential-write)
	* [Random Read](#random-read)
	* [Random Write](#random-write)
	* [Random Read/Write](#random-readwrite)
* [Configuration yaml](#configuration-yaml)

# Summary of results for 07-09-2025-osd-down-clay
  
|Workload Name|Maximum Throughput|Latency (ms)|  
| :--- | ---: | ---: |  
|[4096_read](#4096-read)|62578 IOps|3.1|  
|[8192_read](#8192-read)|37177 IOps|5.2|  
|[16384_read](#16384-read)|21883 IOps|8.8|  
|[32768_read](#32768-read)|17754 IOps|10.8|  
|[65536_read](#65536-read)|1031 MB/s|16.3|  
|[262144_read](#262144-read)|1563 MB/s|10.7|  
|[524288_read](#524288-read)|1579 MB/s|10.6|  
|[1048576_read](#1048576-read)|1593 MB/s|13.2|  
|[4096_write](#4096-write)|17579 IOps|58.2|  
|[8192_write](#8192-write)|19847 IOps|64.5|  
|[16384_write](#16384-write)|11015 IOps|46.5|  
|[32768_write](#32768-write)|11999 IOps|64.0|  
|[65536_write](#65536-write)|250 MB/s|134.5|  
|[262144_write](#262144-write)|577 MB/s|116.2|  
|[524288_write](#524288-write)|308 MB/s|218.0|  
|[1048576_write](#1048576-write)|337 MB/s|499.0|  
|[4096_randread](#4096-randread)|64425 IOps|6.0|  
|[8192_randread](#8192-randread)|43638 IOps|5.9|  
|[16384_randread](#16384-randread)|30223 IOps|12.7|  
|[32768_randread](#32768-randread)|26199 IOps|9.8|  
|[65536_randread](#65536-randread)|1385 MB/s|6.0|  
|[262144_randread](#262144-randread)|1680 MB/s|10.0|  
|[524288_randread](#524288-randread)|1785 MB/s|9.4|  
|[1048576_randread](#1048576-randread)|1793 MB/s|16.4|  
|[4096_randwrite](#4096-randwrite)|3691 IOps|210.1|  
|[8192_randwrite](#8192-randwrite)|3218 IOps|239.0|  
|[16384_randwrite](#16384-randwrite)|5997 IOps|85.6|  
|[32768_randwrite](#32768-randwrite)|4551 IOps|112.4|  
|[65536_randwrite](#65536-randwrite)|235 MB/s|107.0|  
|[262144_randwrite](#262144-randwrite)|334 MB/s|201.0|  
|[524288_randwrite](#524288-randwrite)|298 MB/s|112.4|  
|[1048576_randwrite](#1048576-randwrite)|321 MB/s|156.3|  
|[4096_70_30_randrw](#4096-70-30-randrw)|8041 IOps|31.9|  
|[16384_70_30_randrw](#16384-70-30-randrw)|5814 IOps|44.0|  
|[65536_70_30_randrw](#65536-70-30-randrw)|209 MB/s|40.2|  
|[65536_30_70_randrw](#65536-30-70-randrw)|205 MB/s|81.8|
# Response Curves

## Sequential Read

|||
| :---: | :---: |
|<a name="4096-read"></a>![4.0KK  Sequential Read](plots.250907_212940/4096_read.png)|<a name="8192-read"></a>![8.0KK  Sequential Read](plots.250907_212940/8192_read.png)|
|<a name="16384-read"></a>![16.0KK  Sequential Read](plots.250907_212940/16384_read.png)|<a name="32768-read"></a>![32.0KK  Sequential Read](plots.250907_212940/32768_read.png)|
|<a name="65536-read"></a>![64.0KK  Sequential Read](plots.250907_212940/65536_read.png)|<a name="262144-read"></a>![256.0KK  Sequential Read](plots.250907_212940/262144_read.png)|
|<a name="524288-read"></a>![512.0KK  Sequential Read](plots.250907_212940/524288_read.png)|<a name="1048576-read"></a>![1024.0KK  Sequential Read](plots.250907_212940/1048576_read.png)|

## Sequential Write

|||
| :---: | :---: |
|<a name="4096-write"></a>![4.0KK  Sequential Write](plots.250907_212940/4096_write.png)|<a name="8192-write"></a>![8.0KK  Sequential Write](plots.250907_212940/8192_write.png)|
|<a name="16384-write"></a>![16.0KK  Sequential Write](plots.250907_212940/16384_write.png)|<a name="32768-write"></a>![32.0KK  Sequential Write](plots.250907_212940/32768_write.png)|
|<a name="65536-write"></a>![64.0KK  Sequential Write](plots.250907_212940/65536_write.png)|<a name="262144-write"></a>![256.0KK  Sequential Write](plots.250907_212940/262144_write.png)|
|<a name="524288-write"></a>![512.0KK  Sequential Write](plots.250907_212940/524288_write.png)|<a name="1048576-write"></a>![1024.0KK  Sequential Write](plots.250907_212940/1048576_write.png)|

## Random Read

|||
| :---: | :---: |
|<a name="4096-randread"></a>![4.0KK  Random Read](plots.250907_212940/4096_randread.png)|<a name="8192-randread"></a>![8.0KK  Random Read](plots.250907_212940/8192_randread.png)|
|<a name="16384-randread"></a>![16.0KK  Random Read](plots.250907_212940/16384_randread.png)|<a name="32768-randread"></a>![32.0KK  Random Read](plots.250907_212940/32768_randread.png)|
|<a name="65536-randread"></a>![64.0KK  Random Read](plots.250907_212940/65536_randread.png)|<a name="262144-randread"></a>![256.0KK  Random Read](plots.250907_212940/262144_randread.png)|
|<a name="524288-randread"></a>![512.0KK  Random Read](plots.250907_212940/524288_randread.png)|<a name="1048576-randread"></a>![1024.0KK  Random Read](plots.250907_212940/1048576_randread.png)|

## Random Write

|||
| :---: | :---: |
|<a name="4096-randwrite"></a>![4.0KK  Random Write](plots.250907_212940/4096_randwrite.png)|<a name="8192-randwrite"></a>![8.0KK  Random Write](plots.250907_212940/8192_randwrite.png)|
|<a name="16384-randwrite"></a>![16.0KK  Random Write](plots.250907_212940/16384_randwrite.png)|<a name="32768-randwrite"></a>![32.0KK  Random Write](plots.250907_212940/32768_randwrite.png)|
|<a name="65536-randwrite"></a>![64.0KK  Random Write](plots.250907_212940/65536_randwrite.png)|<a name="262144-randwrite"></a>![256.0KK  Random Write](plots.250907_212940/262144_randwrite.png)|
|<a name="524288-randwrite"></a>![512.0KK  Random Write](plots.250907_212940/524288_randwrite.png)|<a name="1048576-randwrite"></a>![1024.0KK  Random Write](plots.250907_212940/1048576_randwrite.png)|

## Random Read/Write

|||
| :---: | :---: |
|<a name="4096-70-30-randrw"></a>![4.0KK 70/30  Random Read/Write](plots.250907_212940/4096_70_30_randrw.png)|<a name="16384-70-30-randrw"></a>![16.0KK 70/30  Random Read/Write](plots.250907_212940/16384_70_30_randrw.png)|
|<a name="65536-70-30-randrw"></a>![64.0KK 70/30  Random Read/Write](plots.250907_212940/65536_70_30_randrw.png)|<a name="65536-30-70-randrw"></a>![64.0KK 30/70  Random Read/Write](plots.250907_212940/65536_30_70_randrw.png)|

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