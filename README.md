## Global Tax API

[Global Tax API](https://horisystems.com/global-tax-api/) calculates sales tax worldwide in seconds with a single integration. Get instant tax rates for US, Australia, Canada, EU, UK, Mexico, Africa, and Middle East countries through our RESTful API.

### Overview

[Global Tax API](https://horisystems.com/global-tax-api/) delivers tax calculation solutions to businesses operating globally. Our API supports VAT rates, sales tax calculations, tax validation, and automated tax returns to ensure compliance with local tax regulations worldwide.

### Features

* **Worldwide Tax Coverage**: Access tax rates for all major markets including US sales tax, EU VAT, UK VAT, Australian GST, Canadian sales tax, and tax rates for African, Asian, Middle Eastern and Oceania countries
* **Tax Validation**: Validate VAT numbers for EU and UK businesses, and ABN/ACN numbers for Australian businesses
* **Automated Tax Returns**: Generate XML files for UK MTD, Spanish SII, and Portuguese ECSL tax returns
* **Invoice OCR**: Extract data from invoices using optical character recognition technology
* **Address Validation**: Validate US postal addresses to ensure accurate shipping
* **Economic Nexus Detection**: Identify when your business establishes tax obligations in US states

### Authentication

[Global Tax API](https://horisystems.com/global-tax-api/) uses username and password authentication and returns an API key upon successful login. This API key is required for all subsequent API requests.

### API Versions

Current supported API versions:
- 2023-12-24
- 2023-06-19

Include `x-api-version` in your request headers using the YYYY-MM-DD format.

### API Primitives

Our API provides these core primitives:

* Calculate Taxes
* Type of Service (Categories)
* EU VAT Rates
* EU VAT Validation
* Invoice OCR
* Portuguese ECSL
* Spanish SII
* UK VAT Rates
* UK VAT Validation
* UK MTD Return
* USA Sales Tax
* USA Economic Nexus
* USA Address Validation
* African Countries Sales Tax Rates
* Asian Sales Tax
* Australian GST Rates
* Australian ABN and ACN
* Canadian Sales Tax Rates
* Central and South American Sales Tax
* Mexican Sales Tax Rates
* Middle Eastern Countries Sales Tax Rates
* Oceania Sales Tax

### Rate Limiting

Rate limits are measured in Transactions Per Second (TPS). Headers provide information about:
- `X-RateLimit-Limit`: Maximum requests per second/day
- `X-RateLimit-Remaining`: Requests remaining
- `X-Rate-Limit-Reset`: When current window ends
- `Retry-After`: Wait time before next request

Use the `/v2/rate_limit_checker` endpoint to check your remaining requests.

### Role-based Access Control

The API implements RBAC with two roles:
- **Users**: Access to specific endpoints
- **Admin**: Unrestricted access to all resources

### Response Codes

| Code | Description |
|------|-------------|
| 200 | Request processed successfully |
| 201 | Resource created successfully |
| 202 | Request accepted for processing |
| 204 | Request processed with no content to return |
| 401 | Invalid authentication credentials |
| 403 | Authentication failed |
| 404 | Resource not found |
| 405 | Invalid method for endpoint |
| 422 | Invalid JSON formatting or data |
| 429 | Rate limit exceeded |
| 5XX | Server error - try again or contact support |

### Pricing Plans

| Plan | Price (GBP) | Requests/month | Features |
|------|-------------|----------------|----------|
| Starter | £5.99 | 50 | Basic tax calculations |
| Scale | £25 | 2,500 | All tax features |
| Essential | £50 | 7,000 | All tax features |
| Premium | £500 | 80,000 | All tax features |
| Enterprise | Custom | Custom | Volume discounts and custom integrations |

> All [yearly plans](https://horisystems.com/global-tax-api/) include a 20% discount.

### Recent Updates

- 11/01/2025: Systems security patches
- 18/03/2024: Australian ABN/ACN validation endpoint released
- 16/03/2024: Invoice OCR endpoint released
- 10/03/2024: Email delivery for tax return XML files
- 08/03/2024: Spanish SII, Portuguese ECSL, and UK MTD return endpoints released

For detailed API documentation, visit our [API Documentation](https://globaltaxapi.horisystems.com/).

### Integration and Support

For enterprise integration or custom solutions, contact our sales team at [enterprise@horisystems.com](mailto:enterprise@horisystems.com). We provide 24-hour SLA email support at [tech@horisystems.com](mailto:tech@horisystems.com) for all customers, with priority support for enterprise customers. Sample integration code is available in [Python](https://gist.github.com/0xnu/529077809c6840d497c0047ad1ee8fae#file-global_sales_tax-py), [Golang](https://gist.github.com/0xnu/529077809c6840d497c0047ad1ee8fae#file-main-go), [TypeScript/JavaScript](https://gist.github.com/0xnu/529077809c6840d497c0047ad1ee8fae#file-globalsalestaxcalculator-ts), [C#/.NET](https://gist.github.com/0xnu/529077809c6840d497c0047ad1ee8fae#file-global_sales_tax-cs), [Java](https://gist.github.com/0xnu/529077809c6840d497c0047ad1ee8fae#file-global_sales_tax_calculator-java), and [PHP](https://gist.github.com/0xnu/529077809c6840d497c0047ad1ee8fae#file-global_sales_tax_calculator-php).

### License

This project is licensed under the [BSD 3-Clause License](LICENSE) - see the file for details.

### Copyright

(c) 2023 - 2025 [Hori Systems Limited](https://horisystems.com). All Rights Reserved.