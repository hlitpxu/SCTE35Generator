# Scte35 Generator
This project is a tool for generating SCTE35 messages.
* Public GUI can be accessed at [Scte35 Generator](https://hlitpxu.github.io/scte35_generator/)
* If you want to use the esam oob sender feature, you need to deploy the service on your local server

## SCTE35 support
Applicable to ANSI/SCTE 35 2023r1 specification
* downloaded from https://account.scte.org/standards/library/catalog/
### Splice command type
* Splice Insert
* Time Signal
### Descriptor type
* Segmentation descriptor

## ESAM OOB support
### Support basic ESAM OOB request with SCTE35 binary data

## Developer note
### Project setup
```
npm run setup
```

#### Compiles and hot-reloads for development (frontend)
```
npm run vue
```

#### Deploy locally (frontend + backend)
```
npm run deploy
```
