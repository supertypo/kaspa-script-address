# kaspa-script-address
Rusty Kaspa foregin function bindings for script to address (and vice versa) conversion for Python.

```shell
>>> import kaspa_script_address
>>> kaspa_script_address.to_address("kaspa", "20e3a134d07b6719befe296576fdea05a14f555f3491b4c13229b7fc77d3aff5b7ac")
'kaspa:qr36zdxs0dn3n0h799jhdl02qks5742lxjgmfsfj9xmlca7n4l6mw0s0n48nx'
>>> kaspa_script_address.to_script("kaspa:qr36zdxs0dn3n0h799jhdl02qks5742lxjgmfsfj9xmlca7n4l6mw0s0n48nx")
'20e3a134d07b6719befe296576fdea05a14f555f3491b4c13229b7fc77d3aff5b7ac'
```
