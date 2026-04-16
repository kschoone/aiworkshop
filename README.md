# AI Workshop - OpenEdge ABL Project

This project demonstrates modern OpenEdge ABL development patterns including:

- Business Entity architecture with `OpenEdge.BusinessLogic.BusinessEntity`
- Singleton Factory pattern for entity lifecycle management
- Dataset-based data transfer between UI and business layers
- Windsurf AI-assisted development workflows

## Project Structure

```
src/
  business/
    EntityFactory.cls       - Singleton factory for business entities
    CustomerEntity.cls      - Customer business entity
    CustomerDataset.i       - Customer dataset definition
    ItemEntity.cls          - Item business entity
    ItemDataset.i           - Item dataset definition
  CustomerWin.w             - Customer management UI
  ItemWin.w                 - Item management UI
doc/
  business-entity-pattern.md - Architecture pattern documentation
dump/
  sports2000.df             - Database schema definition
```

## Prerequisites

- OpenEdge 12.8+
- Sports2000 database

## Getting Started

1. Clone the repository
2. Create the Sports2000 database: `ant db`
3. Open the project in your OpenEdge IDE
