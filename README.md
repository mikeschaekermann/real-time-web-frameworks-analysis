# Pros/Cons analysis of frameworks for real-time, collaborative web apps

For now, only Meteor and Derby will be compared. As other frameworks emerge, they will be analyzed and compared to the existing frameworks.

As of *December 2013*.

## Conflict Resolution

**Meteor**: none (except for text-based documents, using the ShareJS smart package)

**Derby**: yes, supports fine-grained conflict resolution on arbitrary JSON objects

## Deployment

**Meteor**: `meteor deploy` command to deploy app directly into the Meteor cloud; a more flexible deployment process called Galaxy is planned for v1.0

**Derby**: simple deployment to Heroku

## Support for multiple programming languages

**Meteor**: yes, supports an arbitrary number of different languages per project (one smart-packaged compiler each)

**Derby**: no, either Javascript or Coffeescript

## Scalability

**Meteor**: no, is on the roadmap for v1.0

**Derby**: yes, through livedb

## Support for multiple single-page apps

**Meteor**: no, all resources are packaged per project

**Derby**: yes, supports an arbitrary number of single-page apps per project, which can share code/styles/templates amongst each other

## Fine-grained template updates

**Meteor**: no, the entire template is updated on data change

**Derby**: yes, updates may only affect tags or attributes

## Extensibility

**Meteor**: yes, active development of smart packages, managed by Meteorite (package ecosystem)

**Derby**: yes, support for NPM-based component libraries, but not many packages are there yet

## Community

**Meteor**: very active

**Derby**: less active

## Documentation

**Meteor**: very good + many community resources (such as the e-book "Discover Meteor")

**Derby**: very good

## Future Stability

**Meteor**: high due to major 11M USD investment in 2013 

**Derby**: unknown

## Built-in User Management

**Meteor**: yes

**Derby**: no

## Access to parent scope of data context within template sections

**Meteor**: no

**Derby**: yes
