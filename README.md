hostname Cookbook
=================
This cookbook sets hostname.

Requirements
------------
None

Attributes
----------
{
  "host": {
    "fqdn": ".."
  }
}

Usage
-----
#### hostname::default
Just include `hostname` in your node's `run_list`:

```json
{
  "name":"my_node",
  "run_list": [
    "recipe[hostname]"
  ]
}
```
adding fqdn as seen before.

Contributing
------------
Need help for testing following best practises, if you can help you are welcome!

License and Authors
-------------------
License: MIT

Authors:

Simone Dall'Angelo
