```
organisation.json
```

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






```
organisation.json
```

A schema to describe an organisation

| Abstract            | Extensible | Status       | Identifiable | Custom Properties | Additional Properties | Defined In                             |
| ------------------- | ---------- | ------------ | ------------ | ----------------- | --------------------- | -------------------------------------- |
| Can be instantiated | No         | Experimental | No           | Forbidden         | Permitted             | [organisation.json](https://github.com/ejp-rd-vp/ejprd-vp_metadata-schemas_implementation/blob/main/json_schema/organisation.json) |

## Schema Hierarchy

- Organisation `organisation.json`
    - [Location](location.md) `location.json`

# Organisation Properties

| Property                    | Type     | Required     | Nullable | Defined by                                 |
| --------------------------- | -------- | ------------ | -------- | ------------------------------------------ |
| [@id](#id)                  | `string` | Optional     | No       | Organisation (this schema)                 |
| [name](#name)               | `string` | **Required** | No       | Organisation (this schema)                 |
| [description](#description) | `string` | Optional     | No       | Organisation (this schema)                 |
| [facility](#facility)       | `string` | Optional     | No       | Organisation (this schema)                 |
| [department](#department)   | `string` | Optional     | No       | Organisation (this schema)                 |
| [contactPerson](#contactPerson)       | Person | Optional     | No       | Organisation (this schema)                 |
| [homepage](#homepage)       | `string` | Required     | No       | Organisation (this schema)                 |
| [location](#location)       | Location | Optional     | No       | Organisation (this schema)                 |
| `*`                         | any      | Additional   | Yes      | this schema _allows_ additional properties |

## @id

a primary identifier for the organisation

`@id`

- is optional
- type: `string`
- defined in this schema
- example:

### @id Type

`string`

## name

a name or short description for the organisation

`name`

- is **required**
- type: `string`
- defined in this schema
- example: Orphanet

### name Type

`string`



## description

A description for the organiation

`description`

- is optional
- type: `string`
- defined in this schema
- example: Orphanet is a unique resource, gathering and improving knowledge on rare diseases

### description Type

`string`


## facility

Services and space and equipment provided for a particular purpose; a building or place that provides a particular service or is used for a particular industry.

`facility`

- is optional
- type: `string`
- defined in this schema
- example: Orphanet Building

### description Type

`string`


## department

A unit with a specific responsibility that is a part of a larger organization with a specific responsibility.

`department`

- is optional
- type: `string`
- defined in this schema
- example: Rare Disease Unit

### description Type

`string`


## contactPerson

A person who has the role of being a contact person for a certain thing.

`ContactPerson`

- is optional
- type: `Person`
- defined in this schema
- example: John Smith

### description Type

- [Person](person.md) – `person.json`


## homepage

The primary URL for the homepage of the organisation

`homepage`

- is optional
- type: `string`
- defined in this schema
- example: https://www.orpha.net/consor/cgi-bin/index.php

### homepage Type

`string`

## location

Information about the location associated with the organisation

`location`

- is optional
- type: Location
- defined in this schema
- example:

### location Type

- [Location](location.md) – `location.json`