# cv32e40x-litex
draft for cv32e40x integration for LiteX SoC builder
### Steps to test with Litex:
- copy core migen wrapper to litex cpu folder:

``` 
cp -rf cv32e40x litex/litex/soc/cores/cpu
```
- Install cpu pythondata:
```
pip install -e pythondata-cpu-cv32e40x
```