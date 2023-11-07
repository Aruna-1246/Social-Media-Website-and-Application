**SOFTWARE REQUIREMENTS SPECIFICATION![ref1]**

**For**

**SOCIAL MEDIA WEBSITE AND APPLICATION**

**Prepared by :-**

**ARUNA B**

**DEVISRI S                    KATHIJA FYROSE FATHIMA B MADUMITHA R**

**Academic year : 2023-2024**

1. **Introduction![ref1]**
1. **Purpose**

The main objective of this document is to illustrate the requirements of the project Library Management system. The document gives the detailed description of the both functional and non-functional requirements proposed by the client. The purpose of this document is to specify the requirements for the development of a social media website, hereinafter referred to as "the system." The system aims to provide a platform for users to connect, share content, and engage with others online.

2. **Document Conventions**
- Entire document should be justified.
- Convention for Main title
  - Font face: Times New Roman
  - Font style: Bold
  - Font Size: 14
- Convention for Sub title
  - Font face: Times New Roman
  - Font style: Bold
  - Font Size: 12
- Convention for body
- Font face: Times New Roman
- Font Size: 12
3. **Scope of Development Project**

This document covers the functional and non-functional requirements of the social media website, including user profiles, posting features, messaging, security, and scalability. It is especially useful for the entertainment where modifications in the content can be done easily according to requirements.

The project can be easily implemented under various situations. We can add new features as and when we require, making reusability possible as there is flexibility in all the modules. The language used for developing the project is Java as it is quite advantageous than other languages in terms of performance, tools available, cross platform compatibility, libraries, cost (freely available), and development process.

4. **Definitions, Acronyms, and Abbreviations**

**Definition**

