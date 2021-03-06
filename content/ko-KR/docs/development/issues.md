# Electron 이슈

# 이슈

* [이슈에 기여하는 방법](#how-to-contribute-in-issues)
* [일반적인 도움받기](#asking-for-general-help)
* [버그 신고하기](#submitting-a-bug-report)
* [Triaging a Bug Report](#triaging-a-bug-report)
* [Resolving a Bug Report](#resolving-a-bug-report)

## 이슈에 기여하는 방법

For any issue, there are fundamentally three ways an individual can contribute:

1. By opening the issue for discussion: If you believe that you have found a new bug in Electron, you should report it by creating a new issue in the `electron/electron` issue tracker.
2. By helping to triage the issue: You can do this either by providing assistive details (a reproducible test case that demonstrates a bug) or by providing suggestions to address the issue.
3. By helping to resolve the issue: This can be done by demonstrating that the issue is not a bug or is fixed; but more often, by opening a pull request that changes the source in `electron/electron` in a concrete and reviewable manner.

## 일반적인 도움받기

Because the level of activity in the `electron/electron` repository is so high, questions or requests for general help using Electron should be directed at the [community slack channel](https://atomio.slack.com) or the [forum](https://discuss.atom.io/c/electron).

## 버그 신고하기

When opening a new issue in the `electron/electron` issue tracker, users will be presented with a template that should be filled in.

```markdown
<!--
Thanks for opening an issue! A few things to keep in mind:

- The issue tracker is only for bugs and feature requests.
- Before reporting a bug, please try reproducing your issue against
  the latest version of Electron.
- If you need general advice, join our Slack: http://atom-slack.herokuapp.com
-->

* Electron version:
* Operating system:

### Expected behavior

<!-- What do you think should happen? -->

### Actual behavior

<!-- What actually happens? -->

### How to reproduce

<!--

Your best chance of getting this bug looked at quickly is to provide a REPOSITORY that can be cloned and run.

You can fork https://github.com/electron/electron-quick-start and include a link to the branch with your changes.

If you provide a URL, please list the commands required to clone/setup/run your repo e.g.

  $ git clone $YOUR_URL -b $BRANCH
  $ npm install
  $ npm start || electron .

-->
```

만약 여러분이 Electron의 버그를 찾았다고 확신하시면, 이 양식을 당신의 최고의 기술을 이용해 채워주세요.

The two most important pieces of information needed to evaluate the report are a description of the bug and a simple test case to recreate it. It easier to fix a bug if it can be reproduced.

See [How to create a Minimal, Complete, and Verifiable example](https://stackoverflow.com/help/mcve).

## Triaging a Bug Report

It's common for open issues to involve discussion. Some contributors may have differing opinions, including whether the behavior is a bug or feature. This discussion is part of the process and should be kept focused, helpful, and professional.

Terse responses that provide neither additional context nor supporting detail are not helpful or professional. To many, such responses are annoying and unfriendly.

Contributors are encouraged to solve issues collaboratively and help one another make progress. If encounter an issue that you feel is invalid, or which contains incorrect information, explain *why* you feel that way with additional supporting context, and be willing to be convinced that you may be wrong. By doing so, we can often reach the correct outcome faster.

## Resolving a Bug Report

주요 이슈들은 Pull Request를 열어 해결합니다. The process for opening and reviewing a pull request is similar to that of opening and triaging issues, but carries with it a necessary review and approval workflow that ensures that the proposed changes meet the minimal quality and functional guidelines of the Electron project.