# balena-hedgedoc

[HedgeDoc](https://hedgedoc.org/) is a real-time, multi-platform collaborative markdown note editor. This means that you can write notes with other people on your desktop, tablet or even on the phone. You can sign-in via multiple auth providers like Facebook, Twitter, GitHub and many more on the homepage.

## Getting Started

You can one-click-deploy this project to balena using the button below:

[![Deploy with balena](https://balena.io/deploy.svg)](https://dashboard.balena-cloud.com/deploy?repoUrl=https://github.com/klutchell/balena-hedgedoc&defaultDeviceType=raspberrypi3)

## Manual Deployment

Alternatively, deployment can be carried out by manually creating a [balenaCloud account](https://dashboard.balena-cloud.com) and application,
flashing a device, downloading the project, and pushing it via the [balena CLI](https://github.com/balena-io/balena-cli).

### Environment Variables

| Name | Description                                                                                                       |
| ---- | ----------------------------------------------------------------------------------------------------------------- |
| `TZ` | Inform services of the [timezone](https://en.wikipedia.org/wiki/List_of_tz_database_time_zones) in your location. |

You can find the full list of HedgeDoc options here: <https://docs.hedgedoc.org/configuration/>

## Usage/Examples

Once your device joins the fleet you'll need to allow some time for it to download the application and start the services.

When it's done you should be able to access the access the app at <http://hedgedoc.local>.

Additional usage instructions for this image can be found here: <https://docs.linuxserver.io/images/docker-hedgedoc>.

## Contributing

Please open an issue or submit a pull request with any features, fixes, or changes.
