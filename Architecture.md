# Architecture Overview

The GSB Matrimony Microservices project follows a microservices-based architecture to provide a scalable and modular platform for the GSB (Goud Saraswat Brahmin) community. Each microservice focuses on specific functionalities while promoting code reusability and maintainability.

## Microservices Components

1. **User Authentication and Profile Service:** Handles user registration, authentication, and profile management.

2. **Verification and Matchmaking Service:** Implements GSB community verification and matchmaking algorithms.

3. **Communication and Messaging Service:** Enables user communication and contact sharing.

4. **Priest Communication Service:** Facilitates communication between users and priests.

5. **Melameli Service:** Determines melameli (marriage suitability) based on astrological factors.

6. **Payment and Subscription Service:** Manages subscription plans and payment processing.

7. **Search and Recommendation Service:** Provides search options and personalized recommendations.

8. **Notifications Service:** Sends email and in-app notifications for updates.

9. **Image and File Storage Service:** Handles storage of user images and documents.

10. **API Gateway and Configuration Service:** Acts as an entry point and manages routing.

## Communication Patterns

Microservices communicate using both synchronous and asynchronous methods. Synchronous REST APIs are used for user interactions, while asynchronous messaging (RabbitMQ) is employed for events and notifications.

## Scalability and Deployment

The modular architecture allows individual microservices to scale independently, enhancing performance and resource utilization. Docker and Kubernetes are used for containerization and orchestration.

## Diagram

high-level architecture diagram here to illustrate the interaction between microservices, databases, and external services.

## Future Considerations

As the project evolves, additional microservices or enhancements may be added to further meet the needs of the GSB community.

For more detailed information on each microservice, its endpoints, and interactions, refer to the individual README files in the respective microservices' directories.
