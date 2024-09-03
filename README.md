# Ruby on Rails 6.0 New Features

## 1. Multiple Database Support
- **Introduction**: Rails 6.0 introduced first-class support for using multiple databases within a single application.
- **Features**:
  - Support for horizontal sharding and read/write splitting.
  - Built-in tools for managing migrations across different databases.
  - Seamless integration with Active Record.

## 2. Action Mailbox
- **Introduction**: Action Mailbox routes incoming emails to controller-like mailboxes for processing.
- **Features**:
  - Handles inbound emails in Rails applications.
  - Supports popular email services like Amazon SES, Mailgun, and Postmark.
  - Integrates with Active Storage for attachments.

## 3. Action Text
- **Introduction**: Action Text brings rich text content and editing capabilities to Rails applications.
- **Features**:
  - Uses Trix editor for managing rich text content.
  - Supports embedding images, videos, and other attachments through Active Storage.
  - Integrates with models to handle rich text as an attribute.

## 4. Parallel Testing
- **Introduction**: Rails 6.0 introduced parallel testing to speed up test suites.
- **Features**:
  - Executes tests in parallel, using multiple database connections.
  - Significantly reduces the time taken to run large test suites.
  - Easy to configure and use with existing tests.

## 5. Webpacker as the Default JavaScript Bundler
- **Introduction**: Webpacker became the default JavaScript bundler in Rails 6.0.
- **Features**:
  - Replaces the older asset pipeline for JavaScript, making it easier to use modern JavaScript tools and libraries.
  - Provides out-of-the-box support for React, Vue, Angular, and other front-end frameworks.
  - Integrates seamlessly with Rails views.

## 6. Action Cable Testing
- **Introduction**: Rails 6.0 added testing support for Action Cable, the framework for handling WebSockets in Rails.
- **Features**:
  - Allows unit and integration testing of Action Cable channels.
  - Provides tools for simulating WebSocket connections and broadcasting messages.

## 7. Default Hostname for URL Generation
- **Introduction**: Rails 6.0 introduced a default hostname configuration for URL generation.
- **Features**:
  - Configures the default hostname used in `url_for` and other URL generation helpers.
  - Simplifies the configuration of URL generation in different environments.

---

# Ruby on Rails 6.1 New Features

## 1. Horizontal Sharding
- **Introduction**: Rails 6.1 enhanced support for horizontal sharding in applications with multiple databases.
- **Features**:
  - Provides a cleaner API for defining and using shards.
  - Improves the scalability of applications with massive data distribution needs.

## 2. Delegated Types (Polymorphic Associations Enhancement)
- **Introduction**: Rails 6.1 introduced `Delegated Types` as a better alternative to traditional polymorphic associations.
- **Features**:
  - Simplifies the handling of polymorphic associations by making them more explicit and type-safe.
  - Enhances the readability and maintainability of code.

## 3. Active Record Encryption
- **Introduction**: Rails 6.1 introduced built-in encryption support for Active Record attributes.
- **Features**:
  - Provides a simple API for encrypting and decrypting sensitive data.
  - Supports both deterministic and non-deterministic encryption.
  - Integrates seamlessly with existing Active Record models.

## 4. Asynchronous Query Loading
- **Introduction**: Rails 6.1 added support for asynchronous query loading in Active Record.
- **Features**:
  - Allows queries to be run in parallel, improving performance for certain operations.
  - Reduces the time spent waiting for database queries to complete.

## 5. Improved Error Reporting
- **Introduction**: Rails 6.1 improved error reporting for failed validations and queries.
- **Features**:
  - Provides more detailed error messages for failed validations.
  - Enhances debugging by including additional context in error reports.

## 6. Zeitwerk Mode as Default
- **Introduction**: Zeitwerk became the default autoloader in Rails 6.1, replacing the older classic mode.
- **Features**:
  - Provides a more efficient and reliable way to autoload constants.
  - Supports modern Ruby features like modules and namespacing better.
  - Automatically reloads changes in development mode.

## 7. Schema Dumping with Foreign Keys
- **Introduction**: Rails 6.1 added support for dumping schema with foreign keys.
- **Features**:
  - Ensures that schema dumps include foreign key definitions.
  - Improves the accuracy and completeness of schema dumps.

## 8. Encrypted Credentials Support for Multiple Environments
- **Introduction**: Rails 6.1 improved credentials management by supporting environment-specific encrypted credentials.
- **Features**:
  - Allows different credentials for different environments (e.g., development, test, production).
  - Simplifies the management of sensitive data across multiple environments.

