# keycloak-theme
![Login page](https://user-images.githubusercontent.com/26229521/220850878-4f25e29e-123e-4e91-9e0a-1023ac7433cb.png)

## Installation
Clone the repo into the theme directory of your keycloak install. Log into the Administration Console, choose the desired realm, then goto Realm settings -> Themes and select the theme.

## Developers
It is highly recommended to read the [documentation](https://www.keycloak.org/docs/latest/server_development/#_themes) on creating Keycloak themes before getting started. Here's a brief summary:
- Each top level directory corresponds to a theme type: `account`, `admin`, `commmon`,`email` or `login`.
- The file `theme.properties` in each theme type contains a long list of properties.  Most noteably it specifies the parent theme. 
- HTML templates are coded using FreeMarker Template Language (`.ftl`).
- The `resource` directory for a theme contains stylesheets, scripts, imgaes, and so on.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
