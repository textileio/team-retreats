# 2020 Team Hackathon

This year we wanted to see what our team can build in 24 hours. Here is a preview of the outcomes. Here are the top five results.

## First Place

**Remote config for app developers.**

[@asutula](https://github.com/asutula)

This hack used the developer [Thread](https://blog.textile.io/introducing-textiles-threads-protocol/) in the [Textile CLI](https://cloud.textile.io) to generate Textile Project Configs.

Textile Project Config gives developers the ability to configure dynamic values on Textile Cloud that are then used by their apps. Project Config values can have different values per scope (eg. production, beta, development) and apps can read values explicitly or can subscribe to  a feed to real time changes to any value.

The demo shows a simple React App using a scoped variable (`endpoint`) to display information to users. Next, it shows how the developer can change the value of the `endpoint` key to update the app in real-time.

![Demo Gif](https://raw.githubusercontent.com/textileio/team-retreats/master/2020-hackathon/remote_config_for_apps.gif)

## Second Place

[@sanderpick](https://github.com/sanderpick)

**Filebox a desktop utility and mobile app to sync photos to your private Bucket**

Filebox is a macOS taskbar application much like Dropbox. When a user adds files and directories to their Filebox folder, they are synced to a Textile bucket under their control. Filebox is an example of a Textile Project created by a developer. The application embeds a project token that is used to register new users and manage threads.

![Demo Gif](https://raw.githubusercontent.com/textileio/team-retreats/master/2020-hackathon/developer_account_api_in_browser.gif)

## Third Place

[@jsign](https://github.com/jsign)

**Shoring erasure encoded data in Filecoin using Reed-Solomon.**

This hack is about making a simulator of [Reed-Solomon Encoding](https://en.wikipedia.org/wiki/Reed%E2%80%93Solomon_error_correction) on data to be stored in [Filecoin](https://filecoin.io). Each data and parity shard of the CAR file is stored as an independent deal. A tunable parameter for successful shard retrieval probability allows us to experience data reconstruction if the original data can't be fetched.

![Demo Gif](https://raw.githubusercontent.com/textileio/team-retreats/master/2020-hackathon/reed_solomon_erasure_encoding_over_filecoin.gif)

## Fourth Place

[@carsonfarmer](https://github.com/carsonfarmer)

**Running Automerge on Textile Threads to provide multi-user document editing.**

This work-in-process/experiment takes rich text document updates (via [quilljs](https://quilljs.com/)), passes these through a json-crdt (via [automerge](https://github.com/automerge/automerge)), and then communicates updates between collaborating peers via the low-level Threads protocol (via [js-threads](https://github.com/textileio/js-threads)). The result is a conflict-free collaborative editing environment, where all updates are end-to-end encrypted such that only collaborating peers with explicit access can participate.

![Demo Gif](https://raw.githubusercontent.com/textileio/team-retreats/master/2020-hackathon/crdt_automerge_over_threads.gif)

## Fifth Place

[@andrewxhill](https://github.com/andrewxhill)

**Builds a Textile Auth library and creates a basic web app for developers to manage accounts and projects.**

In this hack we generated a JavaScript client for the [cloud.textile.io](https://cloud.textile.io/) developer APIs. This allows a UI to be built around developer accounts, including session management, team and project management, bucket viewing, token management and more. The hack included a basic demo UI showing a simple login flow and review of projects the developer has already created using the command-line tool.

![Demo Gif](https://raw.githubusercontent.com/textileio/team-retreats/master/2020-hackathon/developer_account_api_in_browser.gif)