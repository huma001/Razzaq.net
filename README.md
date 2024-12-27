# Razzaq.net
---
<br> Razzaq provides a suite of APIs to support property listing, search, and marketing for rental properties. It serves users, real estate agents, landlords, and developers. The platform supports advanced search, user authentication, listing management, and analytics.

Authentication
---
- API Key: Required for access to any endpoint.
- Endpoint: /api/auth/login
- Method: POST
- Parameters:
  1. username: string
  2. password: string
  3. sign in: string

Endpoints
---
1. **Get Property Listings**
- Endpoint: /api/listings
- Method: GET
- Parameters:
  1. location: string (optional)
  2. price_min: integer (optional)
  3. price_max: integer (optional)
  4. property_type: string (optional)
  5. page: integer (optional)

![image](https://github.com/user-attachments/assets/a819159f-8352-43c2-ae63-315d78a1594b)




