* ./pkb.py --project=benchmark-1200 --benchmarks=object_storage_service --machine_type=n1-standard-1

-------------------------PerfKitBenchmarker Results Summary-------------------------
OBJECT_STORAGE_SERVICE:
  boto_lib_version="Version: 2.39.0
" pkb_installed_crcmod="True" storage provider="GCP"
  upload throughput via cli Mbps p0.1       12.869832 Mbps                          
  upload throughput via cli Mbps p1       68.454976 Mbps                          
  upload throughput via cli Mbps p5      308.933349 Mbps                          
  upload throughput via cli Mbps p10      357.874814 Mbps                          
  upload throughput via cli Mbps p50      410.847678 Mbps                          
  upload throughput via cli Mbps p90      434.179973 Mbps                          
  upload throughput via cli Mbps p95      440.952896 Mbps                          
  upload throughput via cli Mbps p99      474.767405 Mbps                          
  upload throughput via cli Mbps p99.9      474.767405 Mbps                          
  upload throughput via cli Mbps average      396.156650 Mbps                          
  upload throughput via cli Mbps stddev       63.022638 Mbps                          
  download throughput via cli Mbps p0.1      106.950889 Mbps                          
  download throughput via cli Mbps p1      151.599923 Mbps                          
  download throughput via cli Mbps p5      190.945028 Mbps                          
  download throughput via cli Mbps p10      267.970875 Mbps                          
  download throughput via cli Mbps p50      328.741011 Mbps                          
  download throughput via cli Mbps p90      350.803806 Mbps                          
  download throughput via cli Mbps p95      358.232868 Mbps                          
  download throughput via cli Mbps p99      375.449582 Mbps                          
  download throughput via cli Mbps p99.9      375.449582 Mbps                          
  download throughput via cli Mbps average      314.621697 Mbps                          
  download throughput via cli Mbps stddev       47.719721 Mbps                          
  one byte upload latency p0.1          0.076405 seconds                       
  one byte upload latency p1            0.083628 seconds                       
  one byte upload latency p5            0.095522 seconds                       
  one byte upload latency p10           0.106063 seconds                       
  one byte upload latency p50           0.148077 seconds                       
  one byte upload latency p90           0.206722 seconds                       
  one byte upload latency p95           0.229236 seconds                       
  one byte upload latency p99           0.349488 seconds                       
  one byte upload latency p99.9         1.367447 seconds                       
  one byte upload latency average        0.157745 seconds                       
  one byte upload latency stddev        0.079001 seconds                       
  one byte download latency p0.1        0.035560 seconds                       
  one byte download latency p1          0.039072 seconds                       
  one byte download latency p5          0.044383 seconds                       
  one byte download latency p10         0.048626 seconds                       
  one byte download latency p50         0.079073 seconds                       
  one byte download latency p90         0.114808 seconds                       
  one byte download latency p95         0.129096 seconds                       
  one byte download latency p99         0.201279 seconds                       
  one byte download latency p99.9        0.278716 seconds                       
  one byte download latency average        0.082126 seconds                       
  one byte download latency stddev        0.029687 seconds                       
  regional one byte upload latency p0.1        0.056373 seconds                       
  regional one byte upload latency p1        0.061047 seconds                       
  regional one byte upload latency p5        0.068857 seconds                       
  regional one byte upload latency p10        0.077181 seconds                       
  regional one byte upload latency p50        0.108753 seconds                       
  regional one byte upload latency p90        0.155938 seconds                       
  regional one byte upload latency p95        0.172173 seconds                       
  regional one byte upload latency p99        0.215065 seconds                       
  regional one byte upload latency p99.9        0.322114 seconds                       
  regional one byte upload latency average        0.113546 seconds                       
  regional one byte upload latency stddev        0.033175 seconds                       
  regional one byte download latency p0.1        0.029314 seconds                       
  regional one byte download latency p1        0.031051 seconds                       
  regional one byte download latency p5        0.032985 seconds                       
  regional one byte download latency p10        0.034041 seconds                       
  regional one byte download latency p50        0.046385 seconds                       
  regional one byte download latency p90        0.071223 seconds                       
  regional one byte download latency p95        0.083404 seconds                       
  regional one byte download latency p99        0.114887 seconds                       
  regional one byte download latency p99.9        0.323687 seconds                       
  regional one byte download latency average        0.050853 seconds                       
  regional one byte download latency stddev        0.021874 seconds                       
  single stream upload throughput Mbps p0.1      328.065990 Mbps                          
  single stream upload throughput Mbps p1      334.906240 Mbps                          
  single stream upload throughput Mbps p5      366.735301 Mbps                          
  single stream upload throughput Mbps p10      398.852428 Mbps                          
  single stream upload throughput Mbps p50      460.384349 Mbps                          
  single stream upload throughput Mbps p90      524.025975 Mbps                          
  single stream upload throughput Mbps p95      540.210713 Mbps                          
  single stream upload throughput Mbps p99      600.728367 Mbps                          
  single stream upload throughput Mbps p99.9      600.728367 Mbps                          
  single stream upload throughput Mbps average      455.093141 Mbps                          
  single stream upload throughput Mbps stddev       50.208855 Mbps                          
  single stream download throughput Mbps p0.1      696.481781 Mbps                          
  single stream download throughput Mbps p1      718.819454 Mbps                          
  single stream download throughput Mbps p5      789.225607 Mbps                          
  single stream download throughput Mbps p10      821.999085 Mbps                          
  single stream download throughput Mbps p50      922.336784 Mbps                          
  single stream download throughput Mbps p90      990.090256 Mbps                          
  single stream download throughput Mbps p95     1002.014947 Mbps                          
  single stream download throughput Mbps p99     1047.976093 Mbps                          
  single stream download throughput Mbps p99.9     1047.976093 Mbps                          
  single stream download throughput Mbps average      912.377885 Mbps                          
  single stream download throughput Mbps stddev       67.747737 Mbps                          
  list-after-write consistency percentage       90.500000 na                            
  list-after-write inconsistency window p0.1        1.194994 seconds                       
  list-after-write inconsistency window p1        1.194994 seconds                       
  list-after-write inconsistency window p5        1.194994 seconds                       
  list-after-write inconsistency window p10        1.244483 seconds                       
  list-after-write inconsistency window p50        2.615079 seconds                       
  list-after-write inconsistency window p90      296.856615 seconds                       
  list-after-write inconsistency window p95      300.000000 seconds                       
  list-after-write inconsistency window p99      300.000000 seconds                       
  list-after-write inconsistency window p99.9      300.000000 seconds                       
  list-after-write inconsistency window average       50.151928 seconds                       
  list-after-write inconsistency window stddev      108.592273 seconds                       
  list-after-write latency p0.1         1.025030 seconds                       
  list-after-write latency p1           1.030542 seconds                       
  list-after-write latency p5           1.099650 seconds                       
  list-after-write latency p10          1.122960 seconds                       
  list-after-write latency p50          1.292284 seconds                       
  list-after-write latency p90          1.552240 seconds                       
  list-after-write latency p95          1.679138 seconds                       
  list-after-write latency p99          2.254604 seconds                       
  list-after-write latency p99.9        2.476469 seconds                       
  list-after-write latency average        1.330731 seconds                       
  list-after-write latency stddev        0.210309 seconds                       
  list-after-update consistency percentage       95.500000 na                            
  list-after-update inconsistency window p0.1        1.077935 seconds                       
  list-after-update inconsistency window p1        1.077935 seconds                       
  list-after-update inconsistency window p5        1.077935 seconds                       
  list-after-update inconsistency window p10        1.077935 seconds                       
  list-after-update inconsistency window p50        3.570464 seconds                       
  list-after-update inconsistency window p90       50.930525 seconds                       
  list-after-update inconsistency window p95       50.930525 seconds                       
  list-after-update inconsistency window p99       50.930525 seconds                       
  list-after-update inconsistency window p99.9       50.930525 seconds                       
  list-after-update inconsistency window average        9.870203 seconds                       
  list-after-update inconsistency window stddev       15.891139 seconds                       
  list-after-update latency p0.1        1.033149 seconds                       
  list-after-update latency p1          1.056134 seconds                       
  list-after-update latency p5          1.111628 seconds                       
  list-after-update latency p10         1.144941 seconds                       
  list-after-update latency p50         1.316132 seconds                       
  list-after-update latency p90         1.594127 seconds                       
  list-after-update latency p95         1.786231 seconds                       
  list-after-update latency p99         2.336518 seconds                       
  list-after-update latency p99.9        2.404753 seconds                       
  list-after-update latency average        1.355208 seconds                       
  list-after-update latency stddev        0.227739 seconds                       
  End to End Runtime                13058.226996 seconds                       

-------------------------
For all tests: cloud="GCP" data_disk_0_legacy_disk_type="standard" data_disk_0_media="hdd" data_disk_0_num_stripes="1" data_disk_0_replication="zone" data_disk_0_size="500" data_disk_0_type="pd-standard" image="ubuntu-14-04" machine_type="n1-standard-1" num_striped_disks="1" perfkitbenchmarker_version="v1.1.0-29-g7743442" preemptible="False" scratch_disk_size="500" scratch_disk_type="standard" vm_count="1" zone="us-central1-a"
2016-02-04 01:05:00,129 95878d16 MainThread INFO     Publishing 135 samples to /tmp/perfkitbenchmarker/run_95878d16/perfkitbenchmarker_results.json
2016-02-04 01:05:00,136 95878d16 MainThread INFO     Benchmark run statuses:
----------------------------------------------------------
Name                    UID                      Status   
----------------------------------------------------------
object_storage_service  object_storage_service0  SUCCEEDED
----------------------------------------------------------
Success rate: 100.00% (1/1)
2016-02-04 01:05:00,136 95878d16 MainThread INFO     Complete logs can be found at: /tmp/perfkitbenchmarker/run_95878d16/pkb.log
