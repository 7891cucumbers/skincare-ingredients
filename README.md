## About this project
Skin Care Ingredients is a simple app that provides information about the effects of using different skin care ingredients in combination - whether they are compatible or not and what issues to the skin they may cause if used together.

Built with:
* ![Go](https://img.shields.io/badge/go-%2300ADD8.svg?style=for-the-badge&logo=go&logoColor=white)

## Getting Started

### Ingredients
	GET /ingredient
	GET /ingredient/:id
	POST /ingredient
	PUT /ingredient/:id
	DELETE /ingredient/:id

### Skin Types
	GET /skinTypes
	GET /skinType/:id
	POST /skinType
	PUT /skinType/:id
	DELETE /skinType/:id

### Initial data:
* <a href="./ingredients.json">ingredients.json</a>
* <a href="./skinTypes.json">skinTypes.json</a>

## TODOs

- [ ] Add Combinations API
- [ ] Make slugs for URLs in UI
- [ ] Create UI