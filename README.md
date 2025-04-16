# Python UART Driver for Sensirion SFX6XXX

This repository contains the Python driver to communicate with a Sensirion sensor of the SFX6XXX family over UART using the SHDLC protocol.

<img src="https://raw.githubusercontent.com/Sensirion/python-uart-sfx6xxx/master/images/product-image-sfx6xxx.png"
    width="300px" alt="SFX6XXX picture">

Click [here](https://sensirion.com/sfc6000) to learn more about the Sensirion SFX6XXX sensor family.



## Supported sensor types

- [SFC6000](https://sensirion.com/products/catalog/SFC6000/)
- [SFC6000D-5SLM](https://sensirion.com/products/catalog/SFC6000D-5slm/)
- [SFC6000D-50SLM](https://sensirion.com/products/catalog/SFC6000D-50slm/)
- [SFC6000D-20SLM](https://sensirion.com/products/catalog/SFC6000D-20slm/)
- [SFM6000](https://sensirion.com/products/catalog/SFM6000)
- [SFM6000D-20SLM](https://sensirion.com/products/catalog/SFM6000D-20slm)
- [SFM6000D-50SLM](https://sensirion.com/products/catalog/SFM6000D-50slm)
- [SFM6000D-5SLM](https://sensirion.com/products/catalog/SFM6000D-5slm)

The following instructions and examples use a *SFC6000*.



## Connect the sensor

You can connect your sensor over the provided USB cable.
For special setups check out the sensor pinout in the section below.

<details><summary>Sensor pinout</summary>
<p>
<img src="https://raw.githubusercontent.com/Sensirion/python-uart-sfx6xxx/master/images/product-pinout-sfx6xxx.png"
     width="300px" alt="sensor wiring picture">

| *Pin* | *Cable Color* | *Name* | *Description*  | *Comments* |
|-------|---------------|:------:|----------------|------------|
| 1 | brown | VDD | Supply Voltage | +24V
| 2 | white | D+ |  |
| 3 | black | D- |  |
| 4 | blue | GND | Ground |


</p>
</details>

## Documentation & Quickstart

See the [documentation page](https://sensirion.github.io/python-uart-sfx6xxx) for an API description and a
[quickstart](https://sensirion.github.io/python-uart-sfx6xxx/execute-measurements.html) example.


## Contributing

### Check coding style

The coding style can be checked with [`flake8`](http://flake8.pycqa.org/):

```bash
pip install -e .[test]  # Install requirements
flake8                  # Run style check
```

In addition, we check the formatting of files with
[`editorconfig-checker`](https://editorconfig-checker.github.io/):

```bash
pip install editorconfig-checker==2.0.3   # Install requirements
editorconfig-checker                      # Run check
```

## License

See [LICENSE](LICENSE).