# Evidence Folder - Task 3

## Screenshots from API Testing

| File Name | Description |
|-----------|-------------|
| `1-api-response.png` | Full list of comments (500 records) - No authentication required |
| `2-api-headers.png` | Headers showing 200 OK and rate limiting (1000 requests) |
| `3-id-enum-1.png` | Accessing comment with ID 1 by changing URL |
| `4-id-enum-2.png` | Accessing comment with ID 2 by changing URL |
| `5-id-enum-3.png` | Accessing comment with ID 3 by changing URL |

## What These Screenshots Prove
- **No authentication** - API returns data without any API key or token
- **ID enumeration** - Attackers can guess IDs and access all records
- **Rate limiting present** - Headers show 1000 requests allowed (good security practice)
- **Missing security headers** - CSP, HSTS, Referrer-Policy not present
