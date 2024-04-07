# Home Assistant Community Add-on: Haargos

Haargos provides advanced monitoring and analytics for your Home Assistant setup.
It offers insights into your smart home's health, performance, and more.

## Installation

To install Haargos on your Home Assistant system:

1. Navigate in your Home Assistant frontend to **Settings** \
-> **Add-ons** -> **Add-on store**.
2. Find the "Haargos" add-on and click it.
3. Click on the "INSTALL" button.

## How to use

1. In the configuration section, enter an `agent_token`. \
This token is used for authentication and data exchange with Haargos.
2. Save the configuration.
3. Start the add-on.
4. Check the add-on log output to see if startup was successful.
5. Check the respective Haargos installation to see reported data.

## Configuration

Add-on configuration:

```yaml
agent_token: YOUR_AGENT_TOKEN
```

### Option: `agent_token` (required)

The agent token required for the Haargos agent to authenticate \
and communicate with the Haargos service.
Grab it from your installation in [Haargos](https://haargos.com)

### Option: `HA Access Token` (optional)

Supplying a Home Assistant access token allows the agent to collect notifications from your system.

### Option: `dev` (required)

Use only if you are a Haargos tester.

## Support

For questions and support:

- Visit the [Haargos website](https://haargos.com).
- For bug reports, please [open an issue on our GitHub](https://github.com/haargos/ha-addons).
