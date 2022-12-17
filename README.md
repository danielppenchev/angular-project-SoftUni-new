1. Create project's folder
Install @angular/cli
Create App as front-end

2. Add Header
Create Product model
Create data.ts
Add sample products
Add images to assets
Create Product service
Create Home component
Implement Search
Add method to Product service
Add search route
Show search result in Home component
Generate search component

3. Tags Bar
Create Tag model
Add sample tags to data.ts
Product service
Add get all tags method
Add get all products by tag method
Add tags route
Show tag result in Home component
Generate Tags component
Add to home component

4. Product Page
Add method to Product service
Generate Product Page component

5. Cart Page
Create CartItem Model
Create Cart Model
Generate Cart service
Add to Cart Button in Product Page
Generate Cart page component

6. Not Found! Page
Generate Component
Add To Pages
Home Page
Product Page
Cart Page

7. Connect To Backend
Create back-end folder
npm init
npm install typescript
Create tsconfig.json
Create .gitignore
Copy data.ts to backend/src
npm install express cors
Create server.ts
install @types
Add APIs
npm install nodemon ts-node --save-dev
Add urls.ts to frontend
Add HttpClient module
Update Product service

8. Login Page
Generate Component
Add to routes
Import Reactive Forms Module
Add Login API
Add jsonwebtoken
Generate User Service
Generate User model
Add User Subject
Add Login Method
Add User Urls
Generate IUserLogin interface
Add ngx-toastr
Import Module
Import BrowserAnimationsModule
Add styles in angular.json
Add to Header
Add Local Storage methods
Add Logout Method
Add to Header

9. Make Components For Login Page
Input Container
Input Validation
Text Input
Default Button

10. Connect Login API To MongoDB
Moving APIs into routers
Install
mongoose
dotenv
bcryptjs
express-async-handler

11. Connect to MongoDB
Use MongoDB instead of data.ts in APIs

12. Register User
Add Register API
Add Register service method
Add Register link
Add Register Component

13. Loading! Animation
Add Image
Add Component
Add Service
Add Interceptor

14. Checkout Page
Create Order Model
Create Checkout Page Component
Add To Router
Add User to User Service
Add Cart to Cart Service
Create Order Items List Component

15. Adding Map To The Checkout Page
Add Leaflet npm package
Add @types/leaflet
Add Css to angular.json
Add AddressLatLng to Order Model
Create Map component
Add to checkout page
Add TS
Change app-map selector to map
Add Html
Add CSS
Add Auth Guard

16. Save Order
Add Order Model
Add Order Status Enum
Add Auth Middleware
Add Order Router
Add create API
Add Order Urls to urls.ts
Add Order Service
Add create Method
Add Auth Interceptor

17. Payment Page
Generate Component
Add 'getOrderForCurrentUser' API
Add Order Service method
Connect Component to Service
Make the map component readonly

18. Adding Paypal
Generate Component
Add to payment page
Get Paypal test client Id
Add Paypal JS to index.html
Set up Paypal button
Add Pay API to order router