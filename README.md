# Paperspace Environment Instantiation CI/CD

## Description

This repository contains the code for setting up a Continuous Integration and Continuous Deployment (CI/CD) pipeline for environment instantiation on Paperspace. Currently, this only includes github actions that can spin up and spin down compute instances via API calls to Paperspace.

## Usage

To install and use this project, follow these steps below:
*Note: paperspace API access and a static IP setup in paperspace are prerequisites. To get API access and set up the IP, follow the directions [here](https://docs.paperspace.com/core/quick-start/) and [here](https://docs.paperspace.com/core/networking/public-ips/#how-to-assign-a-public-ip) respectively.*

1. Fork and rename the repository to that is the intended use case.
2. Create a Github Actions Secrets titled PAPERSPACE_API_KEY and PAPERSPACE_MACHINE_ID, then paste the paperspace API key and static IP as the secret values for the secrets.
3. Go to Actions in github and run activate-instance.yaml to spin up an instance.

## Contributing

If you want to contribute to this project, please follow these steps:

1. Fork the repository
2. Create your feature branch: `git checkout -b feature/your-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin feature/your-new-feature`
5. Submit a pull request

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.