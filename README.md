# Stage Three Task Documentation

## Database Design
### users
This includes the personal details such as first name, last name, email and password

### organisations
The name and description are stored

### activity log
Activities such as create, update and delete gets logged for each user

### user organisations
Displays the relationship between users and organisations they belong to

### roles
Roles are created to be assigned to each users that exist

### blog
Gets created by different author/users that exist in the system

### payments
Transactions made are stored with record of the user that initiate the transaction, payment method, status and amount paid

Other tables provided for in the database design are regions, notifications, user languages, notifications, magic links, social auth,
blog comments, email templates, invite links, settings, password resets, invites and languages.


## API Design
Different endpoints are created for the user, blog, organisation and payment. They include:

- Register a new user
- Login a user
- Update and delete an existing user
- Create, update, retrieve and delete blog post, organisation, waitlist, invite, notification, blog comment, invite link, language, region and email template
- Create and delete payments
- Retrieve and delete social auths, magic links, password resets, contact messages

## Design Image

<a href="https://dbdiagram.io/d/669152f79939893daec95175" style="text-decoration:none;"><img src="https://res.cloudinary.com/dgszzbmfi/image/upload/v1720897476/Stage3_1_nvvovg.png" alt="database design"></a>

## API url

- Click on the [API URL](https://app.swaggerhub.com/apis/AdelakunShola/boilerplate/1.0.0#/) to access the different endpoints available


## Contributors
- [BL4ZE-DEV](https://github.com/BL4ZE-DEV)
- [AdelakunShola](https://github.com/AdelakunShola)
- [AbisolaMajeed](https://github.com/AbisolaMajeed)
- [t33w411](https://github.com/t33w411)
- [davistheweb](https://github.com/davistheweb)


## Additional Resources
- [DBDiagram](https://dbdiagram.io/)