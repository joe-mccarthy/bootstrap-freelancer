# Bootstrap Freelancer

![GitHub Actions Workflow Status](https://img.shields.io/github/actions/workflow/status/joe-mccarthy/bootstrap-freelancer/deploy-example.yml?branch=main&cacheSeconds=1)
![Sonar Quality Gate](https://img.shields.io/sonar/quality_gate/joe-mccarthy_bootstrap-freelancer?server=https%3A%2F%2Fsonarcloud.io&cacheSeconds=1)
![GitHub Release](https://img.shields.io/github/v/release/joe-mccarthy/bootstrap-freelancer?sort=semver&?cacheSeconds=1)
![GitHub commits since latest release](https://img.shields.io/github/commits-since/joe-mccarthy/bootstrap-freelancer/latest?cacheSeconds=1)
![GitHub License](https://img.shields.io/github/license/joe-mccarthy/bootstrap-freelancer?cacheSeconds=1)

## Getting Started

From the root of your site:

```bash
git submodule add https://github.com/joe-mccarthy/bootstrap-freelancer themes/bootstrap-freelancer
```

### Running the example-site

To try out the theme prior to changing your site to use the theme, you can start up the example site within the theme.

```bash
git clone https://github.com/joe-mccarthy/bootstrap-freelancer
cd example-site
hugo server --source . --themesDir ../../ --theme bootstrap-freelancer
```

Open your web browser to http://localhost:1313 to view the demo of the theme.

### Updating

From the root of your site:

```bash
git submodule foreach git pull origin main
```

### Run example site

```bash
hugo new site mysite -f yaml
cd mysite
git init
git submodule add https://github.com/joe-mccarthy/bootstrap-freelancer themes/bootstrap-freelancer
# update config.yaml theme variable to be theme: bootstrap-freelancer
hugo server
```
## Contributing

Have you found a bug or got an idea for a new feature? Feel free to use the [issue tracker](https://github.com/joe-mccarthy/bootstrap-freelancer/issues) to let me know. Or make directly a [pull request](https://github.com/joe-mccarthy/bootstrap-freelancer/pulls).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
