# Podspecutil

Podspecutil is a command line script for managing CocoaPod podspecs. With Podspecutil, you can push podspecs to remote spec repos, update podspec versions, tag repos with podspec versions, and validate podspecs using pod spec lint.

## Requirements

Podspecutil requires the following:

Ruby 2.6.3 or later
Cocoapods 1.8.4 or later

## Installation

To install Podspecutil, simply clone this repository and move the `podspecutil` file to /usr/local/bin/ and run

```bash
chmod +x /usr/local/bin/podspecutil
```

## Usage

To use Podspecutil, simply run the following command in your terminal:

```bash
podspecutil <command> [<args>]
```

## Usage

```
$ podspecutil <command> [<args>]

Commands:
  push         Validate and push a podspec to a remote spec repo.
  update       Update the version of a podspec and commit the changes.
  tag          Tag the repo with the current podspec version and push the change to the remote spec repo.
  validate     Validate a podspec using pod spec lint.

Arguments:
  --spec-repo=<name>      Name of the remote spec repo to push to or pull from.
  --sources=<source1,source2,...>   Comma-separated list of private Cocoapod source URLs to use.
  --path=<path>           Path to the directory containing the podspec. Defaults to the current working directory.
  
Options:
  --help, -h              Show this help message and exit.
```

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/joeypatino/podspecutil. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the Contributor Covenant code of conduct.

## License

podspecutil is available as open source under the terms of the MIT License.
