# kokkos-benchmark-results

Repository for storing performance benchmark results.

## Generate performance graphs locally
```
git clone git@github.com:kokkos/benchmark_monitor.git
git clone git@github.com:kokkos/kokkos-benchmark-results.git
cd benchmark_monitor

python3 -m venv env
source env/bin/activate
pip install -r requirements.txt
python benchmark_monitor.py -d ../benchmark-results -o output
```
This will generate `index.html` and the rest of files in `output` diectory.
