.. _Instagram: https://www.instagram.com/

DjangoGram
==========

The project is a social media site inspired by `Instagram`_, built using
Django and Django REST framework. It focuses on fundamental Django
functionalities, including user authentication, content management, and REST
API integration. The site allows for image sharing, user interactions, and
profile management.

Project goals
-------------

-   Provide a practical learning experience in building a feature-rich social
    media platform using Django.
-   Focus on user privacy and data management, reflecting real-world
    application requirements.
-   Encourage best practices in REST API design and implementation.
-   Develop an understanding of user role management and administrative
    controls within a web application.

Key features
------------

.. rubric:: User registration and authentication

The application will provide user registration and authentication
functionality, allowing individuals to create accounts, log in, and manage
their profile information. This feature will enable authors to have
personalized accounts and maintain ownership of their published images or
stories.

.. rubric:: Images gallery

Users can upload their images to their own site page and maintain access
restrictions. The entire gallery may be marked as private, or public. On
the other hand each single image can be marked as private, or public.

.. rubric:: Connections

The site allows its users to create connections.
Each user can send the connection request to another user.
Once the request is approved by the target user, the connection is established.

.. rubbic:: Site administration

Site admins cannot delete anything from the site. However admins can mark any
image uploaded to the site as "deleted", or block (deactivate) any registered
account.

User registration and authentication
------------------------------------

-   For anonymous users there will be "Sign Up" and "Sign In" options available
    on each page.
-   For authenticated users "Logout" option is available from any site page.
-   Deactivated users cannot log in and mainly acts as anonymous users.
-   Deactivated users will receive a link to request the account restore from
    site admins.
