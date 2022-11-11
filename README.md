# aiida-ccc-plugin

Simple scheduler plugin for aiida allowing communications with Irene

## Installation

```shell
git clone git@github.com:BigDFT-group/aiida-ccc-plugin.git
pip install -e ./aiida_ccc_plugin
verdi daemon restart
reentry scan
```

the `ccc` scheduler should now be available for any `verdi computer setup`
