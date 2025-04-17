# Build Vendor

[![License](https://img.shields.io/github/license/zhanglianxin/build-vendor)](LICENSE)

GitHub Actions workflow to build dependencies for PHP or Node.js projects.

Perfect solution for VPS with limited resources!

Let GitHub Actions handle the heavy lifting of dependency installation, perfect for resource-constrained VPS environments.

## 🚀 Features

### For PHP Projects

[![Build vendor of PHP project](https://github.com/zhanglianxin/build-vendor/actions/workflows/online-repo.yml/badge.svg)](https://github.com/zhanglianxin/build-vendor/actions/workflows/online-repo.yml)

- Build `vendor` directory using GitHub Actions
- Avoid memory limit issues during `composer install`
- Support different PHP versions
- Production/Development dependencies options

### For Node.js Projects

[![Build pages of httpstatuses.io](https://github.com/zhanglianxin/build-vendor/actions/workflows/httpstatuses.yml/badge.svg)](https://github.com/zhanglianxin/build-vendor/actions/workflows/httpstatuses.yml)

- Build static assets using GitHub Actions
- Handle heavy `npm build` processes remotely
- Support different Node.js versions
> [!WARNING]
> Feel free to make some adjustments to suit yourself 🙃
- Optimize for production builds

## Why This Tool?

As an AWS Lightsail user, I encounter notable pain points 😔 during specific operations.

- **Save VPS Resources**: Build vendor directories on GitHub's powerful runners instead of your VPS
- **Save Bandwidth**: Download a single zip instead of running `composer install`
- **Fast Deployment**: Pre-built vendor directory makes deployment quick
- **Multiple PHP Versions**: Build with different PHP versions without installing them locally
- **No Composer Issues**: Bypass common composer memory limit issues on small VPS

## 📝 Usage

1. Go to the Actions tab
2. Select one of the workflows
3. Click "Run workflow"
4. Fill in the parameters if needed
5. Run the workflow
6. Download the artifact when the workflow completes

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
