# Mittayi

Mittayi is a platform for selling authentic sweets, savouries, and snacks with a focus on quality and tradition. The platform supports various features including user authentication, product management, order processing, and payment handling.

## Features

- **User Authentication**: Sign up and login for users and admins.
- **Product Management**: Admins can add, update, and manage products.
- **Shopping Cart**: Users can add products to their cart and proceed to checkout.
- **Payment Integration**: Secure payment gateway integration.
- **Order Tracking**: Users receive notifications about their order status.
- **Delivery Management**: Integration with third-party delivery services.

## Technologies Used

- **Frontend**: React JS
- **Backend**: Spring Boot 3.3.2, Go (for specific microservices)
- **Database**: MySQL, PostgreSQL, MongoDB.
- **Message Broker**: Kafka
- **Deployment**: Docker, Kubernetes

## Installation

Clone the repository:

	git clone https://github.com/username/Mittayi.git

Checkout to the development branch:
	git checkout dev


## Development Workflow:

### Branch Protection and Pull Requests

- **Branch Name**: `dev`
- **Protected**: Yes
- **Rules**:
  - All changes must be made via pull requests.
  - Pull requests require approval (1 required).
  - Stale pull request approvals will be dismissed with new commits.
  - Status checks (if applicable) must pass before merging.
  - Branch must be up to date before merging.
  - Conversations must be resolved before merging.
  - Signed commits are optional.
  - Linear history and deployments (if applicable) are optional.
  - Force pushes and deletions are not allowed.

### Developer Workflow

1. **Create a Feature Branch**:
   ```bash
   git checkout -b feature/your-feature
2. Make Changes and Commit:
	git add .
	git commit -m "Description of changes"
3. Push the Feature Branch:
	git push origin feature/your-feature.
4. Create a Pull Request:
	Submit a pull request from your feature branch to dev on GitHub.

