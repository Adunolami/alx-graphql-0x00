# alx-graphql-0x00
## GraphQL Queries to Fetch Character Information

### Query 1: Character with ID 1
Fetch details for the character with ID 1:
```graphql
query {
  character(id: 1) {
    id
    name
    status
    species
    type
    gender
  }
}
