+++
title = "The Paranoid Android"
description = "A Discord bot for linking to SCP Wiki items."
date = 2020-09-16T23:29:00.735Z

[extra]
repository = "SkeletonsAreBad/the-paranoid-android"
image = "/img/uploads/marv.png"
+++
# Introduction

The Paranoid Android is a Discord bot that is designed to let you view information from the SCP Wiki within Discord. It lets you view info such as SCP articles, tales, SCP-001 proposals, mobile task force units, and groups of interest. The Paranoid Android will automatically detect when you mention an SCP and will link you to the article. You can invite the bot to your own server by [clicking this link right here, yes this one](https://discord.com/api/oauth2/authorize?client_id=699167907254501457&permissions=19456&scope=bot).

Please note: Right now I'm not hosting the bot myself but if you would like to use it on your own bot account you can find the project files on GitHub.

# Usage

## Info & Commands

If you are interested in viewing information about the bot, you can mention the bot on its own or run:

> ./info

If you want to know what commands you can use with the bot, you can run:

> ./help

## SCP Wiki Listings

The Paranoid Android allows you to view articles from the SCP Wiki such as SCP items and tales. You can also view listings from the Canon Hub, SCP-001 proposals, Mobile Task Forces, and Groups Of Interest.

### Wiki Articles

You can view an article that is on the SCP Wiki by running:

> ./article \[title]

This can also be useful for very specific SCP articles that wouldn't be automatically detected because of their naming such as [SPC-1057-J](http://scp-wiki.net/spc-1057-j) and [MZL-1730](http://scp-wiki.net/mzl-1730). Please make sure that when you are entering the title for the article you are after that you correctly spell it otherwise the bot can't find it.

#### Why are certain things missing?

When the bot automatically detects SCP items it displays information which is not seen when running the article command such as the SCP series and the SCP title. This is purely because of how the SCP Wiki works and how we interact with it. When detecting SCP items the bot tries to determine what series the SCP is from and uses that information to get the series name and SCP title. If this were to be done with the article command as well as getting the article info it would take roughly twice as long and while this isn't too long I would rather reduce resource usage and increase performance.

### SCP-001 Proposals

To view a list of the SCP-001 proposals you can run:

> ./scp001

### Mobile Task Forces

To view a list of the Mobile Task Forces you can run:

> ./mtf

To view more information about a Mobile Task Force you can run:

Where the code is a greek letter follow by a number such as 'MTF **Mu-4** ("Debuggers")'. Example:

> ./mtf mu-4

### Groups Of Interest

To view a list of Groups Of Interest you can run:

> ./goi

To view more information about a Group Of Interest you can run:

> ./goi \[name]