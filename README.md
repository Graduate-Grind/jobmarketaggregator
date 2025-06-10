# jobmarketaggregator
Job Market Aggregator

## Secrets Management
This project uses Infiscial.

```sh
git clone https://github.com/Graduate-Grind/jobmarketaggregator.git
cd jobmarketaggregator
infiscial login
infisical export --env=dev --path=/ --format=dotenv > .env
```

May need to use Python SDK in the future: https://github.com/Infisical/python-sdk-official
- Example setup: https://infisical.com/docs/documentation/guides/python