# plot_NX
Script for plotting Newton-X spectra.

## Usage
Add \*.dat spectrum files as arguments. The default unit is nm but can be changed to eV with ```-u eV```:
```
plot_NX cross-section.dat -u eV
```
Experimental data can be included with ```-e``` in a two column format of count and pulse:
```
509.8721672743961    0.8050750906266182
511.63324789501985    0.8344208527533228
512.8072001593686    0.8551355083721732
```

For more help try ```plot_NX -h```

