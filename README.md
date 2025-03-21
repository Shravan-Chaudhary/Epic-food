# Welcome to Epic Food 🍔🎮

Epic Food is your ultimate destination for delicious meals delivered right to your doorstep, perfect for those late-night gaming sessions! Built on a robust microservices architecture and powered by cutting-edge technologies, Epic Food redefines the food delivery experience with its seamless, efficient, and feature-rich platform.

##### Here is an overview of application architecture

![architecture](https://github.com/Shravan-Chaudhary/Epic-food/assets/77013800/b2486752-d7b8-442f-8993-b9e04329967e)

## Key Features 🚀

- **User-Friendly Frontends**: Developed with Next.js and React, our user and admin frontends provide intuitive interfaces for effortless navigation and interaction.

- **Microservices Architecture**: Leveraging Express, Typescript, and Docker, Epic Food is built on a scalable and resilient microservices architecture. The application comprises the following services:

  - **[ClientUI](https://github.com/Shravan-Chaudhary/client-ui)**: Next.js frontend for customers to browse menus, place orders, and track deliveries.
  - **[Deployment Config](https://github.com/Shravan-Chaudhary/epic-food-deployment)**: Kubernetes configuration files for container orchestration and deployment automation.
  - **[Auth Service](https://github.com/Shravan-Chaudhary/auth-service)**: Handles authentication and user management securely.
  - **[Inventory/Catalog Service](https://github.com/Shravan-Chaudhary/inventory-service)**: Manages restaurant menus, item availability, and pricing.
  - **[Order Service](https://github.com/Shravan-Chaudhary/order-service)**: Facilitates order processing, tracking, and fulfillment.
  - **[Websocket Service]()**: Powers real-time communication for order updates and notifications.
  - **[Notification Service]()**: Sends out alerts and notifications to users regarding their orders.

- **Data Management**: Epic Food utilizes a combination of MongoDB, PostgreSQL, and Redis for efficient data storage, retrieval, and caching.

- **Advanced Querying**: React Query enhances data fetching and management, ensuring lightning-fast performance and responsiveness.

- **Scalability and Resilience**: Deployed on AWS with Nginx for load balancing and reverse proxying, Epic Food is designed to scale seamlessly to meet growing demand while maintaining high availability. Docker containers enable easy deployment and management of microservices.

- **Real-Time Communication**: Integrated websockets enable real-time updates and communication between users, administrators, and delivery partners.

- **Event-Driven Architecture**: Kafka facilitates event-driven communication between services, ensuring asynchronous and decoupled interactions for improved reliability and scalability.

- **Security and Compliance**: Epic Food prioritizes security with robust authentication mechanisms, encrypted communication, and adherence to industry best practices.

Join Epic Food today and embark on a culinary journey like never before, perfectly complementing your late-night gaming adventures! 🎮🍕
