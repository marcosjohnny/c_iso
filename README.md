# ciso

[![Tests](https://github.com/ioos/ciso/actions/workflows/tests.yml/badge.svg)](https://github.com/ioos/ciso/actions/workflows/tests.yml)
[![Wheels](https://github.com/ioos/ciso/actions/workflows/cibuildwheel.yml/badge.svg)](https://github.com/ioos/ciso/actions/workflows/cibuildwheel.yml)

Fast cythonized code for iso-slices of ocean models properties.

comandos:
pip install build abi3audit

abi3audit dist/\*.whl --summary --assume-minimum-abi3 3.11 --verbose --strict
