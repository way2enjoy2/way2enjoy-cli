# Way2enjoy CLI

> Handy command line tool for shrinking JPG,PNG,GIF images including PDF, MP3, MP4 and all music, video files using the Way2enjoy API

## Installation

	npm install -g way2enjoy-cli

## Preamble

To use way2enjoy CLI, you need an API key for way2enjoy. You can get one at [https://way2enjoy.com/developers](https://way2enjoy.com/developers).

## Usage

way2enjoy CLI allows you to provide your API key in two different ways. The more convenient one is to save the API key into a file called `.way2enjoy` within your home directory. The other way is to provide it as an option while running the CLI.

	way2enjoy demo.png -k Hk09oPOI899j98080970990

To optimize all JPG, PNG, GIF images , PDF, MP3, MP4 files and all Music/Video files within the current directory, you may run one of the following commands—both do exactly the same.

	way2enjoy
	way2enjoy .

To optimize all JPG, PNG, GIF images , PDF, MP3, MP4 files and all Music/Video files within the current directory and subdirectoies, use the `-r` flag

	way2enjoy -r

To optimize all JPG, PNG, GIF images , PDF, MP3, MP4 files and all Music/Video files within a specific directory (`assets/img` in this example), you may run the following command.

	way2enjoy assets/img

You may also provide multiple directories.

	way2enjoy assets/img1 assets/img2

To shrink a single image (`assets/img/demo.png` in this example), you may run the following command.

	way2enjoy assets/img/demo.png

You may also provide multiple images.

	way2enjoy assets/img/demo1.png assets/img/demo2.png

To resize an image, use the `--width` and/or `--height` flag.

	way2enjoy assets/img/demo.png --width 123
	way2enjoy assets/img/demo.png --height 123
	way2enjoy assets/img/demo.png --width 123 --height 123

That's it. Pretty easy, huh?

## Changelog

* 0.0.1
	* Initial version

## TODO

- Documentation
- Tests

## License

Copyright (c) 2019[way2enjoy2](https//way2enjoy.com/)  
Licensed under the MIT license.

See LICENSE for more info.

## Contributors

- [@rasshofer](https://github.com/rasshofer)
- [@maxkueng](https://github.com/maxkueng)
- [@tholu](https://github.com/tholu)
- [@mvenghaus](https://github.com/mvenghaus)
- [@jblok](https://github.com/jblok)
- [@tomatolicious](https://github.com/tomatolicious)
- [@kolya182](https://github.com/kolya182)