- **User:** An individual who registers and interacts with the social media website.
- **Profile:** A personal page created by a user containing information about themselves.
- **Post:** User-generated content that can include text, images, videos, and links.
- **Friend:** A mutual connection between two users who have accepted each other's friend requests.
- **Follower:** A user who subscribes to another user's posts without a mutual connection.![ref1]
- **Feed:** A personalized stream of posts and content that a user sees on their homepage.
- **Notification:** A message or alert informing users of specific events or interactions.
- **Hash tag:** A keyword or phrase preceded by a hash symbol (#) used to categorize and discover content.
- **DM (Direct Message):** A private message sent from one user to another.
- **API (Application Programming Interface):** A set of rules and protocols that allow different software applications to communicate with each other.
- **XSS (Cross-Site Scripting):** A security vulnerability where malicious scripts are injected into web pages viewed by other users.
- **CSRF (Cross-Site Request Forgery):** A security vulnerability where unauthorized commands are transmitted from a user that the web application trusts.
- **GDPR (General Data Protection Regulation):** A European Union regulation governing the protection of personal data and privacy.

**Acronyms and Abbreviations**

- **SRS:** Software Requirements Specification
- **HTTPS:** Hypertext Transfer Protocol Secure
- **API:** Application Programming Interface
- **UI:** User Interface
- **UX:** User Experience
- **SQL:** Structured Query Language
- **HTML:** Hypertext Markup Language
- **CSS:** Cascading Style Sheets
- **DNS:** Domain Name System
- **SMTP:** Simple Mail Transfer Protocol
- **HTTP:** Hypertext Transfer Protocol
- **TCP/IP:** Transmission Control Protocol/Internet Protocol
- **JSON:** JavaScript Object Notation
5. **References**

**Books:**

- "Software Requirements" by Karl E. Wiegers and Joy Beatty: This book provides a comprehensive guide on gathering, documenting, and managing software requirements.

**Online Documentation and Guides:![ref1]**

- IETF RFCs (Request for Comments): These documents often include technical standards and protocols relevant to web and social media applications.
- API Documentation: If you plan to integrate with social media platforms or third- party services, refer to their API documentation for technical details.
- Web Development Framework Documentation: Depending on the technologies you're using (e.g., Django, Ruby on Rails, Node.js), consult the official documentation for best practices and guidelines.
2. **Overall Descriptions**
1. **Product Perspective**

![](Aspose.Words.a0637858-4cf9-416d-b935-6fcb62415a1f.002.jpeg)

2. **Product Function![ref1]**

![](Aspose.Words.a0637858-4cf9-416d-b935-6fcb62415a1f.003.jpeg)

3. **Class Diagram**

![](Aspose.Words.a0637858-4cf9-416d-b935-6fcb62415a1f.004.png)

4. **User Classes and Characteristics![ref1]**

The system provides different types of services based on the type of users.

1. **Registered Use :** Individuals who have created accounts on the platform.
1. **Administrators** : Moderators and administrators responsible for monitoring and managing content and user accounts.
1. **Guest Users :** Visitors who can access limited features without registration.
5. **Assumptions and Dependencies Assumptions:**

The system assumes that users have access to a stable internet connection for real-time interactions.

1. **User Engagement:**
   1. **Assumption**: Users will actively engage with the platform by posting content, interacting with others, and returning regularly.
   1. **Implication:** The success of the platform relies on user participation and content generation.
1. **Scalability:**
   1. **Assumption:** The user base will grow over time.
   1. **Implication:** The system should be designed with scalability in mind to handle increasing traffic and data storage requirements.
1. **Content Moderation:**
   1. **Assumption:** Some user-generated content may violate community guidelines or be inappropriate.
   1. **Implication**: Implementing effective content moderation tools and processes is necessary to maintain a safe and welcoming environment.
1. **Privacy and Data Security:**
   1. **Assumption:** Users expect their personal information to be kept secure.
   1. **Implication:** Robust security measures, including encryption and access controls, must be in place to protect user data.
1. **Third-Party Integrations:**
   1. **Assumption:** Integrations with external services (e.g., social media APIs, payment gateways) will be reliable and available.
   1. **Implication:** Reliability of third-party services may impact the functionality of the social media website.
1. **User Behavior:**
- **Assumption:** Users will adhere to platform policies and guidelines.
- **Implication:** The platform should have mechanisms to handle user violations

and enforce policies.

7. **Technical Stack:![ref1]**
- **Assumption:** The chosen technology stack (e.g., programming languages, databases, web servers) is suitable for the project's needs.
- **Implication:** Changes in the technology stack may require adjustments to the project plan and development timeline.

**Dependencies:**

Dependencies include external libraries, APIs, and third-party services for features like geo location, content sharing, and authentication.

1. **API Dependencies:**
   1. **Dependency:** Integration with external APIs (e.g., social media sharing, authentication) is required.
   1. **Implication:** Development and testing timelines depend on the availability and stability of these APIs.
1. **Infrastructure Dependencies:**
   1. **Dependency:** Availability of hosting infrastructure, server resources, and databases.
   1. **Implication:** Any delays or issues with infrastructure provisioning can impact the project schedule.
1. **Third-Party Services:**
   1. **Dependency:** Relying on third-party services for features like email notifications or analytics.
   1. **Implication:** The project timeline is contingent on the reliability and availability of these services.
1. **Regulatory Compliance**
   1. **Dependency:** Compliance with data privacy regulations (e.g., GDPR, CCPA) is mandatory.
   1. **Implication:** Compliance requirements may dictate specific development practices and impact data handling.
1. **User Feedback:**
   1. **Dependency:** Gathering user feedback and conducting usability testing.
   1. **Implication:** Incorporating user feedback may lead to iterative changes in the development process.
6. **Requirement**

**Software Configuration:-** This software package is developed using java as front end which is supported by NetBeans system. Microsoft SQL Server as the back end to store the database.

**Operating System:** Windows NT, windows 98, Windows XP Language: Java Runtime Environment, Net beans 7.0.1 (front end)

**Database:** MS SQL Server (back end)![ref1]

**Hardware Configuration:-**

- Processor: Pentium(R)Dual-core
- CPU Hard Disk: 40GB RAM: 256 MB or more
7. **Data Requirement**
1. **User Profiles:**
- User Information
- Profile Pictures
- User Preferences
2. **Content Data:**
- Posts
- Comments
- Likes and Reactions
- Shares and Re-tweets
- Hash tags and Tags
3. **Connections and Relationships:**
- Friends/Followers
- Friendship Status
- Groups or Communities
4. **Notifications:**
- Notifications Data
- Notification Settings
5. **Messaging and Chat:**
- Messages
- Message Status
6. **Reporting and Moderation:**
- Reported Content
- Moderation Actions
7. **Authentication and Security:**
- User Credentials
- Session Data
- Security Logs
3. **Functional and Non-Functional Requirements**
1. **Functional Requirements**
1. **User Registration and Authentication**
- Users must be able to register with a unique username and password.
- Users can log in with their credentials.![ref1]
- User authentication must be secure and protect against unauthorized access.
2. **User Profiles**
- Users can create and manage their profiles.
- Profiles should include user information, profile picture, and optional personal details.
- Users can update and customize their profiles.
3. **Posting and Sharing**
- Users can create text posts, upload images, videos, and links.
- Posts can be edited and deleted by the user who created them.
- Users can like, comment on, and share posts from others
4. **Friends and Follower**
- Users can send friend requests.
- Users can accept or decline friend requests.
- Users can follow other users without requiring mutual friendship.
5. **Messaging**
- Users can send private messages to friends and followers.
- Messaging should support text, images, videos, and attachments.
- Messages should have real-time chat functionality.
6. **Notifications**
- Users receive notifications for friend requests, likes, comments, and messages.
- Users can customize notification preferences.
7. **Search and Discovery**
- Users can search for other users, posts, and content by keywords and hashtags.
- The system suggests friends and content based on user preferences.
2. **Non-Functional Requirements**
1. **Performance**
- The website should load quickly and handle a large number of concurrent users.
- Response times should be minimal for typical user interactions.
2. **Security**
- User data must be securely stored and transmitted.
- Passwords must be hashed and stored securely.
- Protection against common web vulnerabilities (e.g., XSS, CSRF) is required.
3. **Scalability**
- The system should be able to scale horizontally to accommodate increasing user loads.
- Scalability should not compromise performance.
4. **Availability![ref1]**
- The website should aim for high availability, with minimal downtime for maintenance.
5. **Usability**
- The user interface should be intuitive and easy to navigate.
- Mobile responsiveness is essential.
4. **External Interface Requirement**
1. **Social Media Sharing APIs**

**Description:** The system shall integrate with external social media sharing APIs (e.g., Facebook, Twitter, Instagram) to allow users to share content from the social media website to their social media profiles.

**Requirements:**

- Users shall be able to connect their social media accounts.
- Users shall be able to post content from the social media website to their connected social media accounts.
2. **Content Delivery Network (CDN)**

**Description:** To optimize content delivery and reduce latency, the system shall use a Content Delivery Network (CDN) for serving static assets (e.g., images, videos). **Requirements:**

- Content shall be cached and distributed through the CDN to improve content loading speed.
3. **Third-Party Authentication Providers**

**Description:** The system shall integrate with third-party authentication providers (e.g., Google, Facebook) to enable users to log in using their existing accounts.

**Requirements:**

- Users shall have the option to log in using third-party accounts.
- User data retrieved from third-party providers shall be securely managed and stored**.**
5. **Hardware Interfaces**
1. **Server Hardware**

**Description:** The system shall be hosted on physical or virtual servers with sufficient computing resources to handle user requests and data storage.

**Requirements:**

- Server hardware shall be scalable to accommodate increasing user loads.
- Redundancy and failover mechanisms shall be in place to ensure high availability.
2. **Storage Devices**

**Description:** The system shall use storage devices (e.g., hard drives, SSDs) to store user- generated content and data.

**Requirements:![ref1]**

- Storage devices shall have adequate capacity to store user data, including text, images, videos, and user profiles.
- Regular data backups shall be performed for disaster recovery.
6. **Software Interfaces**
1. **Database Management System (DBMS)**

**Description:** The system shall use a relational database management system (e.g., MySQL, PostgreSQL) to store and retrieve user data.

**Requirements:**

- The DBMS shall support efficient data retrieval for user profiles, posts, and messages.
2. **Web Server Software**

**Description:** The system shall run on web server software (e.g., Apache, Nginx) to handle HTTP requests and serve web pages.

**Requirements:**

- The web server shall be configured to support secure connections using SSL/TLS.
- It shall be capable of handling concurrent user connections efficiently.
7. **System Features**
1. **User Registration and Authentication:**
- User account creation with email verification or social media login.
- Secure authentication and password recovery mechanisms.
2. **User Profiles:**
- Customizable user profiles with profile pictures and cover photos.
- Options to add personal information, such as bio, location, and website links.
- Privacy settings to control who can view profile information.
3. **Content Posting:**
- Ability to create and share various types of content, including text, images, videos, links, and polls.
- Rich text editor for formatting posts.
- Tagging other users in posts.
- Scheduling posts for future publishing.
4. **Interactions:**
- Likes, reactions, and comments on posts.
- Share or re-tweet posts to reach a wider audience.
- Private messaging and chat functionality.
- Mentioning and tagging other users in comments and posts.
5. **Friend and Follower System:![ref1]**
- Ability to follow other users and be followed.
- Friend requests and mutual friend management.
6. **Notifications:**
- Real-time notifications for interactions (likes, comments, mentions, messages).
- Email or push notifications based on user preferences.
7. **User Settings and Preferences:**
- Account settings, including privacy settings.
- Notification preferences and frequency.
- Theme customization and dark mode.
8. **User Blocking and Privacy Controls:**
- Ability to block or mute users.
- Options to control who can comment on posts and send messages.
9. **Security Measures:**
- Account security features like two-factor authentication (2FA).
- Protection against common security threats, such as XSS and CSRF attacks.
8. **Glossaries**
- **User :** An individual registered on the social media website.
- **Profile :** A user's personal page containing information about them.
- **Post :** User-generated content, including text, images, videos, and links.
- **Friend:** A mutual connection between two users.
- **Follower :** A one-way connection where one user can follow another's updates.
- **Notification :** A message or alert informing users of specific events or interactions.
9. **Maintenance**
1. **Routine Maintenance**
   1. **Regular Updates:** The development team shall provide regular updates to the social media website to address bugs, security vulnerabilities, and performance improvements.
   1. **Software Patching:** Critical security patches and bug fixes shall be applied promptly to ensure system security and stability.
   1. **Database Maintenance:** Routine database maintenance, including optimization and backups, shall be performed to maintain data integrity.
1. **Feature Enhancements**
1. **Feature Requests:** A process shall be in place to collect and prioritize user feedback and feature requests for future enhancements.
1. **New Feature Development:** The development team shall plan and implement new features based on user demand and market trends.

[ref1]: Aspose.Words.a0637858-4cf9-416d-b935-6fcb62415a1f.001.png
