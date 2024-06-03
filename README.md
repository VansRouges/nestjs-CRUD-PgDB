
# Catoff Interview Test: NESTjs CRUD Operations for PostgreSQL

## Setup

1. Clone the repository.
2. Install dependencies:
   ```sh
   npm install
3. Clone the repository.
4. Install dependencies:
   ```sh
   npm run start:dev
## **API ENDPOINTS**
### Users
* Create User
   * POST /users
   * Body: { "name": "string", "email": "string" }
* Get All Users
   * GET /users
* Get User by ID
   * GET /users/:id
* Update User
   * PATCH /users/:id
   * Body: { "name": "string", "email": "string" }
* Delete User
   * DELETE /users/:id

### WalletAddress
* Create WalletAddress

   * POST /wallet-address
   * Body: { "address": "string", "userId": "number" }

* Get All WalletAddresses
   * GET /wallet-address

* Get WalletAddress by ID
  * GET /wallet-address/:id

* Update WalletAddress
  * PATCH /wallet-address/:id
  * Body: { "address": "string", "userId": "number" }

* Delete WalletAddress
  * DELETE /wallet-address/:id

This implementation should cover all the requirements of the task:
1. **Database Setup**: PostgreSQL with Users and WalletAddress tables.
2. **NESTjs Application**: Developed to handle CRUD operations.
3. **API Development**: Endpoints for CRUD operations.
4. **Testing**: Verified using Postman.
 
5. **Code Quality**: Clean, well-commented code.
6. **Submission**: Include code and `README.md` for documentation.

This guide should help you understand and implement the task effectively. If you have any further questions or need additional details, feel free to ask!
