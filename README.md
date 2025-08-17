# GraphQL Character Queries

## Task 0: Get Specific Character by ID

Easily fetch detailed information about a single character using their unique ID (1-4).  
Each query returns the following fields:

| Field   | Description           |
|---------|-----------------------|
| `id`    | Unique character ID   |
| `name`  | Character's name      |
| `status`| Alive, Dead, or Unknown |
| `species`| Character's species  |
| `type`  | Character's type      |
| `gender`| Character's gender    |

**Example Query:**
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
```

**Result:**  
A JSON object with the character's details.

---

Four queries to fetch individual character details using their IDs (1-4).
Each query retrieves:

- id
- name
- status
- species
- type
- gender

## Task 1: Get List of Characters

Four queries to fetch paginated lists of characters (pages 1-4).
Each query retrieves:

- id
- name
- status
- image

## File Structure

- `character-id-{n}.graphql`: Individual character queries
- `character-id-{n}-output.json`: Query results
- `characters-page-{n}.graphql`: Character list queries
- `characters-page-{n}-output.json`: Query results

## Task 2: Episode Queries

## Query Structure

Fetches episode details using ID, including:

- id
- name
- air_date
- episode

## Files

- episode-page-{n}.graphql: Episode queries
- characters-page-{n}-output.json: Query results

## Usage

Execute queries against the GraphQL endpoint using a GraphQL client.
