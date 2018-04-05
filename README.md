# oomph-setups
The repo contains OOMPH setup files for MINRES projects and tools to ease jump start working with these projects.

# How to use
## Download the eclipse installer

Download the Eclipse Installer from [here](https://www.eclipse.org/downloads/eclipse-packages/?show_instructions=TRUE) and install it
according to the instructions given there.

## Use the MINRES setups permanently with the eclipse installler

Open the eclipse_inst.ini file being part of the Eclipse Intaller. Add the following line at the end:

``` 
-Doomph.redirection.setups=index:/->https://raw.githubusercontent.com/Minres/oomph-setups/master/
```

## Use the MINRES setups temporarily with the eclipse installler

Run the eclipse installer with additional command line arguments:

```
eclipse-inst -vmargs '-Doomph.redirection.setups=index:/->https://raw.githubusercontent.com/Minres/oomph-setups/master/'
```

