# 🌟 GraphQL Character Queries

Welcome! This guide helps you interact with character data using GraphQL queries.

---

## 🚀 Task 0: Fetch a Character by ID

Retrieve details for specific characters (IDs 1–4):

**Fields returned:**
- `id`
- `name`
- `status`
- `species`
- `type`
- `gender`

---

## 📋 Task 1: List Characters (Paginated)

Fetch paginated lists of characters (pages 1–4):

**Fields returned:**
- `id`
- `name`
- `status`
- `image`

---

## 📁 File Structure

| File Name                        | Description                  |
| -------------------------------- | ---------------------------- |
| `character-id-{n}.graphql`       | Query for character by ID    |
| `character-id-{n}-output.json`   | Output for character query   |
| `characters-page-{n}.graphql`    | Query for character list     |
| `characters-page-{n}-output.json`| Output for list query        |

---

## 🛠️ Usage

1. Open your preferred GraphQL client.
2. Load the desired `.graphql` file.
3. Execute the query against the GraphQL endpoint.
4. View results in the corresponding `.json` output file.

---

✨ Happy querying!
