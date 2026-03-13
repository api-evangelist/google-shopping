# Google Content API for Shopping

The Content API for Shopping allows apps to interact directly with the Google Merchant Center platform, enabling management of product listings, account information, data feeds, inventory, orders, and promotions. It provides programmatic access to create, update, and delete products, manage shipping and tax settings, handle order workflows, and access reporting data for Google Shopping.

## Artifacts

- **APIs.yml** - Machine-readable API metadata following the APIs.json specification.
- **OpenAPI** (`openapi/openapi.yml`) - OpenAPI 3.1.0 specification describing the Content API for Shopping endpoints, parameters, and response schemas.
- **JSON Schema** (`json-schema/google-shopping.json`) - JSON Schema (draft 2020-12) defining product and related objects.
- **JSON-LD** (`json-ld/google-shopping.jsonld`) - JSON-LD context mapping Shopping API terms to schema.org vocabularies.

## Key Endpoints

| Method | Path | Description |
|--------|------|-------------|
| GET | `/{merchantId}/products` | List products |
| POST | `/{merchantId}/products` | Insert a product |
| GET | `/{merchantId}/products/{productId}` | Get a product |
| DELETE | `/{merchantId}/products/{productId}` | Delete a product |
| GET | `/{merchantId}/accounts` | List accounts |
| GET | `/{merchantId}/orders` | List orders |
| GET | `/{merchantId}/datafeeds` | List data feeds |

## Resources

- [API Documentation](https://developers.google.com/shopping-content)
- [Getting Started](https://developers.google.com/shopping-content/guides/quickstart)
- [API Reference](https://developers.google.com/shopping-content/reference/rest/v2.1)

## Maintainer

Kin Lane - kin@apievangelist.com
