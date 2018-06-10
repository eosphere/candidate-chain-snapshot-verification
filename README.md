10th June 2018 

Added verification of snapshot injection for EOS Mainet - post ABP resignation for chain_id":"aca376f206b8fc25a6ed44dbdc66547c36c6c33e3a119ffbeaef943642f0e906"

Using both
https://github.com/eosnewyork/eospy
https://github.com/EOSArgentina/firestarter/tree/master/validator

validation.txt.eosphere.eospy.chain_aca376f2.txt
validation.txt.eosphere.firestarter.chain_aca376f2.txt



--------------------------

# candidate-chain-snapshot-verification

EOS Snapshot verification results using https://github.com/eosnewyork/eospy on candidate chains:

579a649aae8f660aa1abbab262437596d1f388f709b0b94a9fd6bba479889ea5

and

0d6c11e66db1ea0668d630330aaee689aa6aa156a27d39419b64b5ad81c0a760

Running with the follwing parameters:

--snapshot ./eos-snapshot-files/final/1/snapshot.csv --snapshot-hash 6df61f12f96f89c907fac14a021d788c9e77098952a6c5494c7999d2e79d0a35 --currency-check "10000000000.0000 EOS" --check-accounts --num-threads 8

And Referecing snapshow.csv from https://raw.githubusercontent.com/eosphere/eos-snapshot-files/master/final/1/snapshot.csv


