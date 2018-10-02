# MESSENGER mission local data dictionary

The MESSENGER mission dictionary contains classes that describe aspects of the MESSENGER mission and related instruments.

## Versions (source)

- [1.0.0.0](src/1.0.0.0)
- [1.0.1.0](src/1.0.1.0)

## Builds

A Local Data Dictionary (LDD) is built for each version of the [PDS4 Information Model](https://pds.nasa.gov/pds4/doc/im/). 
The build process insures compatiblity of the LDD with the core information model.

This LDD has been built for the following versions of the PDS4 information model.

- [1.9.0.0](build/1.9.0.0)
   - [1.0.0.0](src/1.0.0.0)
     (Download: 
      [XMLSchema (XSD)](https://github.com/nasa-pds/ldd-template/raw/master/build/1.9.0.0/1.0.0.0/PDS4_MESS_1900_1000.xsd)
      | [Schematron (SCH)](https://github.com/nasa-pds/ldd-template/raw/master/build/1.9.0.0/1.0.0.0/PDS4_MESS_1900_1000.sch)
      )
   - [1.0.1.0](src/1.0.1.0)
     (Download: 
      [XMLSchema (XSD)](https://github.com/nasa-pds/ldd-template/raw/master/build/1.9.0.0/1.0.1.0/PDS4_MESS_1900_1010.xsd)
      | [Schematron (SCH)](https://github.com/nasa-pds/ldd-template/raw/master/build/1.9.0.0/1.0.1.0/PDS4_MESS_1900_1010.sch)
      )
	
## Notes

Each build is generating using the [lddtool](https://pds.nasa.gov/pds4/software/ldd/) specific to a version of the [PDS4 Information Model](https://pds.nasa.gov/pds4/doc/im/). The build command used is:

```
lddtool -lp ldd-file.xml
```

Documentation included in the source (src) directory is generated using the "pds-ldd-doc" tool in the [pds4-tools](https://github.com/nasa-pds/pds4-tools) package.

After a build the README.md files are updated (manually) to reflect the content of repository.

