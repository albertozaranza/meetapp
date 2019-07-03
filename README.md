# MeetApp
App event aggregator for developers configured with the following tools:

- Sucrase + Nodemon;
- ESLint + Prettier + EditorConfig;
- Sequelize (PostgresSQL);

## Functionalities

Below are described some application present features.

### Authentication

Allowed a user to authenticate in the application using email and password.

- Authentication using JWT.
- Perform the validation of the input data;

### Registering and updating users

Allows new users to sign in to the application using name, email and password.

To update the password, the user must also send a confirmation field with the same password.

- User password encryption for security.
- Validation of the input data;
