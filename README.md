# Project Zomboid Translations

## Overview
This repository is for the video game Project Zomboid (https://projectzomboid.com/) translation files to allow community translators a centralised location to collaborate and see when translations are updated by the developers.

## Contributing

There are two ways of contributing.

The first way is to fork the repository (or find someone who has forked it and get access to contributing the repository) and make the necessary changes you need to, before initiating a pull request so that the changes can be accepted into the main repository.

The second way is to request access to this repository/organisation and use/create a branch associated with the language you are updating to make your changes in and then initiate a pull request for the changes to get merged in master branch.

The master branch acts as the default branch and reflects the live version of what gets distributed in the most recent build of the game. As such, the branch has been protected and therefore requires review before pull requests are merged in.

It is wise to seek out if contribution is actively happening with a language and join that effort, before starting up one on your own.

TAKE NOTE: We treat forks and branches as work in progress and we will not merge in these locations without a pull request.

Contributing to the repository is voluntary and abides by the Project Zomboid Terms & Conditions: https://projectzomboid.com/blog/2013/09/terms-conditions/

Some languages use different encoding (See [issue #155](https://github.com/TheIndieStone/ProjectZomboidTranslations/issues/155)), but GitHub should show all symbols correctly with [pull request #423](https://github.com/TheIndieStone/ProjectZomboidTranslations/pull/423). You can also change encoding with external editor or use TranslationZed tool available under *[Releases](https://github.com/TheIndieStone/ProjectZomboidTranslations/releases)* and upload the files it saves.

## TranslationZed

Windows binaries are provided, but the program can be launched on different platforms with OpenJDK8 and OpenJFX8 by navigating to the folder and starting it with `java -jar translatoid.jar` or similar command.

## Testing Translations Locally

To test the translations (or modified English texts) in your game, place the files from this repository in `…\projectzomboid\media\lua\shared\Translate`

You can back up the original translation first and then replace the folder or make a copy or a symbolic/hard link to a mirror of this repository.

## Joining As Contributor

If you want to join as a contributor instead of forking, then create an issue or send a message to the repository maintainers/admins, or through Discord.

If you have questions you can click the link below to get to the Discord server and post to the #translations channel.

## Links

* Translation Discussion Thread: https://theindiestone.com/forums/index.php?/topic/23806-official-translation-files-v2/

* Discord Server: https://discord.gg/0lGvMrCiUWbasJFh

* Game Website: https://projectzomboid.com/
