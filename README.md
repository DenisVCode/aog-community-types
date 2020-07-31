# Actions Builder Community Types

Community Types is a collection of open Types to use with [Actions Builder](https://developers.google.com/assistant/conversational/build). These Types were contributed by the community!

## Usage

Use the contents table below to find a Type you are looking for.

Include the type in your project using the [gactions CLI](https://developers.google.com/assistant/actionssdk/gactions).

Run following command in project directory where you can clone the Actions files:

```shell
gactions pull --project-id {project-id}
```

This downloaded your complete Actions on Google project.

_For Types:_ \
Copy the Type .yaml file into `custom/types` folder. 

_For Intents:_ \
Copy the Intent .yaml file into `custom/intents` folder.

Run following command to push your updates to the Action!

```shell
gactions push
```

## Contents

### Types

| Type                                        | Description                                                | Source                                                                                 |
| ------------------------------------------- | ---------------------------------------------------------- | -------------------------------------------------------------------------------------- |
| [Yes/No](builder/types/YesNo.yaml)          | Yes / No type                                              |
| [Languages](builder/custom/types/Languages.yaml)   | All languages supported by AoG with language code as a key | [AoG Documentation](https://developers.google.com/assistant/console/languages-locales) |
| [Currencies](builder/custom/types/Currencies.yaml) | Currencies with currency code as a key                     | [ISO 4217](https://en.wikipedia.org/wiki/ISO_4217)                                     |
| [URL](builder/custom/types/URL.yaml)               | Regex type that matches URL                                |
| [Color](builder/custom/types/Color.yaml)           | Color type with color names and HEX code as a key          | [color-names](https://github.com/meodai/color-names)                                   |
| [Countries](builder/custom/types/Countries.yaml)           | Countries with country code as a key          | [ISO 3166-1](https://en.wikipedia.org/wiki/ISO_3166-1)                                   |
| [World Cities](builder/custom/types/Cities_World.yaml)           | World Cities with City\|Country as a key          | [Simplemaps.com](https://simplemaps.com/data/world-cities)                                   |
| [US Cities](builder/custom/types/Cities_US.yaml)           | US Cities with City\|Country as a key          | [Simplemaps.com](https://simplemaps.com/data/world-cities)                                   |
| [Capital Cities](builder/custom/types/Cities_US.yaml)           | World Capital Cities with City\|Country as a key          | [Simplemaps.com](https://simplemaps.com/data/world-cities)                                   |
| [Major Cities](builder/custom/types/Cities_US.yaml)           | Major World Cities with population > 500 000, City\|Country as a key          | [Simplemaps.com](https://simplemaps.com/data/world-cities)                                   |

### Intents
| Intent                                        | Description                                                | Language                                                                                 |
| ------------------------------------------- | ---------------------------------------------------------- | -------------------------------------------------------------------------------------- |
| [Yes](builder/custom/intents/Yes.yaml)   | - |  |
| [No](builder/custom/types/No.yaml)   | - |  |
| [Repeat](builder/custom/types/Repeat.yaml)   | - |  |
| [Help](builder/custom/types/Help.yaml)   | - |  |
| [Slow down](builder/custom/types/Speak_Slower.yaml)   |  -|  |

## Contributing

Pull requests with additional types/fixes for current types are more than welcome! Please just make sure that you have permission to use the data you are contributing. Thanks!

If you don't want to create the ```.yaml``` file itself, feel free to submit a ```.csv``` or link to Google Sheets!

## Contributors

Created by [@DenisValasek](https://twitter.com/DenisValasek)

## License

[MIT](https://choosealicense.com/licenses/mit/)
