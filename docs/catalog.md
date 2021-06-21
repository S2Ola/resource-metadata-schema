`dcat:Dataset` is a concept in DCAT2 which is a sub-class of
`dcat:Resource`.

### Metadata model figure

<p align="center"> 
    <a href="../images/turtle/dataset.svg" target="_blank">
        <img src="../images/turtle/resource.svg"> 
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
    <a href="../images/shex/dataset.svg" target="_blank">
        <img src="../images/shex/resource.svg"> 
    </a>
</p>

***
##### ShEx

``` ShEx

```


`Catalog: `
A curated collection of metadata about resources (e.g., datasets in the context of a data catalog).


`Sub-class of:` dcat:Dataset

[Catalog Diagram:](Catalog.png)

| Abstract            | Extensible | Status       | Identifiable | Custom Properties | Additional Properties | Defined In                                               |
| ------------------- | ---------- | ------------ | ------------ | ----------------- | --------------------- | -------------------------------------------------------- |
| Can be instantiated | No         | Experimental | No           | Forbidden         | Permitted             | [catalog.json](https://github.com/ejp-rd-vp/ejprd-vp_metadata-schemas_implementation/blob/main/json_schema/catalog.json) |

# Rare disease resources Properties

| Property                      | Type         | Composition  | Required     | Nullable | Defined by                                 |
| ----------------------------- | ------------ | -------------| ------------ | -------- | ------------------------------------------ |
| [@id]                         | `string`     |              | **Required** | No       | Rare disease catalog (this schema)         |
| [@type]                       |'Object`|              |  **Required**            |          |                                            |
| [catalog](#catalog)           | `Object`     |              | **Required** | No       | Rare disease catalog (this schema)         |
| [dataset](#dataset)           | `Object`     |              | **Required** | No       | Rare disease catalog (this schema)         |
| [resources](#resources)             | `object`     |              |  **Required** | No       | Rare disease catalog (this schema)         |
| [hasPart](#hasPart)           | `string`   |              | **Required** | No       | Rare disease catalog (this schema)         |
| [homepage](#homepage)         | `string`     |              | **Required** | No       | Rare disease catalog (this schema)         |
| [record](#record)             | `string`     |              | **optional** | No       | Rare disease catalog (this schema)         |
| `*`                           | any          |              | Additional   | Yes      | this schema _allows_ additional properties |



## Catalog

	A catalog whose contents are of interest in the context of this catalog.

`catalog`

- is **required**
- type: ``dcat:catalog``
- defined in this schema
- example:

### catalog Type

``dcat:catalog``


## Dataset

	A collection of data that is listed in the catalog.

`dataset`

- is **required**
- type: `dcat:Dataset`
- defined in this schema
- example:

## dataset Type

`dcat:Dataset`



## hasPart

	An item that is listed in the catalog.

`hasPart`

- is **required**
- type: `dcat:resources`
- defined in this schema
- example:

### hasPart Type

`dcat:resources same as catalogedResources`



# Record

	An item that is listed in the catalog.

`record`

- is **required**
- type: `string`
- defined in this schema
- example:

### record Type

`string`


# resources

	Resource published or curated by agent or organisation.

`resources`

- is **required**
- type: `object`
- defined in this schema
- example:

### record Type

`object`



## Homepage

The primary URL for the homepage of the catalog (a public Web document usually available in HTML).

`homepage`

- is **required**
- type: `string`
- defined in this schema
- example: http://www.orpha.net

### homepage Type

`string`

