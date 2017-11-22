# Cocoon Plugin Android Architecture

This plugin allows you to build your application for arm (or x86) only.

## Deployment

Include this plugin in your config.xml:
``` xml
<plugin name="cocoon-plugin-android-architecture" spec="https://github.com/CocoonIO/cocoon-plugin-android-architecture.git"/>
```

If you want to target x86, add the following preference:
``` xml
<preference name="android-architecture" value="x86"/>
```

If you want to target arm, add the following preference:
``` xml
<preference name="android-architecture" value="arm"/>
```

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **Martin Buchalik** - *Initial work* - [MBuchalik](https://github.com/MBuchalik)
* **Jorge Domínguez** - *Adapt to Cocoon.io* - [BlueSialia](https://github.com/BlueSialia)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.