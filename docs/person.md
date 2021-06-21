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
person.json
```

A schema to describe an object that has certain capacities or attributes constituting personhood.

| Abstract            | Extensible | Status       | Identifiable | Custom Properties | Additional Properties | Defined In                             |
| ------------------- | ---------- | ------------ | ------------ | ----------------- | --------------------- | -------------------------------------- |
| Can be instantiated | No         | Experimental | No           | Forbidden         | Permitted             | [person.json](https://github.com/ejp-rd-vp/ejprd-vp_metadata-schemas_implementation/blob/main/json_schema/person.json) |

## Schema Hierarchy

- Person `person.json`


# Person Properties

| Property                    | Type     | Required     | Nullable | Defined by                                 |
| --------------------------- | -------- | ------------ | -------- | ------------------------------------------ |
| [@id](#id)                  | `string` | Optional     | No       | Person (this schema)                 |
| [surname](#surname) | `string` | Optional     | No       | Person (this schema)                 |
| [firstname](#homepage)       | `string` | Optional     | No       | Person (this schema)                 |
| [workInfoHomepage](#workInfoHomepage)       | Location | Optional     | No       | Person (this schema)                 |
| [emailAddress](#emailAddress)               | `string` | **Required** | No       | Person (this schema)                 |
| [contactPhoneNumber](#contactPhoneNumber)               | `string` | **Required** | No       | Person (this schema)                 |
| [officeDesignation](#officeDesignation)               | `string` | **Required** | No       | Person (this schema)                 |
| [publication](#publication)               | publication | **Optional** | No       | Person (this schema)                 |
| `*`                         | any      | Additional   | Yes      | this schema _allows_ additional properties |



## @id

a primary identifier for the person

`@id`

- is optional
- type: `string`
- defined in this schema
- example:

### @id Type

`string`




## surname

A surname (last name ) is a name added to a given name and is part of a personal name and is often the family name.

`surname`

- is optional
- type: `string`
- defined in this schema
- example: John

### description Type

`string`



## firstname

A first name is a name that denotes a specific individual between members of a group of individuals, whose members usually share the same surname.

`firstname`

- is optional
- type: `string`
- defined in this schema
- example: Doe

### description Type

`string`


## workInfoHomepage

The primary URL for the homepage of the Person

`workInfoHomepage`

- is optional
- type: `string`
- defined in this schema
- example: https://www.orpha.net/consor/cgi-bin/John_Doe.php

### workInfoHomepage Type

`string`

## emailAddress

an email address is an identifier to send mail to particular electronic mailbox.

`emailAddress`

- is optional
- type: 'string'
- defined in this schema
- example: johndoe@orphanet.org

### emailAddress Type
emailAddress
'string'


## contactPhoneNumber

Phone number of the contact person or organization.

`contactPhoneNumber`

- is **required**
- type: `string`
- defined in this schema
- example: +44(0)0123453245

### name Type

`string`


## officeDesignation

Phone number of the contact person or organization.

`officeDesignation`

- is **required**
- type: `string`
- defined in this schema
- example: Research Officer

### name Type

`string`



## publication

A publication is a document that has been made available by a publisher.

`publication`

- is **required**
- type: `publication`
- defined in this schema
- example:

### name Type

`publication`
