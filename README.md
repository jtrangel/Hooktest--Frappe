# Hooktest

Testing a string modifier using hooks. This app is an initial attempt at customizing an app built through the Frappe - ERPnext framework.

## Initialization

Frappe supports MacOS/Ubuntu OS distributions, which means you'll need a virtual machine (VM) if you're on Windows.

Installation of Frappe: https://frappeframework.com/docs/v14/user/en/installation

## Running on Bash

To run the app, the first choice is to clone the repository to a folder named "hooktest "within the directory ~/frappe-bench/apps. Frappe automatically initializes the base directory after installation.


Afterwards, run:

`bench get-app hooktest`

The other choice is to install the app directly from this repository.

`
bench get-app https://github.com/jtrangel/Hooktest--Frappe
`

Last, we install the app to your frappe website.

``
bench --site <yoursite.com> install-app hooktest

bench start
``



#### License

MIT
