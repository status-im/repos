# Status Repositories

Overview of all repositories we have.

Soon we are going to need a [list of lists of lists](https://en.wikipedia.org/wiki/List_of_lists_of_lists)

## Table of Contents

- [Protocol](#protocol)
- [General (dev)](#general-dev)

## Protocol

Questions? Ping @oskarth or #status-protocol in Status.

For w3f/messaging, this Riot channel is used https://riot.im/app/#/room/#web3-messaging:matrix.org

- https://github.com/status-im/specs/ - Specifications for Status clients. Things that are live.
- https://github.com/status-im/status-research - Research Proof of Concept implementations.
- https://github.com/status-im/bigbrother-specs/ - Research and specification for (new) Big Brother protocol.
- https://github.com/w3f/messaging - Messaging for Web3, cross-team collaboration for transport privacy / mixnet layer.
- https://github.com/status-im/messaging-pm/ - PM for w3f/messaging calls.
- https://github.com/status-im/mvds - minimal viable data sync implementation.
- github.com/status-im/staples - PoC for Swarm/Feeds/PSS chat.

## General (dev)

- https://github.com/status-im/swarms - Swarm Home. New, completed and in-progress features for Status
- https://github.com/status-im/pm/ - PM for core dev calls.
- https://github.com/status-im/nixpkgs - Fork of NixOS/nixpkgs, where we keep our `status-mods` branch used by `status-react`

## Bots

- https://github.com/status-im/status-github-bot - A bot for github (kicks e2e tests, among other tasks)
- https://github.com/status-im/probot-settings - Keeps the baseline settings for probot apps that can be referenced from other repos 
- https://github.com/status-im/packages-check-bot - This Probot checks changes to packages.json to ensure that URL schemes match intended pattern and that forks are referenced with a tag, instead of a branch
- https://github.com/status-im/deps-lock-snitch-bot - A GitHub App built with Probot that pings collaborators every time there are changes to a dependency lock file (package-lock.json, yarn.lock, etc)
- https://github.com/status-im/stale - A GitHub App built with Probot that closes abandoned Issues and Pull Requests after a period of inactivity.
- https://github.com/status-im/figma-diff-probot - Probot using figma api to comment on PRs with before after images 
