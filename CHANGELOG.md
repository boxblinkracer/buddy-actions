# Changes in Project

All notable changes of this project are documented in this file
using the [Keep a CHANGELOG](https://keepachangelog.com/) principles.

## [unreleased]

### Changed

- Update the **categories** of the actions. (I now know where they are displayed and it was wrong).
- Increased max. tokens of OpenAI action to be 500 to avoid truncation of results.

## [1.1.0]

### Added

- Added new action **Create OpenAI Image** to automatically generate images using AI.
- Added **display title** to all actions. A good name instead of the technical name is now displayed.
- Added selection of **models** to the OpenAI action. This allows you to select the model you want to use.

### Fixed

- The Buddy action **Ask OpenAI** will now correctly fail if OpenAI returns an error.

## [1.0.0]

### Added

- Add new action "Ask OpenAI" to ask for a prompt. The result can then be used in the pipeline.
- Add new action "Deployment Slack" notifications. This allows to send deployment notifications to your team in Slack
  when deployments start, succeed, fail or are canceled.
