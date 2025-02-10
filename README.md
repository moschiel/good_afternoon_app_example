# Good Afternoon App Example

This is a simple example application used as an external package for Buildroot. It prints **"Good Afternoon Mr Roger"** when executed.

## Usage in Buildroot

This package is integrated into [buildroot_external_example](https://github.com/moschiel/buildroot_external_example) and can be selected in `menuconfig`. Buildroot will automatically fetch, compile, and install it.

To manually compile:

```bash
git clone https://github.com/moschiel/good_afternoon_app_example.git
cd good_afternoon_app_example
make
./afternoon
```

Expected output:
```bash
Good Afternoon Mr Roger!
```
