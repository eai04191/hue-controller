hue-controller
===

Hue web UI.

## Feature

- One-click light ON-OFF.

Other functions will implement if I needed. :wink:

For example, I live in a narrow house so there is only one group of Hue. Please give me some money!

## Usage

```
https://eai04191.github.io/hue-controller/?server=HUE_BRIDGE_IP&key=HUE_API_KEY&group=LIGHT_GROUP&scene=SCENE_ID
```

Replace `HUE_BRIDGE_IP`, `HUE_API_KEY`, `LIGHT_GROUP` and `SCENE_ID`.

### Is the connection not-secure?

Yes, The Hue Bridge API has not supported https.

This problem is known and can be addressed by using an HTTPS relay proxy. But it takes time and effort.

- [Using HTTPS from Hue Bridge? | Philips Hue API](https://developers.meethue.com/content/using-https-hue-bridge)


## License

This project is licensed under the MIT License.