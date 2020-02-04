# Process And Invoice

Add a "Process" button to the order tab in your backoffice. Pressing it will 
print the invoices for all orders with the status 'paid' and put them in the
status 'processing' instead.

## Installation

### Manually

* Copy the module into ```<thelia_root>/local/modules/``` directory and be sure that the name of the module is ProcessAndInvoice.
* Activate it in your thelia administration panel

### Composer

Add it in your main thelia composer.json file

```
composer require thelia/process-and-invoice-module:~1.0
```
