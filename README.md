# Example: Single Page App using Microsoft OIDC

For very simple apps, especially where you don't need an active server, a Single Page App that can simply rely on authentication and identity information provided by an OIDC provider (such as Facebook) is much easier to build. It means you don't have anything heavy weight to implement at your end.

## Getting Started

See - full example workthrough here: [Medium - Example Sinlge Page App Using Microsoft OIDC](https://aubyncrawford.medium.com/example-single-page-app-using-microsoft-oidc-ac71a9d54318)

### Prerequisites

This project was created with Visual Studio 2019, and is an ASP.NET Core 3 Web Application

The example is targeted to Microsoft Azure AD, so you would need a tenant configured to connect to. However, the code will work with any OIDC Provider


## Deployment

This sample can be run locally, as long as it can reach the OIDC provider to carry out authentication

## Built With

* Visual Studio 2019 - ASP.NET Core 3 and Razor pages
* [oidc-client-js](https://github.com/IdentityModel/oidc-client-js) - OpenID Certified JavaScript library


## License

This is just code brought together to help others get started quickly, nothing unique. Licensed under Zero-Clause BSD - see [LICENSE.md](LICENSE.md)

## Acknowledgments

* Identity Server project / site has a lot of good walkthroughs, and I used this page to help me build out the example https://identityserver4.readthedocs.io/en/aspnetcore1/quickstarts/7_javascript_client.html
* Billie Thompson - README Template - [PurpleBooth](https://github.com/PurpleBooth)


