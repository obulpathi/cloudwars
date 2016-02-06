# MySQL Benchmark

* ./pkb.py --project=benchmark-1200 --benchmarks=sysbench_oltp --machine_type=n1-standard-1

-------------------------PerfKitBenchmarker Complete Results-------------------------
{'metadata': {'cloud': 'GCP',
              'data_disk_0_legacy_disk_type': 'standard',
              'data_disk_0_media': 'hdd',
              'data_disk_0_num_stripes': 1,
              'data_disk_0_replication': 'zone',
              'data_disk_0_size': 500,
              'data_disk_0_type': 'pd-standard',
              'image': 'ubuntu-14-04',
              'machine_type': 'n1-standard-1',
              'num_striped_disks': 1,
              'perfkitbenchmarker_version': 'v1.1.0-29-g7743442',
              'preemptible': False,
              'scratch_disk_size': 500,
              'scratch_disk_type': 'standard',
              'vm_count': 1,
              'zone': 'us-central1-a'},
 'metric': 'OLTP Transaction Rate',
 'official': False,
 'owner': 'obulpathi',
 'product_name': 'PerfKitBenchmarker',
 'run_uri': '28af0a30-9067-4de2-adf0-18947f9389ea',
 'sample_uri': '34a62fc7-2455-483c-b278-57d7df4d7743',
 'test': 'sysbench_oltp',
 'timestamp': 1454722371.894778,
 'unit': 'Transactions/sec',
 'value': 688.25}
{'metadata': {'cloud': 'GCP',
              'data_disk_0_legacy_disk_type': 'standard',
              'data_disk_0_media': 'hdd',
              'data_disk_0_num_stripes': 1,
              'data_disk_0_replication': 'zone',
              'data_disk_0_size': 500,
              'data_disk_0_type': 'pd-standard',
              'image': 'ubuntu-14-04',
              'machine_type': 'n1-standard-1',
              'num_striped_disks': 1,
              'perfkitbenchmarker_version': 'v1.1.0-29-g7743442',
              'preemptible': False,
              'scratch_disk_size': 500,
              'scratch_disk_type': 'standard',
              'vm_count': 1,
              'zone': 'us-central1-a'},
 'metric': 'End to End Runtime',
 'official': False,
 'owner': 'obulpathi',
 'product_name': 'PerfKitBenchmarker',
 'run_uri': '28af0a30-9067-4de2-adf0-18947f9389ea',
 'sample_uri': '7e90ad44-c0aa-448f-bf66-80c8c0880caf',
 'test': 'sysbench_oltp',
 'timestamp': 1454722480.097273,
 'unit': 'seconds',
 'value': 500.17469906806946}


-------------------------PerfKitBenchmarker Results Summary-------------------------
SYSBENCH_OLTP:
  OLTP Transaction Rate               688.250000 Transactions/sec              
  End to End Runtime                  500.174699 seconds                       

-------------------------
