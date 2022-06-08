# cbcsv

Generates a `csv` file from `cargo bench` output.

## Usage

Run cargo bench using `--format=json`, as shown below:

```
cargo bench -- --format=json -Z unstable-options >> json_output.bench
```

Then, execute `cbcsv`:

```
./cbcsv json_output.bench output.csv
```
