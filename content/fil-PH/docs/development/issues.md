# Issues In Electron

# Isyu

* [Kung paano maka pag-ambag sa isyu](#how-to-contribute-in-issues)
* [Humingi nang pangkalahatang tulong](#asking-for-general-help)
* [Pagsusumite sa bug report](#submitting-a-bug-report)
* [Pagsasagawa sa bug report](#triaging-a-bug-report)
* [Paglutas sa bug report](#resolving-a-bug-report)

## Kung paano maka pag-ambag sa isyu

Para sa anumang isyu, merong mga panimula at tatlong pamamaraan na idibidwal na maka pag-ambag:

1. Sa pamamagitan nang pagbukas nang isyu para sa talakayan: Kung maniniwala ka na nahanap mo na ang bagong bug sa electron, kailangan mo itong iulat sa pamamagitan nang paggawa nang bagong isyu sa Ang`elektron/elektron`isyu tracker.
2. Sa pamamagitan nang pag tulong para sa traige ang isyu: Magagawa mo ito alinman sa pagbibigay nang tulong sa mga detalye (maaaring kopyahin nang pagsusulit na kaso na maipakita nang isang bug) o sa pamamagitan nang pagbibigay mungkahi sa address ang isyu.
3. Sa pamamagitan nang pagtulong upang malutas ang issue: Ito ay maaaring gawin sa pagpakita na ang isyu ay hindi bug o ito ay naayos na; pero kadalasan, sa pamamagitan nang pagbukas sa hilahin ang kahilingan na makapagbabago nang pinagmulan sa `elektron/elektron` sa isang kongreto at pagsusuring paraan.

## Humingi nang pangkalahatang tulong

Dahil ang antas nang aktibidad nasa `elektron/elektron` imbakan ay napakataas, mga tanong o hiling para sa pangkalahatang tulong sa paggamit elektron ay dapat na direktang sa [kommunidad malubay na channel](https://atomio.slack.com) o ang [forum](https://discuss.atom.io/c/electron).

## Pagsusumite sa bug report

Kapag nagbukas kanang bagong isyu sa `elektron/elektron` isyu tracker, mga gumagamit ay maipapakita na may isang template na dapat mapunan.

```markdown
&It;!--
Salamat sa pagbukas nang isyu! Ilang bagay na dapat tandaan:

- Ang isyu tracker ay para sa bugs at tampok na hiling.
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

If you believe that you have found a bug in Electron, please fill out this form to the best of your ability.

The two most important pieces of information needed to evaluate the report are a description of the bug and a simple test case to recreate it. It easier to fix a bug if it can be reproduced.

See [How to create a Minimal, Complete, and Verifiable example](https://stackoverflow.com/help/mcve).

## Pagsasagawa sa bug report

It's common for open issues to involve discussion. Some contributors may have differing opinions, including whether the behavior is a bug or feature. This discussion is part of the process and should be kept focused, helpful, and professional.

Terse responses that provide neither additional context nor supporting detail are not helpful or professional. To many, such responses are annoying and unfriendly.

Contributors are encouraged to solve issues collaboratively and help one another make progress. If encounter an issue that you feel is invalid, or which contains incorrect information, explain *why* you feel that way with additional supporting context, and be willing to be convinced that you may be wrong. By doing so, we can often reach the correct outcome faster.

## Paglutas sa bug report

Most issues are resolved by opening a pull request. The process for opening and reviewing a pull request is similar to that of opening and triaging issues, but carries with it a necessary review and approval workflow that ensures that the proposed changes meet the minimal quality and functional guidelines of the Electron project.