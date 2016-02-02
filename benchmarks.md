# Cloud Wars: Google Cloud vs AWS

## Commands
* ./pkb.py --project=benchmark-1200 --benchmarks=iperf --machine_type=f1-micro

-------------------------PerfKitBenchmarker Results Summary-------------------------
IPERF:
  receiving_machine_type="f1-micro" receiving_zone="us-central1-a" runtime_in_seconds="60" sending_machine_type="f1-micro" sending_thread_count="1" sending_zone="us-central1-a"
  Throughput                          291.000000 Mbits/sec                      (ip_type="external")
  Throughput                          651.000000 Mbits/sec                      (ip_type="internal")
  Throughput                          251.000000 Mbits/sec                      (ip_type="external")
  Throughput                          575.000000 Mbits/sec                      (ip_type="internal")
  End to End Runtime                  596.510909 seconds                       
* ./pkb.py --project=benchmark-1200 --benchmarks=iperf --machine_type=g1-small

-------------------------PerfKitBenchmarker Results Summary-------------------------
IPERF:
  receiving_machine_type="g1-small" receiving_zone="us-central1-a" runtime_in_seconds="60" sending_machine_type="g1-small" sending_thread_count="1" sending_zone="us-central1-a"
  Throughput                          964.000000 Mbits/sec                      (ip_type="external")
  Throughput                          999.000000 Mbits/sec                      (ip_type="internal")
  Throughput                          755.000000 Mbits/sec                      (ip_type="external")
  Throughput                          999.000000 Mbits/sec                      (ip_type="internal")
  End to End Runtime                  556.756788 seconds                       

* ./pkb.py --project=benchmark-1200 --benchmarks=iperf --machine_type=n1-standard-1

-------------------------PerfKitBenchmarker Results Summary-------------------------
IPERF:
  receiving_machine_type="n1-standard-1" receiving_zone="us-central1-a" runtime_in_seconds="60" sending_machine_type="n1-standard-1" sending_thread_count="1" sending_zone="us-central1-a"
  Throughput                         1229.000000 Mbits/sec                      (ip_type="external")
  Throughput                         1985.000000 Mbits/sec                      (ip_type="internal")
  Throughput                          951.000000 Mbits/sec                      (ip_type="external")
  Throughput                         1991.000000 Mbits/sec                      (ip_type="internal")
  End to End Runtime                  553.011616 seconds                       

* ./pkb.py --project=benchmark-1200 --benchmarks=iperf --machine_type=n1-standard-2

-------------------------PerfKitBenchmarker Results Summary-------------------------
IPERF:
  receiving_machine_type="n1-standard-2" receiving_zone="us-central1-a" runtime_in_seconds="60" sending_machine_type="n1-standard-2" sending_thread_count="1" sending_zone="us-central1-a"
  Throughput                         1080.000000 Mbits/sec                      (ip_type="external")
  Throughput                         3979.000000 Mbits/sec                      (ip_type="internal")
  Throughput                         1344.000000 Mbits/sec                      (ip_type="external")
  Throughput                         3988.000000 Mbits/sec                      (ip_type="internal")
  End to End Runtime                  550.667636 seconds                       

* ./pkb.py --project=benchmark-1200 --benchmarks=iperf --machine_type=n1-standard-4

-------------------------PerfKitBenchmarker Results Summary-------------------------
IPERF:
  receiving_machine_type="n1-standard-4" receiving_zone="us-central1-a" runtime_in_seconds="60" sending_machine_type="n1-standard-4" sending_thread_count="1" sending_zone="us-central1-a"
  Throughput                          887.000000 Mbits/sec                      (ip_type="external")
  Throughput                         6606.000000 Mbits/sec                      (ip_type="internal")
  Throughput                          642.000000 Mbits/sec                      (ip_type="external")
  Throughput                         6618.000000 Mbits/sec                      (ip_type="internal")
  End to End Runtime                  550.629390 seconds                       

* ./pkb.py --project=benchmark-1200 --benchmarks=iperf --machine_type=n1-standard-8

-------------------------PerfKitBenchmarker Results Summary-------------------------
IPERF:
  receiving_machine_type="n1-standard-8" receiving_zone="us-central1-a" runtime_in_seconds="60" sending_machine_type="n1-standard-8" sending_thread_count="1" sending_zone="us-central1-a"
  Throughput                         1072.000000 Mbits/sec                      (ip_type="external")
  Throughput                         7038.000000 Mbits/sec                      (ip_type="internal")
  Throughput                         1212.000000 Mbits/sec                      (ip_type="external")
  Throughput                         6834.000000 Mbits/sec                      (ip_type="internal")
  End to End Runtime                  588.248736 seconds                       

* ./pkb.py --project=benchmark-1200 --benchmarks=iperf --machine_type=n1-standard-16

* ./pkb.py --project=benchmark-1200 --benchmarks=iperf --machine_type=n1-standard-32
