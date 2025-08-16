# alx-graphql-0x00

# ALX GraphQL Queries

This repository contains solutions to GraphQL query tasks from the **alx-graphql-0x00** project.  
The tasks demonstrate how to query characters and episodes from the [Rick and Morty GraphQL API](https://rickandmortyapi.com/graphql).

---

## 📌 Directory Structure

alx-graphql-0x00/
├── character/
│ ├── README.md
│ ├── character-id-1.graphql
│ ├── character-id-1-output.json
│ ├── character-id-2.graphql
│ ├── character-id-2-output.json
│ ├── character-id-3.graphql
│ ├── character-id-3-output.json
│ ├── character-id-4.graphql
│ ├── character-id-4-output.json
│ ├── characters-page-1.graphql
│ ├── characters-page-1-output.json
│ ├── characters-page-2.graphql
│ ├── characters-page-2-output.json
│ ├── characters-page-3.graphql
│ ├── characters-page-3-output.json
│ ├── characters-page-4.graphql
│ ├── characters-page-4-output.json
│
└── episode/
├── README.md
├── episode-id-1.graphql
├── episode-id-1-output.json
├── episode-id-2.graphql
├── episode-id-2-output.json
├── episode-id-3.graphql
├── episode-id-3-output.json
├── episode-id-4.graphql
├── episode-id-4-output.json


---

## 🧑‍🚀 Tasks

### 1. Get a Specific Character by ID
- **Objective:** Query a character using character(id: ID!).
- 
- **Fields:** id, name, status, species, type, gender.
- 
- **Files:**  
  - character-id-1.graphql + character-id-1-output.json
  - 
  - character-id-2.graphql + character-id-2-output.json
  - 
  - character-id-3.graphql + character-id-3-output.json
  - 
  - character-id-4.graphql + character-id-4-output.json  

**Example Query**
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

### 2. Get a Specific Episode by ID

- **Objective:** Query an episode using episode(id: ID!).
- 
- **Fields:** id, name, air_date, episode.
- 
- **Files:**

episode-id-1.graphql + episode-id-1-output.json

episode-id-2.graphql + episode-id-2-output.json

episode-id-3.graphql + episode-id-3-output.json

episode-id-4.graphql + episode-id-4-output.json

**Example Query**
query {
  episode(id: 1) {
    id
    name
    air_date
    episode
  }
}
**Example output**
{
  "data": {
    "episode": {
      "id": "1",
      "name": "Pilot",
      "air_date": "December 2, 2013",
      "episode": "S01E01"
    }
  }
}

