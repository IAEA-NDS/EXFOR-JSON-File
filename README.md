# EXFOR-JSON-File (J4)
The EXFOR JSON File (J4) is the [EXFOR Entry File](https://nds.iaea.org/nrdc/exfor-master/entry/) converted to JSON by the X4TOJ4 module of the [ForEXy](https://pypi.org/project/forexy/) package [1]. The J4 file can be converted to the EXFOR Entry File by the J4TOX4 module of the ForEXy package.

**Download**
- download the zipped file of the current version from the [EXFOR JSON File](https://nds.iaea.org/nrdc/exfor-master/j4/) website, or
- download the full repository using the terminal command:
```
git clone https://github.com/iaea-nrdcnetwork/exfor-json-file.git
```
**Directory structure**
```
    +--+--x4_makj4l.log   # update log file
       |
       +--schema
       |  +--j4_schema.json      # J4 schema file
       |  +--j4_schema_dict.json # JSON Dictionary schema
       |
       +--j4
          |
          +--1            # Area 1
          |  +--10001.json  # EXFOR 10001
          |  +--10002.json  # EXFOR 10002
          |  ...
          |
          +--2            # Area 2
          |  +--20001.json  # EXFOR 20001
          |  ...
          |
          ...
          +--9            # Area 9
          |  +--90001.json  # EXFOR 90001 (Dictionary)
          |
          +--a            # Area A
          ...
          +--v            # Area V

```
**Terms of Use**
- Cite Refs.[1] and [2] when you redistribute it in the original or another form, or use it in a publication,

The EXFOR JSON File is distributed under the terms of the CC BY 4.0 license.

**References**
1. N.Otuka, V.Devi, O.Iwamoto, [Appl.Radiat.Isot.225(2025)111903](https://doi.org/10.1016/j.apradiso.2025.111903) [[pdf](https://doi.org/10.48550/arXiv.2505.03758)]
2. N.Otuka et al., [Nucl. Data Sheets 120(2014)272](http://dx.doi.org/10.1016/j.nds.2014.07.065) [[pdf](https://doi.org/10.48550/arXiv.2002.07114)]
