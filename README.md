# TheMealDB (themealdb)
TheMealDB is a comprehensive online platform offering a vast collection of recipes from around the world with a free API. The API and site will always remain free at point of access.

**URL:** [Visit TheMealDB](https://www.themealdb.com/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Recipes, Meals, Food, Cooking

## Timestamps

- **Created:** 2024-11-14
- **Modified:** 2026-05-03

## APIs

### TheMealDB API
Free Recipe API providing access to a crowd-sourced database of meals from around the world. Search by name, category, area/region, or ingredient. Look up full recipes with step-by-step instructions, ingredients, measurements, YouTube videos, and images. The API and site will always remain free at point of access.

**Human URL:** [https://www.themealdb.com/api.php](https://www.themealdb.com/api.php)

#### Tags:

 - Recipes, Meals, Food, Cooking, Nutrition

#### Properties

- [Documentation](https://www.themealdb.com/api.php)
- [OpenAPI](openapi/themealdb-openapi.yml)
- [JSONSchema - Meal Schema](json-schema/themealdb-meal-schema.json)
- [JSONStructure - Meal Structure](json-structure/themealdb-meal-structure.json)
- [JSON-LD - TheMealDB JSON-LD Context](json-ld/themealdb-context.jsonld)

## Common Properties

- [Website](https://www.themealdb.com/)
- [Documentation](https://www.themealdb.com/api.php)
- [Sign Up](https://www.themealdb.com/)
- [SpectralRules](rules/themealdb-spectral-rules.yml)
- [Vocabulary](vocabulary/themealdb-vocabulary.yml)
- [NaftikoCapability - Meal Recipe Discovery](capabilities/meal-recipe-discovery.yaml)

## Features

| Name | Description |
|------|-------------|
| Meal Search | Search meals by name or browse alphabetically by first letter |
| Category Browse | Browse by category (Beef, Chicken, Seafood, Dessert, Pasta, etc.) |
| Regional Cuisine | Filter by area/region (Italian, Japanese, Mexican, Indian, etc.) |
| Ingredient Filtering | Find meals that use a specific ingredient |
| Random Meal | Retrieve a random meal for cooking inspiration |
| Full Recipe Details | Complete recipes with up to 20 ingredients, measurements, and instructions |
| YouTube Integration | Video cooking tutorials linked in recipe data |
| Images | Meal and ingredient images available in multiple sizes |
| Category Details | Full category listing with thumbnails and descriptions |

## Use Cases

| Name | Description |
|------|-------------|
| Recipe App Development | Build meal recipe apps and cooking websites |
| Meal Planning | Plan weekly meals by category, region, or available ingredients |
| AI Cooking Assistant | Power AI agents that suggest meals and cooking ideas |
| Dietary Filtering | Find meals filtered by ingredients, cuisine, or category |

## Integrations

| Name | Description |
|------|-------------|
| TheCocktailDB | Sister site providing cocktail recipes from the same provider |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [TheMealDB API OpenAPI](openapi/themealdb-openapi.yml)

### JSON Schema

- [themealdb-meal-schema.json](json-schema/themealdb-meal-schema.json)
- [themealdb-meals-response-schema.json](json-schema/themealdb-meals-response-schema.json)
- [themealdb-category-schema.json](json-schema/themealdb-category-schema.json)
- [themealdb-categories-response-schema.json](json-schema/themealdb-categories-response-schema.json)
- [themealdb-filter-response-schema.json](json-schema/themealdb-filter-response-schema.json)
- [themealdb-list-response-schema.json](json-schema/themealdb-list-response-schema.json)

### JSON Structure

- [themealdb-meal-structure.json](json-structure/themealdb-meal-structure.json)
- *(and 5 more)*

### JSON-LD

- [TheMealDB JSON-LD Context](json-ld/themealdb-context.jsonld)

### Examples

6 example JSON payloads for all schema types.

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [TheMealDB](capabilities/shared/themealdb.yaml) — 6 operations for meal recipe access

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Meal Recipe Discovery](capabilities/meal-recipe-discovery.yaml) | TheMealDB | 10 | Home Cook, Meal Planner, AI Agent |

## Vocabulary

- [TheMealDB Vocabulary](vocabulary/themealdb-vocabulary.yml) — Unified taxonomy mapping 4 resources, 5 actions, 1 workflow, and 3 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [TheMealDB Spectral Rules](rules/themealdb-spectral-rules.yml) — 18 rules across 7 categories enforcing TheMealDB API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
