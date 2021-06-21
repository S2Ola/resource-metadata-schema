`dcat:Dataset` is a concept in DCAT2 which is a sub-class of
`dcat:Resource`.

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
`DataService: `
A collection of operations that provides access to one or more datasets or data processing functions.


`Sub-class of:` dcat:Resource

`Sub-class of:` dctype:Service

[DataService Diagram:](DataService.png)

| Abstract            | Extensible | Status       | Identifiable | Custom Properties | Additional Properties | Defined In                                               |
| ------------------- | ---------- | ------------ | ------------ | ----------------- | --------------------- | -------------------------------------------------------- |
| Can be instantiated | No         | Experimental | No           | Forbidden         | Permitted             | [DataService.json](https://github.com/ejp-rd-vp/ejprd-vp_metadata-schemas_implementation/blob/main/json_schema/dataService.json) |

# Rare disease resources Properties

| Property                      | Type         | Composition  | Required     | Nullable | Defined by                                 |
| ----------------------------- | ------------ | -------------| ------------ | -------- | ------------------------------------------ |
| [@id]                         | `string`     |              | **Required** | No       | Rare disease catalog (this schema)         |
| [@type]                       |'Object`|              |  **Required**            |          |                                            |
| [resources](#resources)           | `Object`     |              | **Required** | No       | Rare disease catalog (this schema)         |
| [endpointURL](#endpointURL)           | `string`     |              | **Required** | No       | Rare disease catalog (this schema)         |
| [endpointDescription](#endpointDescription)           | `String`     |              | **Required** | No       | Rare disease catalog (this schema)         |
| [servesDataset](#servesDataset)             | `Object`     |              |  **Required** | No       | Rare disease catalog (this schema)         |
| [type](#type)           | `String`  |              | **Required** | No       | Rare disease catalog (this schema)         |
| `*`                           | any          |              | Additional   | Yes      | this schema _allows_ additional properties |



# Resources

	Resource published or curated by agent or organisation.

`Resources`

- is **required**
- type: `object`
- defined in this schema
- example:

### Resources Type

`dcat:resources same as catalogedResources`



## EndpointURL

	The root location or primary endpoint of the service (a Web-resolvable IRI).

`endpointURL`

- is **required**
- type: `String`
- defined in this schema
- example:

### endpointURL type

`String`



## EndpointDescription

	A description of the services available via the end-points, including their operations, parameters etc.

`endpointDescription`

- is **required**
- type: `String`
- defined in this schema
- example:

### endpointDescription type

`String`




## servesDataset

	A collection of data that this data service can distribute.

`endpointDescription`

- is **required**
- type: `String`
- defined in this schema
- example:

### servesDataset type

`String`




## Type

	An item that is listed in the catalog with values from the ejp:serviceType

`type`

- is **required**
- type: `ejp:serviceType`
- defined in this schema
- example:

### Type

`String`