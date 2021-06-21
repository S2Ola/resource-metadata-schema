`dcat:distribution`

### Metadata model figure

<p align="center"> 
    <a href="../images/turtle/dataset.png" target="_blank">
        <img src="../images/turtle/resource.png"> 
    </a>
</p>


***

### Example rdf (turtle)

```ttl


```

***

### Validation artifacts

##### ShEx figure

<p align="center"> 
    <a href="../images/shex/dataset.png" target="_blank">
        <img src="../images/shex/resource.png"> 
    </a>
</p>

***
##### ShEx

``` ShEx

```

`Distribution: `
A collection of data, published or curated by a single agent, and available for access or download in one or more representations.





`[Distribution Diagram:]`(Distribution.png)


| Abstract            | Extensible | Status       | Identifiable | Custom Properties | Additional Properties | Defined In                                               |
| ------------------- | ---------- | ------------ | ------------ | ----------------- | --------------------- | -------------------------------------------------------- |
| Can be instantiated | No         | Experimental | No           | Forbidden         | Permitted             | [Distribution.json](https://github.com/ejp-rd-vp/ejprd-vp_metadata-schemas_implementation/blob/main/json_schema/distribution.json) |

# Distribution Properties

| Property                           | Type         | Required     | Nullable | Defined by                                 |
| ---------------------------------- | ------------ | ------------ | -------- | ------------------------------------------ |
| [@id]                         | `string`     |              | **Required** | No       | Rare disease catalog (this schema)         |
| [@type]                       |'dcat:Distribution`|              |  **Required**            |          |                                            |
| [title](#title)                | `string`     | **Required** | No       | Rare disease catalog (this schema)         |
| [download](#downloadURL)  | `string`     | **Optional** | Yes     | Rare disease catalog (this schema)         |
| [accessURL](#accessURL)      | `string`     | **Optional** | Yes       | Rare disease catalog (this schema)         |
| [conformsTo](#conformsTo)                | `string`     | **Required** | No       | Rare disease catalog (this schema)         |
| `*`                                |  any         | Additional   | Yes      | this schema _allows_ additional properties |





## title

	The geographical area covered by the dataset.

`spatial`

- is **required**
- type: `object`
- defined in this schema
- example:

### title Type

`string`




## download

	The URL of the downloadable file in a given format. E.g. CSV file or RDF file. The format is indicated by the distribution's dct:format and/or dcat:mediaType


`download`

- is **required**
- type: `string`
- defined in this schema
- example:

### download

`string`



## accessURL

	An available distribution of the dataset.

`accessURL`

- is **required**
- type: `string`
- defined in this schema
- example:

### accessURL Type

`string`



## conformsTo

	The URL of the downloadable file in a given format. E.g. CSV file or RDF file. The format is indicated by the distribution's dct:format and/or dcat:mediaType


`conformsTo`

- is **required**
- type: `string`
- defined in this schema
- example:

### conformsTo

`string`