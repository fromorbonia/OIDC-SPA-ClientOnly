# Example: Single Page App using Microsoft OIDC

For very simple apps, especially where you don't need an active server, or where you have a Single Page App that can simply rely on authentication and identity information provided by an OIDC provider (such as Facebook). You don't want anything heavy weight to implement at your end.

## Getting Started

See - full example workthrough here:

### Prerequisites

This project was created with Visual Studio 2019, and is an ASP.NET Core 3 Web Application

You will need a Microsoft Azure AD tenant configured to connect to, although the code should work with any OIDC Provider


## Deployment

This sample can be run locally, as long as it can reach the OIDC provider to carry out authentication

## Built With

* Visual Studio 2019 - ASP.NET Core 3 and Razor pages
* [oidc-client-js](https://github.com/IdentityModel/oidc-client-js) - OpenID Certified JavaScript library


## Authors


See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This is just code brought together to help others get started quickly, nothing unique. Licensed under Zero-Clause BSD - see [LICENSE.md](LICENSE.md)

## Acknowledgments

* The Identity Server site has a lot of good walkthroughs, and I used this page to help me build out the example https://identityserver4.readthedocs.io/en/aspnetcore1/quickstarts/7_javascript_client.html
* Billie Thompson - README Template - [PurpleBooth](https://github.com/PurpleBooth)


