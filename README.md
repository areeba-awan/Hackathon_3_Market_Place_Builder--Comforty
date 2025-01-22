
Comforty Marketplace Hackathon Progress Report
Hackathon 3: E-Commerce Marketplace Journey for Comforty (Furniture E-commerce Platform)
Eco-Friendly and Reliable Marketplace

Day 1 - Day 3: Laying the Foundation for Comforty Marketplace
The first three days were all about setting up the foundation for Comforty’s e-commerce journey. The focus was on understanding the business goals, target audience, and designing a simple, user-friendly marketplace for selling furniture products. Here's a summary:

Marketplace Choice:

The chosen marketplace is Comforty, which will sell eco-friendly and sustainable furniture products.
The platform will aim to provide a seamless shopping experience, with features like advanced product filtering, easy checkout, and real-time order tracking.
Primary Purpose:

To create a marketplace that ensures eco-friendliness, reliability, and ease of use for customers looking for sustainable furniture solutions.
Tech Stack:

Frontend: Next.js, Tailwind CSS
Backend: Sanity CMS for managing products, NextAuth.js for authentication.
Deployment: Vercel for hosting and GitHub for version control.
Features Planned:

User authentication (via Google and GitHub)
Dynamic product listing and filtering
Add-to-cart functionality
Real-time cart management and checkout process
Promotional banners for featured products
Day 4: Dynamic Frontend Components for Comforty Marketplace
On Day 4, the focus shifted to building dynamic frontend components to enhance user interaction with the platform. This includes adding features that users would directly interact with.

Key Features Implemented:
Search Bar:

A responsive, functional search bar that allows users to dynamically search products across categories and filter them based on attributes (price, category, etc.).
Dynamic Product Listing:

Products are fetched in real-time from Sanity CMS and dynamically displayed on the homepage. Each product has its own pricing, image, and quick “Add to Cart” option.
Authentication Integration:

Integrated NextAuth.js for user authentication, allowing sign-in via Google or GitHub.
Promotional Banner:

A dynamic banner to display promotional offers, discounts, or featured products directly from Sanity CMS.
Cart Management:

Users can manage their cart, adjust quantities, and view their order total seamlessly.
Technologies Used:
Next.js 14.2.13 for the frontend
Sanity CMS for content management
NextAuth.js for OAuth-based authentication
Tailwind CSS for responsive UI design
TypeScript for type safety
Challenges & Solutions:
Dynamic Image Loading:

Issue: Some product images were not loading correctly due to URL resolution issues with Sanity’s asset pipeline.
Solution: Resolved this by properly configuring the URL paths and ensuring correct caching mechanisms.
Search Filtering:

Issue: Managing search state and applying filters dynamically proved complex.
Solution: Implemented robust state management using React hooks to handle product filtering based on user input.
What’s Next?:
For Day 5, I will focus on:
Advanced product filtering (by price, category, and ratings)
Integrating order management and payment gateway solutions
Day 5: Testing, Error Handling, and Backend Integration Refinement
Day 5 was dedicated to improving the backend integration, handling errors effectively, and refining the user experience by implementing robust error-handling mechanisms.

Key Tasks Completed:
Backend Integration:

Further integrated the backend services for handling orders, product details, and user authentication. Made sure that data is being fetched and displayed properly, with correct error handling.
Error Handling:

Implemented try-catch blocks and used custom error pages for displaying user-friendly messages in case of failed operations (e.g., failed login, unavailable products).
Incorporated validation for user input (e.g., checkout forms) to ensure data consistency.
Testing:

Unit and integration tests were added for core functionalities like:

Product fetch from Sanity CMS
Cart updates (add, remove, quantity change)
User authentication flow
Ensured that the platform functions smoothly under different user scenarios.

Challenges:
Handling user input validation across various components (cart management, user forms) and ensuring that error states were correctly displayed in the UI.
Next Steps:
For Day 6, I will focus on deploying the platform to Vercel and fine-tuning the environment settings for optimal performance.
Day 6: Deployment and Environment Settings
On Day 6, I focused on deploying the marketplace to Vercel, setting up the production environment, and making sure everything works seamlessly.

Key Tasks Completed:
Deployment:

Deployed the Comforty marketplace to Vercel using GitHub CI/CD integration.
Ensured that all environment variables, API keys, and third-party integrations (like Sanity and NextAuth) were correctly set up for production.
Environment Settings:

Configured production and staging environments in Vercel.
Set environment variables for keys like Sanity API tokens and NextAuth.js authentication secrets.
Production Testing:

Verified that everything, from product listings to cart management, is working as expected in the production environment.
Performance Optimization:

Ran performance tests on various components (image loading, product fetch time) and optimized the build by enabling Next.js Image optimization and caching strategies.
Challenges:
Ensuring the environment variables were correctly configured in Vercel for smooth backend communication.
Debugging minor issues related to the deployment pipeline.
Next Steps:
On Day 7, I plan to monitor the live deployment, gather feedback, and finalize all functionalities.
