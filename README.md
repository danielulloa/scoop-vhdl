# scoop-vhdl

This bucket is for FPGA development using VHDL with open-source software such as [ghdl](http://ghdl.free.fr/).

To make it easier to install apps from this bucket, run:

````
scoop bucket add vhdl 'https://github.com/danielulloa/scoop-vhdl.git'
````

## How this bucket was made

Following the documentation [Creating your own bucket](https://scoop.netlify.app/concepts/#creating-your-own-bucket) and [App manifests](https://github.com/lukesampson/scoop/wiki/App-Manifests).

Hash were computed using:

````
certutil -hashfile ./filename SHA256
````

While testing I followed this [steps](https://github.com/lukesampson/scoop/issues/1749).

### ghdl

The pre-built packages are [here](https://ghdl.readthedocs.io/en/latest/getting/Releases.html#downloading-pre-built-packages).

