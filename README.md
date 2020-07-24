# Actions Builder Community Types

Community Types is a collection of open Types to use with [Actions Builder](https://developers.google.com/assistant/conversational/build). These Types were contributed by the community!

## Usage

Use the table below to find a Type you are looking for.

Include the type in your project using the [gactions CLI](https://developers.google.com/assistant/actionssdk/gactions).

Run following command in project directory where you can clone the Actions files:

```shell
gactions pull --project-id {project-id}
```

This downloaded your complete Actions on Google project.

Copy the Type .yaml file into `custom/types` folder.

Run following command to push your updates to the Action!

```shell
gactions push
```

## Contents

| Type                                        | Description                                                | Source                                                                                 |
| ------------------------------------------- | ---------------------------------------------------------- | -------------------------------------------------------------------------------------- |
| [Yes/No](builder/types/YesNo.yaml)          | Yes / No type                                              |
| [Languages](builder/types/Languages.yaml)   | All languages supported by AoG with language code as a key | [AoG Documentation](https://developers.google.com/assistant/console/languages-locales) |
| [Currencies](builder/types/Currencies.yaml) | Currencies with currency code as a key                     | [ISO 4217](https://en.wikipedia.org/wiki/ISO_4217)                                     |
| [URL](builder/types/URL.yaml)               | Regex type that matches URL                                |
| [Color](builder/types/Color.yaml)           | Color type with color names and HEX code as a key          | [color-names](https://github.com/meodai/color-names)                                   |

## Contributing

Pull requests with additional types/fixes for current types are more than welcome! Please just make sure that you have permission to use the data you are contributing. Thanks!

## Contributors

Created by [@DenisValasek](https://twitter.com/DenisValasek)

## License

[MIT](https://choosealicense.com/licenses/mit/)
