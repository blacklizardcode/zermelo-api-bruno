# Zermelo api bruno

This is a repository putting the zermelo api into bruno for testing and reference for **your** projects.

## How to use

1. Download the project: code -> Download Zip
2. Unzip with your favorite unzipping tool 
3. In bruno click on the hamburger menu in the top right
4. File -> Open Collection
5. Select the unzipped folder
6. configure the env vars by clicking on `zermelo` in the navigation of bruno -> `1 collection environment` and set at least the env var `baseUrl` and `code` or `access_token`

## Folder structure

``` yaml
zermelo-api-bruno
├── documented # Endpoints documented at https://docs.zportal.nl/docs/
├── enviroments
│   └── zermelo.yaml # Configuration for variables
├── undocumented # Endpoints that are not documented at https://docs.zportal.nl/docs/
└── readme.md # This file

```

## Todo

- [x] endpoints from the [docs](https://docs.zportal.nl/docs/)
- [ ] endpoints from the [swagger ui](https://rlo.zportal.nl/static/swagger/)

## Contributing

If you wish to contribute please do so, the easy part is just done and we still need to document most of the api.

### Tools
https://rlo.zportal.nl/static/swagger/

https://docs.zportal.nl/docs/

### Guidelines

- No fake endpoints - all endpoints will have to be in the [swagger ui](https://rlo.zportal.nl/static/swagger/
)
- No location specific endpoints. I have not yet found these, but if you do - **do not** create a pull request with these.
